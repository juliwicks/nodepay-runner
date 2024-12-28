# NodePay Runner Bot

Welcome to the NodePay Runner Bot! This script allows you to efficiently manage multiple accounts and proxies for NodePay.

## Prerequisites

Before running the script, make sure you have Python installed on your system. If Python is not already installed, follow the steps below to install it:

### Installing Python

1. Visit the [Python Downloads page](https://www.python.org/downloads/).
2. Download the appropriate version for your operating system.
3. Install Python by following the installation instructions for your OS.
   - **Windows**: Ensure you check the option to add Python to your PATH during installation.
   - **macOS/Linux**: Follow the instructions provided on the Python website or use your package manager (e.g., `brew` for macOS or `apt` for Linux).

To verify the installation, run the following command in your terminal:

```bash
python3 --version
```

You should see the Python version printed in the terminal.

---

## Installation Instructions

1. Clone the NodePay Runner repository:

```bash
git clone https://github.com/juliwicks/nodepay-runner
```

2. Navigate to the project directory:

```bash
cd nodepay-runner
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Ensure you have two files in the project directory:
   - `tokens.txt`: A file containing your NodePay tokens (one token per line).
   - `proxies.txt`: A file containing your proxy list (one proxy per line).

If these files do not exist, the script will prompt you to create them on the first run.

---

## Running the Script

To start the bot, run the following command:

```bash
python3 main.py
```

Follow the on-screen instructions. The bot will handle multiple accounts and proxies automatically.

---

## Stopping the Script

To stop the script, press **Ctrl+C** in the terminal. The program will gracefully terminate and save any necessary session information.

---

## Troubleshooting

- If you encounter any issues during installation or running the script, ensure all dependencies are installed correctly by running:

```bash
pip install -r requirements.txt
```

- Verify that `tokens.txt` and `proxies.txt` files are correctly formatted and located in the project directory.

- Check the logs for any error messages and refer to the repository documentation for further assistance.

---

## License

This project is licensed under the MIT License. For more details, see the `LICENSE` file in the repository.

---

Happy botting!
