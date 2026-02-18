# WormGPT Python Script

This script is a Python-based terminal client for interacting with an AI persona. It provides a conversational interface with customizable text colors for user and AI responses.

## Features

- AI persona with a predefined character.
- Interactive chat interface.
- Customizable text colors for better readability.

---

## Prerequisites

To run this script, you need to install the following dependencies:

### Python Requirements

- Python 3.6 or higher
- Required Python libraries:
  - `requests`
  - `colorama`

### Supported Environments

- Termux (Android)
- Ubuntu Terminal
- Kali Linux Terminal

---

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/Danarfr27/WORM-PY.git
cd WORM-PY
```

### 2. Install Python

Ensure Python is installed on your system. For Termux, Ubuntu, or Kali Linux, use the following commands:

#### Termux:

```bash
pkg install python
```

#### Ubuntu/Kali Linux:

```bash
sudo apt update
sudo apt install python3
```

### 3. Install Required Libraries

Install the required Python libraries using `pip`:

```bash
pip install requests colorama
```

---

## Usage

### 1. Run the Script

To start the script, use the following command:

```bash
python3 worm.py
```

### 2. Interact with the AI

- Type your message and press Enter to interact with the AI.
- Use the following commands:
  - `exit` or `keluar` to exit the script.
  - `reset` to reset the conversation.

---

## Notes

- Ensure you have a stable internet connection as the script interacts with an external API.
- The API URL is predefined in the script. Update it if necessary.

---

## Troubleshooting

### Common Issues

1. **`requests` library not found:**
   - Ensure you have installed the `requests` library using `pip install requests`.

2. **Permission Denied:**
   - Ensure the script has executable permissions:
     ```bash
     chmod +x worm.py
     ```

3. **Connection Errors:**
   - Check your internet connection.
   - Verify the API URL in the script.

---

Enjoy using WormGPT!
