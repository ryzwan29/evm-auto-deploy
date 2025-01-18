# EVM Auto Deploy

A tool for automatically deploying Ethereum smart contracts to various networks.

## Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)
- Ethereum private key
- Ethereum RPC node URL

## Getting Started

To use **EVM Auto Deploy**, follow these steps:

1. Install with script
   ```
   source <(curl -s https://raw.githubusercontent.com/ryzwan29/evm-auto-deploy/main/quick-installation.sh)
   ```

3. Rename the file `.env.example` to `.env`
   ```
   mv .env.example .env
   ```
   - `PRIVATE_KEY`: Your Ethereum private key

4. Add your desired chain configuration to `chains/testnet.json` or `chains/mainnet.json`.

5. Run the script:

   ```bash
   npm start
   ```

## Donations

If you would like to support the development of this project, you can make a donation using the following addresses:

- **Solana**: `GLQMG8j23ookY8Af1uLUg4CQzuQYhXcx56rkpZkyiJvP`
- **EVM**: `0x960EDa0D16f4D70df60629117ad6e5F1E13B8F44`
- **BTC**: `bc1p9za9ctgwwvc7amdng8gvrjpwhnhnwaxzj3nfv07szqwrsrudfh6qvvxrj8`

## License

**EVM Auto Deploy** is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
