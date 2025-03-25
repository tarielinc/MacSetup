How to Set Up a Mac from Scratch

1. Download and Install Microsoft Edge

By default, macOS comes with Safari as the primary web browser. However, if you prefer Microsoft Edge, follow these steps:

Open Safari (pre-installed on macOS).

Go to the official Microsoft Edge download page: Download Microsoft Edge.

Click "Download" and select "macOS" as the platform.

Once the download is complete, open the .pkg file and follow the installation instructions.

After installation, open Microsoft Edge from the Applications folder or Launchpad.

Set Edge as the default browser: Open System Settings → Default Browser → Microsoft Edge.

2. Install Logitech Options+ to Set Up MX Series Mouse

If you're using a Logitech MX series mouse, install Logitech Options+ to customize its settings:

Open Safari or Microsoft Edge.

Go to the official Logitech Options+ download page: Download Logitech Options+.

Click "Download for macOS" and wait for the .dmg file to finish downloading.

Open the downloaded .dmg file and follow the installation instructions.

Open Logi Options+, connect your Logitech MX mouse, and customize the settings as needed.

3. Install Essential Apps from the Mac App Store

The following apps improve usability, performance, and development capabilities:

Open App Store from the Dock or Launchpad.

Search for and install the following apps:

Telegram – A fast and secure messaging app.

Speedtest by Ookla – To test internet speed.

HiddenBar – To manage and hide menu bar icons.

Amphetamine – Prevents Mac from sleeping when needed.

Windows App – Allows access to Microsoft apps on Mac.

Xcode – Apple’s official development environment for macOS and iOS apps.

Once installed, open each app and configure settings as needed.

4. Download and Install ChatGPT for Mac

The ChatGPT app allows you to access AI-powered assistance directly from your Mac:

Open Safari or Microsoft Edge.

Go to the official OpenAI ChatGPT download page: Download ChatGPT for Mac.

Click "Download for macOS" and wait for the .dmg file to finish downloading.

Open the downloaded .dmg file and drag the ChatGPT app into the Applications folder.

Open ChatGPT from Launchpad or Finder and sign in with your OpenAI account.

5. Adjust Mac System Settings

To optimize performance and usability, adjust the following system settings:

Disable "Wake for Network Access"

Prevents your Mac from waking up unnecessarily due to network activity:

Open System Settings → Battery.

Click Power Adapter from the sidebar.

Find Wake for network access and set it to Never.

Enable 24-Hour Time Format

Open System Settings → General → Date & Time.

Toggle on Use 24-hour time.

Set Region to Armenia

Open System Settings → General → Language & Region.

Under Region, select Armenia.

Restart your Mac to apply the changes.

Enable Trackpad for Dragging (Three-Finger Drag)

Open System Settings → Accessibility → Pointer Control.

Click Trackpad Options.

Toggle on Use trackpad for dragging and select Three-finger drag.

Click OK to save the changes.

Set Siri Voice to British Voice 3

Open System Settings → Siri & Spotlight.

Click Siri Voice.

Select British as the variety.

Choose Voice 3 from the list.

Wait for the voice to download if needed.

Additional System Settings

Show battery percentage: System Settings → Battery → Show Battery Percentage (Enable).

Change Dock position to left and enable auto-hide: System Settings → Dock & Menu Bar → Position on screen: Left, toggle Automatically hide and show the Dock.

Turn off suggested and recent apps on Dock: System Settings → Desktop & Dock → Show recent applications in Dock (Disable).

Disable notifications on lock screen: System Settings → Notifications → Allow notifications when locked (Disable).

Delete "Do Not Disturb" schedules: System Settings → Focus → Do Not Disturb (Remove any schedules).

Never start a screen saver: System Settings → Screen Saver → Start after: Never.

6. Add Google Account (Sync All Except Contacts)

Open System Settings → Internet Accounts.

Click Google and sign in.

Sync everything except Contacts.

7. Install Development Tools

Install Visual Studio Code

Open Safari or Microsoft Edge.

Go to Download VS Code.

Click "Download for macOS" and install.

Install Homebrew (Package Manager)

Run the following command in Terminal:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

After installation, add Homebrew to your PATH:

echo >> /Users/tarielinc/.zprofile
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/tarielinc/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

Install AppLite (GUI for Homebrew)

brew install --cask applite

Install Steam and Epic Games

Download and install Steam.

Download and install Epic Games.

8. Configure Finder and Screenshot Settings

Change Finder Preferences

Open Finder → Settings.

Set New Finder windows show to Downloads.

Under Advanced, set When performing a search to Search this Mac.

Enable Show Path Bar (View → Show Path Bar).

Change Screenshot Location

Open Terminal and run:

defaults write com.apple.screencapture location ~/Documents/
killall SystemUIServer

9. Install Additional Utilities

Install Armenian Keyboard Layout

Download Armenian keyboard files.

Copy them to /Library/Keyboard Layouts.

Log out and log in again.

Install PearCleaner

Download PearCleaner.

Install and configure as needed.
