# How to Set Up a Mac from Scratch

This guide provides a step-by-step process to configure a Mac for optimal performance, usability, and development.

## 1. Download and Install Browsers
By default, macOS comes with Safari as the primary web browser. However, if you prefer Microsoft Edge or Google Chrome, follow these steps:

- Open Safari (pre-installed on macOS).
- Go to the official Microsoft Edge download page: **[Download Microsoft Edge](https://www.microsoft.com/edge)**.
- Go to the official Google Chrome download page: **[Download Google Chrome](https://www.google.com/intl/en/chrome/)**.
- Set Edge as the default browser: Open **System Settings → Default Browser → Microsoft Edge**.

## 2. Install Logitech Options+ to Set Up MX Series Mouse
If you're using a Logitech MX series mouse, install Logitech Options+ to customize its settings:

- Go to the official Logitech Options+ download page: **[Download Logitech Options+](https://www.logitech.com/en-us/setup/mxsetup.html)**.
- Click "Download for macOS" and wait.

## 3. Install Essential Apps from the Mac App Store
Enhance usability, performance, and development with these essential apps:

- Open App Store from the Dock or Launchpad.
- Search for and install the following apps:
  - **Telegram** – A fast and secure messaging app.
  - **Speedtest by Ookla** – To test internet speed.
  - **Amphetamine** – Prevents Mac from sleeping when needed.
  - **Windows App** – Allows access to Microsoft apps on Mac.
  - **Xcode** – Apple’s official development environment for macOS and iOS apps.

## 4. Download and Install ChatGPT for Mac
The ChatGPT app allows you to access AI-powered assistance directly from your Mac:

- Go to the official OpenAI ChatGPT download page: **[Download ChatGPT for Mac](https://openai.com/blog/chatgpt-apps)**.

## 5. Adjust Mac System Settings

To optimize performance and usability, adjust the following system settings:

### Dock and UI Enhancements
- **Change Dock position to left and enable auto-hide**: System Settings → Dock & Menu Bar → Position on screen: **Left**, toggle **Automatically hide and show the Dock**.
- **Set a very short timer for a super quick jump-in animation in the Dock**:
  ```sh
  defaults write com.apple.dock autohide-time-modifier -float 0.15; killall Dock
  ```

### Disable "Wake for Network Access"
Prevents your Mac from waking up unnecessarily due to network activity:

- Open **System Settings** → **Battery**.
- Click **Power Adapter** from the sidebar.
- Find **Wake for network access** and set it to **Never**.

### Enable 24-Hour Time Format

- Open **System Settings** → **General → Date & Time**.
- Toggle on **Use 24-hour time**.

### Set Region to Armenia

- Open **System Settings** → **General → Language & Region**.
- Under **Region**, select **Armenia**.
- Restart your Mac to apply the changes.

### Enable Trackpad for Dragging (Three-Finger Drag)

- Open **System Settings** → **Accessibility → Pointer Control**.
- Click **Trackpad Options**.
- Toggle on **Use trackpad for dragging** and select **Three-finger drag**.
- Click **OK** to save the changes.

### Set Siri Voice to British Voice 3

- Open **System Settings** → **Siri & Spotlight**.
- Click **Siri Voice**.
- Select **British** as the variety.
- Choose **Voice 3** from the list.
- Wait for the voice to download if needed.

### Additional System Settings

- **Show battery percentage**: System Settings → Battery → Show Battery Percentage (Enable).
- **Turn off suggested and recent apps on Dock**: System Settings → Desktop & Dock → Show recent applications in Dock (Disable).
- **Disable notifications on lock screen**: System Settings → Notifications → Allow notifications when locked (Disable).
- **Delete "Do Not Disturb" schedules**: System Settings → Focus → Do Not Disturb (Remove any schedules).
- **Never start a screen saver**: System Settings → Screen Saver → Start after: **Never**.
- **Change hot corner settings using Option key**: Adjust hot corners in **System Settings → Desktop & Dock → Hot Corners** while holding the **Option** key.

## 6. Add Google Account (Sync All Except Contacts)

- Open **System Settings** → **Internet Accounts**.
- Click **Google** and sign in.
- Sync everything except **Contacts**.

## 7. Install Development Tools

### Install Visual Studio Code

- Open Safari or Microsoft Edge.
- Go to **[Download VS Code](https://code.visualstudio.com/Download)**.
- Click "Download for macOS" and install.

### Install Homebrew (Package Manager)

Run the following command in Terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After installation, add Homebrew to your PATH:

```sh
echo 'eval "$( /opt/homebrew/bin/brew shellenv )"' >> /Users/tarielinc/.zprofile
eval "$( /opt/homebrew/bin/brew shellenv )"
```

### Install AppLite (GUI for Homebrew)

```sh
brew install --cask applite
```

### Install Steam and Epic Games

- Download and install **[Steam](https://store.steampowered.com/about/)**.
- Download and install **[Epic Games](https://www.epicgames.com/store/en-US/)**.

## 8. Configure Finder and Screenshot Settings

### Change Finder Preferences

- Open Finder → **Settings**.
- Set **New Finder windows show** to **Downloads**.
- Under **Advanced**, set **When performing a search** to **Search this Mac**.
- Enable **Show Path Bar** (View → Show Path Bar).
- Enable **Show Status Bar** (View → Show Status Bar).

### Change Screenshot Location

- Open **Terminal** and run:

```sh
defaults write com.apple.screencapture location ~/Documents/
killall SystemUIServer
```

## 9. Install Additional Utilities

### Install Armenian Keyboard Layout

- Download **Armenian keyboard files**.
- Copy them to **`/Library/Keyboard Layouts`**.
- Log out and log in again.

### Install PearCleaner

- Download **[PearCleaner](https://github.com/alienator88/Pearcleaner/releases)**.
- Install and configure as needed.

### Install Additional Useful Apps

- **[Marta File Manager](https://marta.sh/)** – A fast dual-pane file manager.
- **[KeyClu](https://sergii.tatarenkov.name/keyclu/support/)** – Simple and handy overview of applications shortcuts.
- **[Ice](https://github.com/jordanbaird/Ice)** – A menu bar management tool.



- **[Yandex Music](https://music.yandex.ru/download/)** - Music streaming app.

- **[GeForce NOW](https://gfn.am/en/download.html)** - Instantly play the most demanding PC games and seamlessly play across your devices.

- **[TextMate](https://macromates.com/)** - MPowerful and customizable text editor with support for a huge list of programming languages and developed as open source.

- **[IINA](https://iina.io/)** - The modern media player for macOS.

- **[VMware Fusion](https://support.broadcom.com/group/ecx/productdownloads?subfamily=VMware%20Fusion&freeDownloads=true)** - Let run virtual machines on a Windows, Linux or Mac computer. (You will need a customer account at support.broadcom.com to access downloads.)



---

## Setting Up GitHub on macOS

### 1. Install GitHub Desktop

1. Go to **[Download GitHub Desktop](https://desktop.github.com/)**.
2. Launch GitHub Desktop and sign in with your GitHub account.

### 2. Configure Git in Terminal

To use Git from the terminal, set up your username and email:

```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

---

Your Mac is now fully set up and optimized for productivity, development, and personal use! 🚀
