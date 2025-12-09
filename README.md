# Solana Dynamic NFT Project

## Overview
The Solana Dynamic NFT project is designed to create and manage dynamic NFTs on the Solana blockchain. This project encompasses a complete workflow from idea generation to the final 3D art representation, allowing users to interact with various stages of the NFT creation process.

## Project Structure
The project is divided into two main parts: **frontend** and **backend**.

### Frontend
The frontend is built using Next.js and TypeScript, providing a user-friendly interface for interacting with the NFT project.

- **Pages**:
  - `index.tsx`: Overview and introduction to the project.
  - `inspiration.tsx`: A space for users to view and submit ideas.
  - `design.tsx`: A section for users to view and submit design drafts.
  - `modeling.tsx`: A page for users to view and submit 3D models.
  - `rendering.tsx`: A section for users to view and submit rendered images.
  - `gallery.tsx`: A gallery showcasing all stages of the project.

- **Components**:
  - `Header.tsx`: Navigation and title component.
  - `Footer.tsx`: Footer component with copyright and links.
  - `NFTCard.tsx`: Component for displaying NFT details.
  - `Viewer3D.tsx`: Component for showcasing 3D models.

- **Styles**:
  - `globals.css`: Global styles for the application.

### Backend
The backend is built using Node.js and TypeScript, providing the necessary APIs for NFT management.

- **Routes**:
  - `metadata.ts`: Handles NFT metadata operations.
  - `attestation.ts`: Manages NFT attestation processes.
  - `onchain.ts`: Handles on-chain updates for NFTs.

- **Controllers**:
  - `metadataController.ts`: Contains methods for getting and updating NFT metadata.
  - `attestationController.ts`: Contains methods for NFT attestation.

- **Services**:
  - `ipfsService.ts`: Interacts with IPFS for asset storage.
  - `solanaService.ts`: Manages interactions with the Solana blockchain.
  - `rendererService.ts`: Handles rendering processes.

### Programs
The project includes a Solana program defined in Rust, which manages the logic and state of the NFTs.

### Models
The project contains source files for 3D models and exports them in a usable format.

### Tools
Tools for off-chain rendering and deployment scripts are included to facilitate the development and deployment process.

## Getting Started
To get started with the project, clone the repository and install the necessary dependencies for both the frontend and backend. Follow the instructions in the respective `README.md` files located in the `frontend` and `backend` directories for detailed setup and usage instructions.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.