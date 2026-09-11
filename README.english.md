# ENI-VULogger

ENI-VULogger is a free application designed for amateur radio operators participating in VHF and UHF contests. Developed with the goal of providing an intuitive and easy-to-use interface, it includes the essential features required for contest operation and QSO logging. Although the project is still under active development, it continues to evolve with the primary objective of expanding compatibility with a growing number of contests and adding new features that meet the needs of the amateur radio community.

## Features

- Add, edit, sort, and delete QSOs.
- Automatic date/time handling with display of local time and configured UTC time.
- Distance calculation between the station locator and the correspondent's locator.
- Detection of potentially duplicate contacts with visual indication.
- Automatic STX numbering per band and preservation of the received SRX.
- Score and multipliers displayed by band and as a total.
- Save and load QSOs in JSON format.
- ADIF, EDI, and Excel import/export, plus Cabrillo export.
- Light/dark themes, statistics window, and built-in user manual.

## Screenshot

<img width="1238" height="596" alt="ENI-VULogger Screenshot" src="https://github.com/user-attachments/assets/cbdaeb06-cabe-417c-aa26-af654b9c6e50" />

## Compatibility

ENI-VULogger is supported on:

- Windows 10
- Windows 11
- x86 and x64 systems
- Windows ARM64 through emulation

Windows 7 is not officially supported due to the end of support for the Microsoft Edge WebView2 Runtime on that operating system.

## Supported Export Formats

ADIF, EDI, Cabrillo, Excel, and JSON.

## Supported Import Formats

ADIF, EDI, Excel, and JSON.

## Supported Contests

- Dia de Portugal VHF/UHF — REP
- ARAM VHF/UHF — ARAM
- Combinado V/UHF — URE
- Segóvia EA1RCS V/UHF — URE
- Nacional V/UHF — URE
- Atlántico V/UHF — URE
- Costa del Sol V/UHF — URE
- QSL V/UHF — URE
- IARU Region 1 VHF Contest (144 MHz)
- IARU Region 1 UHF Contest (432 MHz)
- IARU Region 1 SHF Contest (1296 and 2300 MHz)
- Marconi Memorial VHF Contest
- DARC VHF Contest
- DARC UHF Contest
- REF VHF Contest
- ARI International 50 MHz Contest
- Custom contest with a ×1 multiplier on all bands

## Downloading the Application

At the bottom of this page, download files with names similar to:

- ENI-VULogger_v0.26.0.0.zip
- Manual_ENI-VULogger_v0.26.0.0.pdf

**Important:** Do not download **Source code (zip)** or **Source code (tar.gz)**. These files contain the project source code and are not the ready-to-run application.

## Extracting the ZIP File

After the download is complete:

- Open the Downloads folder or the folder where the file was saved.
- Right-click the ZIP file.
- Select **Extract All...**
- Choose the destination folder.
- Click **Extract**.

For example:

`C:\ENI-VULogger\`

Do not run the application directly from inside the ZIP file.

## Running the Application

Open the extracted folder and run:

`ENI_VULogger.exe`

The folder may also contain libraries, configuration files, and subfolders required for proper operation.

Do not delete or move the executable file on its own. Keep all files and folders extracted from the ZIP package together and unchanged.

### Windows Security Warning

The first time you run the application, Windows may display a security warning because the file was downloaded from the Internet.

If the **"Windows protected your PC"** dialog appears:

- Verify that you downloaded the application from the official repository.
- Click **More info**.
- Click **Run anyway**.

On some systems, you may need to:

- Right-click `ENI_VULogger.exe`
- Select **Properties**

If an **Unblock** option is available:

- Check **Unblock**
- Click **Apply**
- Click **OK**
- Run the application again

## Requirements

The current version is intended for:

- Windows 10
- Windows 11
- x86 and x64 systems
- Windows ARM64 through emulation, depending on system configuration

The application uses the Microsoft Edge WebView2 Runtime. If WebView2 is not available, the application window may not open correctly.

Windows 7 and Windows 8/8.1 are not officially supported.

## First Use

When running the application for the first time, fill in the operating information:

- Callsign
- Name
- QTH Locator
- Local time offset from UTC
- Contest
- Operator category
- Power
- Station type

Then click **Save**.

The configuration window can also be opened through:

- The **Configuration** button
- Pressing **F2**

## Creating a Desktop Shortcut

To create a desktop shortcut:

- Right-click `ENI_VULogger.exe`
- Select **Show more options** if necessary
- Choose **Send to**
- Select **Desktop (create shortcut)**

Do not move only the executable file to the desktop. Use a shortcut so the application can continue to access all required files within its installation folder.

## Updating to a New Version

Before updating:

1. Open the current version.
2. Use **Save QSOs** to create a backup in JSON format.
3. Export the operator configuration as well.
4. Close the application.
5. Download the new version.
6. Extract the ZIP file to a new folder (for example, a folder containing the new version number).
7. Run the new version.
8. Load the previously saved configuration and QSOs.

It is recommended not to immediately delete the old folder. Keep it until you have confirmed that the new version works correctly and that all data has been restored.

Currently, ENI-VULogger is not distributed with a traditional installer.

It behaves as a **portable application**:

- The application runs directly from the extracted folder.
- All required files are supplied in the same package.
- The folder can be copied to another compatible computer.
- The program should not be run directly from inside the ZIP file.

**Recommendation:** Regularly save backup copies of your QSOs and configuration data. While a portable application is convenient for running and transferring the software, it does not replace proper backups.

## Project Status

Application under continuous development.

## Author

**CT1ENI — Joe**

## Downloads

### All Versions

All versions:
[![Downloads - todas as versões](https://img.shields.io/github/downloads/CT1ENI/ENI-VULogger/total?style=flat-square&logo=github&label=Downloads)](https://github.com/CT1ENI/ENI-VULogger/releases)

Last version:
[![Downloads da última versão](https://img.shields.io/github/downloads/CT1ENI/ENI-VULogger/latest/total?style=flat-square&logo=github&label=Downloads%20última%20versão)](https://github.com/CT1ENI/ENI-VULogger/releases/latest)

