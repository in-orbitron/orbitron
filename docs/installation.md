# Installation

To install Orbitron, follow the instructions for your preferred method below.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Windows](#windows)
  - [Installing Prerequisites on Windows](#installing-prerequisites-on-windows)
  - [Installing Orbitron on Windows](#installing-orbitron-on-windows)
- [Linux](#linux)
  - [Installing Prerequisites on Linux](#installing-prerequisites-on-linux)
  - [Installing Orbitron on Linux](#installing-orbitron-on-linux)

## Prerequisites

Before installing Orbitron, ensure that your system meets the following requirements:

| Requirement | Description | Version |
|-------------|-------------|---------|
| Operating System | Supported OS for Orbitron | Windows, Linux |
| Python | Python interpreter | 3.13 or higher |
| Git | Version control system | Latest stable version |
| UV | Python package manager | Latest stable version |

## Windows

For Windows, follow the steps below to install Orbitron and its prerequisites.

### Installing Prerequisites on Windows

Use the links below to download and install the required prerequisites:

| Requirement | Web page | URL |
|-------------|-------------|-----|
| Python | Official Python website | https://www.python.org/ |
| Git | Official Git website | https://git-scm.com/ |
| UV | UV package manager website | https://docs.astral.sh/uv/ |

### Installing Orbitron on Windows

After installing the prerequisites, follow these steps to install Orbitron on Windows:

1. Open a terminal or command prompt.
2. Clone the Orbitron repository:
   ```cmd
   git clone https://github.com/in-orbitron/orbitron.git
   ```
3. Navigate to the cloned directory:
   ```cmd
   cd orbitron
   ```
4. Install Orbitron using UV:
   ```cmd
   uv sync
   ```
5. Verify the installation by running:
   ```cmd
   uv run python -m orbitron
   ```

## Linux

For Linux, follow the steps below to install Orbitron and its prerequisites.

### Installing Prerequisites on Linux

Use the package manager for your Linux distribution to install the required prerequisites. For example, on Debian-based systems:

```bash
sudo apt update
sudo apt install python3 python3-pip git
```

Check the installed Python version to ensure it meets the requirement:

```bash
python3 --version
```

If the installed Python version is lower than 3.13, you need to upgrade Python before proceeding. Use the instructions provided on the [official Python website](https://www.python.org/) to install the latest version of Python for linux systems.

Follow the instructions on the [official UV documentation](https://docs.astral.sh/uv/) to install UV on your Linux system.

**Note:** If you install uv and your Python version is lower than 3.13, you can use it to install the required Python version using the command:

```bash
uv install python 3.13
```

### Installing Orbitron on Linux

After installing the prerequisites, follow these steps to install Orbitron on Linux:

1. Open a terminal.
2. Clone the Orbitron repository:
   ```bash
   git clone https://github.com/in-orbitron/orbitron.git
   ```
3. Navigate to the cloned directory:
   ```bash
   cd orbitron
   ```
4. Install Orbitron using UV:
   ```bash
   uv sync
   ```
5. Verify the installation by running:
   ```bash
   uv run python -m orbitron
   ```