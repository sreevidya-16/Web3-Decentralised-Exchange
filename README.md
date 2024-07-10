# Web3 Decentralized Exchange

## Overview

This project is a fully functional Web3 Decentralized Exchange (DEX) that allows users to swap ERC20 tokens on a selected EVM chain. The DEX integrates various technologies to provide a seamless and efficient token swapping experience.

## Features

-   **Token Swapping**: Users can easily swap ERC20 tokens to other ERC20 tokens.
-   **EVM Chain Support**: Supports token swaps on multiple EVM-compatible chains.
-   **Real-time Data**: Leverages Moralis Web3 API and 1Inch Aggregator for real-time data and optimal swap rates.
-   **User-friendly Interface**: Built with React and Wagmi for an intuitive and responsive user interface.
-   **Backend Integration**: NodeJS is used for server-side operations and API integrations.

## Technologies Used

-   **Moralis Web3 API**: To interact with the blockchain and fetch real-time data.
-   **1Inch Aggregator**: For aggregating multiple DEXs to find the best swap rates.
-   **Wagmi**: A set of React hooks for Ethereum, used to manage user wallets and connections.
-   **React**: For building the user interface.
-   **NodeJS**: For backend server operations and API integrations.

## Installation

1.  Clone the repository

    
2.  Install the dependencies:

         npm install
    
4.  Set up environment variables: Create a `.env` file in the root directory and add the following variables:
    
		    REACT_APP_MORALIS_API_KEY=your-moralis-api-key
    
		    REACT_APP_1INCH_API_URL=https://api.1inch.exchange/v3.0/
    
		    REACT_APP_CHAIN_ID=your-chain-id
    
5.  Start the development server:
    
			   npm start
    

## Usage

1.  **Connect Wallet**: Use the Wagmi hook to connect your wallet to the DEX.
2.  **Select Tokens**: Choose the ERC20 tokens you want to swap.
3.  **Swap Tokens**: Execute the swap and view the transaction details.

## Conclusion
This Web3 Decentralized Exchange project showcases the potential of decentralized finance (DeFi) by providing a seamless and efficient platform for swapping ERC20 tokens on EVM-compatible chains. By leveraging cutting-edge technologies such as the Moralis Web3 API, 1Inch Aggregator, Wagmi, React, and NodeJS, we have created an application that not only offers optimal swap rates but also ensures a user-friendly experience.

We believe that this project can serve as a foundation for future enhancements and integrations, further expanding the capabilities of decentralized exchanges. We encourage the community to contribute and collaborate, as we continue to innovate and push the boundaries of what is possible in the world of DeFi.


## License

This project is licensed under the MIT License.
