# BBEARSV1-Rare-NFT's

## Getting Started

Install the latest version of the SDK:

npm install @thirdweb-dev/sdk ethers@5

Initialize the SDK and contract on your project:

import { ThirdwebSDK } from "@thirdweb-dev/sdk/evm";

const sdk = new ThirdwebSDK("binance");
const contract = await sdk.getContract("0x84ec8A6AA5D265158Fd1038d515b931957170DEC");

