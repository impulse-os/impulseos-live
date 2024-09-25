# Impulse OS

Impulse OS is a custom Linux distribution based on Arch Linux, designed for simplicity, performance, and a user-friendly experience. This project aims to provide an efficient and aesthetically pleasing operating system, utilizing a minimal yet functional environment.

## Features

- **Based on Arch Linux**: Enjoy the rolling release model with the latest packages and features.
- **Custom Installer**: A rebranded installer named `impulseinstall`, providing an intuitive installation process.
- **Minimalist Desktop Environment**: Choose from various desktop environments to suit your needs.
- **User-Centric Design**: Focus on usability and aesthetics with custom themes and wallpapers.

## Table of Contents

- [Installation](#installation)
- [Customization Steps](#customization-steps)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Download the Impulse OS ISO**: Visit the [releases page](#) to download the latest ISO image.
2. **Create a Bootable USB Drive**:
   ```bash
   sudo dd if=impulse-os.iso of=/dev/sdX bs=4M status=progress oflag=sync
   ```
   Replace `/dev/sdX` with your USB device identifier.
3. **Boot from USB**: Insert the USB drive into your computer and boot from it.
4. **Run the Installer**: Once in the live environment, run the installer by executing:
   ```bash
   impulseinstall
   ```
5. **Follow the Prompts**: The installer will guide you through the installation process.

## Customization Steps

To contribute to or modify Impulse OS, follow these steps:

1. **Create Live Environment**
   - Set up archiso and customize the live session configuration.
   - Modify `packages.x86_64` to include necessary packages.

2. **Customize the Installer**
   - Fork the Archinstall repository and rename it to `impulseinstall`.
   - Rebrand the installer and modify user-facing texts.

3. **Configure Installation Process**
   - Create profiles for Impulse OS and customize the installer interface.
   - Add dialog or TUI elements for better user interaction.

4. **Customize OS Configuration**
   - Use post-install scripts to set system configurations, themes, and services.
   - Modify `/etc/skel/` to define the default user environment.

## Usage

After installation, enjoy the following features:

- Choose your preferred desktop environment during installation.
- Access a minimal yet powerful application suite pre-installed.
- Customize your environment further using the package manager.

## Contributing

We welcome contributions to Impulse OS! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request detailing your changes.

## License

Impulse OS is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for trying out Impulse OS! We hope you enjoy your experience. For any issues or suggestions, please open an issue on the GitHub repository.