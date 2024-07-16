# IoTeX Chain Assets Repository

Welcome to the IoTeX Chain Assets Repository. This repository is designed to maintain and share information about assets on the IoTeX blockchain, including XRC20 tokens, logos, and other related information.

## Table of Contents

- [Introduction](#introduction)
- [Structure](#structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository aims to provide a centralized resource for tracking and managing assets on the IoTeX blockchain. We welcome contributions from the community to help keep the information accurate and up-to-date.

## Structure

The repository is organized as follows:

```
.
├── README.md
├── assets
│   ├── xrc20
│   │   ├── token1
│   │   │   ├── info.json
│   │   │   └── logo.png
│   │   ├── token2
│   │   │   ├── info.json
│   │   │   └── logo.png
│   │   └── ...
└── ...
```

- `README.md`: This file.
- `assets`: Directory containing information about assets.
  - `xrc20`: Subdirectory for XRC20 tokens.
    - Each token has its own subdirectory, named after the token.
    - Each token subdirectory contains:
      - `info.json`: JSON file with information about the token (e.g., name, symbol, contract address).
      - `logo.png`: Logo image of the token.

## Contributing

We welcome contributions from the community! To add or update information in this repository, please follow these steps:

1. **Fork the repository**: Create a fork of this repository in your GitHub account.
2. **Clone your fork**: Clone your fork to your local machine.
    ```sh
    git clone https://github.com/<your-username>/iotex-assets.git
    cd iotex-assets
    ```
3. **Create a new branch**: Create a new branch for your changes.
    ```sh
    git checkout -b add-token-xyz
    ```
4. **Add your changes**: Add information about your asset in the appropriate directory. Ensure the `info.json` and `logo.png` files are correctly named and formatted.
5. **Commit your changes**: Commit your changes with a descriptive message.
    ```sh
    git add .
    git commit -m "Add XYZ token information"
    ```
6. **Push to your fork**: Push your changes to your fork on GitHub.
    ```sh
    git push origin add-token-xyz
    ```
7. **Create a pull request**: Open a pull request to the main repository.

### JSON File Format



## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
