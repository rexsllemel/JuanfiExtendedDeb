# JuanfiExtended Debian Package

## Installation

### Option 1: Install from Repository (Recommended)

Add the repository and install using apt:

```bash
echo "deb [trusted=yes] https://rexsllemel.github.io/JuanfiExtendedDeb/ ./" | sudo tee /etc/apt/sources.list.d/juanfiextended.list

sudo apt update
sudo apt install juanfiextended
```

### Option 2: Manual Installation

Clone the repository and install the .deb package directly:

```bash
git clone https://github.com/rexsllemel/JuanfiExtendedDeb.git

cd JuanfiExtendedDeb && dpkg -i JuanfiExtended_*.deb
```
