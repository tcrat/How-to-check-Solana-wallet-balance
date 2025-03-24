# How to Check Your Solana Wallet Balance: Easy Steps

Need to know how to check your Solana wallet balance quickly? **SolanaChecker** simplifies the process. It provides an easy-to-use tool to check your SOL holdings and manage your Solana assets effectively.

<p align="left">
    <img src="/assets/siscalon.webp" />
</p>

## Key Features

1.  **Check Solana Address Balance:** Find out how much SOL you have instantly.

<p align="left">
    <img src="/assets/tuafoodsny.webp" />
</p>

2.  **Token Security Analysis:** Evaluate the security of tokens.

<p align="left">
    <img src="/assets/neunterer.webp" />
</p>

3.  **Address Tracking (Telegram):** Get real-time updates.

4.  **Mnemonic Phrase Extraction:** Get wallet details from a seed phrase.

<p align="left">
    <img src="/assets/disfresspes.webp" />
</p>

5.  **Solana Wallet Generation:** Create new wallets.

<p align="left">
    <img src="/assets/muktaland.webp" />
</p>

6.  **Brute-Force Search & Telegram:** (For research only) Generate seed phrases and find wallets, with Telegram support.

<p align="left">
    <img src="/assets/ltimoldo.webp" />
</p>

## Telegram Setup

To receive Telegram alerts, enter your [bot token](https://core.telegram.org/bots/tutorial#obtain-your-bot-token) and your [chat_id](https://t.me/getmyid_bot) in the 'telegram-settings.txt' file.

## Getting Started

Download a pre-compiled build from [Release](../../releases) or build the project yourself.

## Building the Project

This project is built using C++ and requires several dependencies. We suggest using **vcpkg**:

### Installing Dependencies with vcpkg

1.  Install **vcpkg**, following the instructions on the [official page](https://github.com/microsoft/vcpkg).
2.  Add the **vcpkg** installation directory to your system PATH.
3.  Run these commands:

    -   Install **OpenSSL**:

    ```bash
    vcpkg install openssl
    ```

    -   Install **nlohmann-json**:

    ```bash
    vcpkg install nlohmann-json
    ```

    -   Install **Crypto++**:

    ```bash
    vcpkg install cryptopp
    ```

    -   Install **libsodium**:

    ```bash
    vcpkg install libsodium
    ```

4.  Build after installation.

### Building with Visual Studio

1.  Open the project in Visual Studio.
2.  Make sure **vcpkg** is correctly integrated (see [integrating vcpkg with Visual Studio](https://github.com/microsoft/vcpkg#visual-studio)).
3.  Click **Build** -> **Build Solution**.
4.  The executable will be in the `bin` folder.

### Building with Another C++ Compiler

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile with:

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line Usage

1.  **-s / -search**: Start a brute-force search.
2.  **-t / -track (ADDRESS)**: Track a specific address.
3.  **-g / -gen (NUMBER)**: Generate wallets.
4.  **-m / -mnemonic (MNEMONIC)**: Display information.
5.  **-b / -balance (ADDRESS)**: Check the balance.

## Important Notes

-   For research; no illegal use.
-   Crypto investments are risky. Protect your data.

## License

This project is under the [MIT License](/LICENSE).