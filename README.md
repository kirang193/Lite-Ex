# Lite-Ex

This application is designed to extract packet-based and flow-based features from Pcap files. The executable is built using **Scapy**.

## Prerequisites

Ensure that you have the following software installed on your system:

1. **Ubuntu 24.04 LTS**
2. **Python 3** (for running dependencies)
3. **Scapy** (installed using `pip`)

---

## Installation Instructions

## 1. Install Dependencies on Ubuntu 24.04 LTS

Before running the application, you need to ensure that the required dependencies are installed:

#### a. Install Python 3 and pip
Make sure **Python 3** and **pip** (Python's package manager) are installed on your system.

```bash
sudo apt update
sudo apt install python3 python3-pip
```
### b. Install Scapy

The application relies on Scapy, which is installed via pip. Run the following command to install Scapy version 2.6.1:

```bash
pip3 install scapy==2.6.1
```
### c. Check ldd Version

Ensure that the correct version of ldd (used to check shared libraries) is installed. For Ubuntu 24.04 LTS, the following version should be present:

```bash
ldd --version
```
You should see the following output (or similar):
```
ldd (Ubuntu GLIBC 2.39-0ubuntu8.4) 2.39
```

## 2. Clone the Repository

Clone the repository containing the pkt2flow source code and install pkt2flow module

```bash
git clone https://github.com/kirang193/pkt2flow.git
cd pkt2flow
scons
```

## 3. Download and Run the Executable

```bash
git clone https://github.com/kirang193/Lite-Ex.git
cd Lite-Ex
chmod +x LiteEx
./LiteEx
```

## 📢 Note for Ubuntu 22.04 (ldd 2.35)

If you're using Ubuntu 22.04 with ldd version 2.35, you can download the pre-built executable for Ubuntu 22.04 from the following link:

[Download](https://drive.google.com/file/d/1-NZFRgAssvW3--A6OPn3V97fD5p4zRIq/view?usp=sharing) the executable for Ubuntu 22.04 (ldd 2.35)


 
