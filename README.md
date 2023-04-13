# Tenderly Node Extension Library

<div align="center">
    <a href="https://tenderly.co">
        <img src="https://storage.googleapis.com/tenderly-public-assets/node-extensions/node-extensions.png" alt="tenderly-logo" width="100%" height="auto" style="background-color: #ffffffb2;padding: 10px 20px;box-sizing: border-box;max-width:200px;" />
    </a>
</div>


This library is a collection of Tenderly Node Extensions. It’s used to extend Tenderly Web3 Gateway, our Node-as-a-Service, with additional functionalities.

Node Extensions are a game-changing enhancement to our existing production node. This feature allows devs to create custom JSON-RPC method names and write custom JS/TS code snippets that are executed each time the method is called. It’s like having your very own sorcerer’s apprentice working behind the scenes! 🧙‍

> **Note:** Node Extensions require @tenderly/actions version >= **0.2.0**.

## How to use

Go to the Extensions Library and search for the extension that you want to include in your Web3 Gateway. Click on the extension and click "Activate".
Once activated, go to JSON-RPC Request Builder and select your extension method from the dropdown menu. You can then enter the JSON payload and click "Send Request".

## Node Extension Examples

To get started creating your own node extensions, you can use the following Node Extension Starter Pack:

- [node-extension-starter](./node-extension-starter) - This Node Extension gets the current block number.
- [node-extension-starter-jest](./node-extension-starter-jest) - This Node Extension gets the current block number and has the Jest testing library installed.

Here are examples of Node Extensions that you can use in your projects:

- [chainlink-price-feed](./chainlink-price-feed) - Use this Node Extension to query Chainlink Price Feeds.
- [multicall-uniswap-erc20-balance](./multicall-uniswap-erc20-balance) - This Node Extension uses Wonderland's multicall strategy to quickly fetch Uniswap's ERC20 balances.
- [pm-can-sponsor-user-operation](./pm-can-sponsor-user-operation) - Use this Node Extension to check whether Pimlico's Paymaster service can sponsor a User Operation on behalf of a third-party dapp.
- [pm-sponsor-user-operation](./pm-sponsor-user-operation) - This Node Extension asks Pimlico's Paymaster to sponsor a submitted User Operation on behalf of a wallet.
- [pm-supported-entry-points](./pm-supported-entry-points) - This Node Extension returns the list of entryPoint contracts that are supported on the chain you’re using.
- [polygon-block-author](./polygon-block-author) - Use this Node Extension to get the block author for a given block number on Polygon (Matic) network.
- [simulate-mempool-transaction](./simulate-mempool-transaction) - This Tenderly Node Extension allows you to simulate a transaction in the mempool.
- [simulate-send-transaction](./simulate-send-transaction) - This Tenderly Node Extension allows you to simulate a transaction before sending on-chain.
