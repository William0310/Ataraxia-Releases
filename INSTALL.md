# Installing the Ataraxia beta

**Requirements:** a Mac with Apple silicon (M1 or later) and macOS 26 or later. Intel Macs aren't supported.

This beta is **signed by its developer but not notarized by Apple**, so macOS asks you to confirm the first time
you open it. You never need to turn off any macOS security setting.

## 1. Install
1. Download **Ataraxia-1.2.0-121.dmg** from the [latest release](https://github.com/William0310/Ataraxia-Releases/releases/latest).
2. Optional: check the download. In Terminal, `shasum -a 256 ~/Downloads/Ataraxia-1.2.0-121.dmg` should print
   `4dc30952bf59a465fafc0a6e04a17c9afcf0e1e7c02a16bf8565b9048e372de7`.
3. Open the DMG and drag **Ataraxia** onto **Applications**. Eject the DMG.

## 2. Open it the first time
1. Open Ataraxia from Applications. macOS says **"Ataraxia" Not Opened** because Apple hasn't checked it. Click **Done** (not Move to Trash).
2. Open **System Settings → Privacy & Security**, scroll down to **Security**: you'll see that Ataraxia was blocked. Click **Open Anyway** and confirm with Touch ID or your password. (The button appears only for about an hour after you tried to open the app.)
3. Click **Open** in the dialog that follows. From then on Ataraxia opens normally.
4. Read and accept the user agreement. It explains what Ataraxia stores and the few requests it makes (search suggestions, announcements, update checks).

On a Mac managed by an organization, Open Anyway may not be available; Ataraxia can't be used there.

## 3. Updates
Choose **Ataraxia → Check for Updates…** at any time, or use **Settings → General → Software Updates**. On a later
launch Ataraxia asks whether to check automatically; your choice is respected. Every update is signed, and is
verified before it is installed. Updates are installed by Ataraxia itself — you don't need to repeat step 2.

## 4. Passwords
Saved passwords stay on this Mac. Using them needs Touch ID or your Mac password. They can't be moved to another
Mac; keep the recovery file and code Ataraxia gives you.

## 5. Reporting a problem
Send it to the developer the way you received this link. Please include:
- your Mac model and macOS version (Apple menu → About This Mac), and the Ataraxia version (Ataraxia → About Ataraxia);
- what you did, what you expected, and the exact message (a screenshot helps);
- which part was involved: **installation or Open Anyway**, **launch**, **Keychain or password prompts**, **Touch ID**, or **updates** (for updates, the text of Ataraxia's update window).

Never send passwords, your recovery file or code, or browsing data.
