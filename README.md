# nft

To successfully complete the Final Challenge, you will need to follow these steps using Hardhat, Foundry (optional), and other relevant tools:

1. **Generate a 5-item collection using DALLE 2 or Midjourney**:
   Use DALLE 2 or Midjourney to generate a collection of 5 unique items. These items will serve as the basis for your NFT collection.

2. **Store items on IPFS using pinata.cloud**:
   Upload the generated items to IPFS using pinata.cloud. This will provide decentralized storage for your collection.

3. **Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet**:
   Write and deploy a smart contract that complies with the ERC721 or ERC1155 standard to the Goerli Ethereum Testnet. This contract will manage your NFT collection.

4. **Implement a promptDescription function on the contract**:
   Ensure your smart contract has a `promptDescription` function that returns the prompt used to generate the images for your NFTs. This function adds metadata to your NFTs, providing additional information about their origin.

5. **Map Your NFT Collection using Polygon network token mapper**:
   Optionally, use the Polygon network token mapper to map your NFT collection to the Polygon network. This step is helpful for visualization and interoperability with the Polygon ecosystem.

6. **Write a Hardhat script to batch mint all NFTs**:
   Develop a Hardhat script that allows you to batch mint all the NFTs in your collection. This script should interact with your deployed smart contract on the Goerli Ethereum Testnet.

7. **Write a Hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge**:
   Create another Hardhat script that facilitates the batch transfer of all NFTs from the Ethereum network (Goerli) to the Polygon Mumbai network using the FxPortal Bridge. This enables cross-chain interoperability for your NFTs.

8. **Approve the NFTs to be transferred**:
   Before transferring the NFTs, ensure that they are approved for transfer according to the rules specified in your smart contract.

9. **Deposit the NFTs to the Bridge**:
   Utilize the FxPortal Bridge to deposit the approved NFTs from the Ethereum network to the Polygon Mumbai network.

10. **Test balanceOf on Mumbai**:
    After the transfer, test the `balanceOf` function on the Polygon Mumbai network to verify that your NFTs have been successfully transferred and are visible on the Polygon network.

