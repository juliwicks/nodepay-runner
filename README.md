# NodePay Runner Bot

Welcome to the NodePay Runner Bot! This script allows you to efficiently manage multiple accounts and proxies for NodePay.

## Prerequisites

Before running the script, make sure you have Python installed on your system. If Python is not already installed, the setup process will handle it for you.

### Quick Setup One-Liner

Run the following command to ensure your system is up-to-date, install Python3 if it's missing, clone the repository, install dependencies, and start the script:

```bash
sudo apt update && sudo apt install -y python3 python3-pip git && git clone https://github.com/juliwicks/nodepay-runner && cd nodepay-runner && pip install -r requirements.txt && python3 main.py
```

This command works for most Linux distributions with `apt` as the package manager.

---

## Detailed Installation Instructions

If you prefer step-by-step instructions, follow these:

1. **Update your system and install Python3 (if not installed):**

```bash
sudo apt update && sudo apt install -y python3 python3-pip
```

2. **Clone the NodePay Runner repository:**

```bash
git clone https://github.com/juliwicks/nodepay-runner
```

3. **Navigate to the project directory:**

```bash
cd nodepay-runner
```

4. **Install the required dependencies:**

```bash
pip install -r requirements.txt
```

5. **Ensure you have two files in the project directory:**
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
