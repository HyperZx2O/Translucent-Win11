# <p align="center"> Translucent Win11 </p>



https://github.com/user-attachments/assets/bb29775a-280f-4e63-bcc3-ec9ed0018684



We have all seen our fair share of Windows ricing along with OG themes like Gruvbox, [Catppuccin](https://catppuccin.com/), [Dracula](https://draculatheme.com/) and much more. Time to feast your eyes upon a whole Translucnt Makeover of Windows, starting from changing appearance from the system level to finding alternatives to your default apps, all in one place!

> [!IMPORTANT]
> It is advised that you go through the guide fully at least once! You can always come back to check out specific sections later on.
> Softwares mentioned here works better installed anywhere else your C:\ drive.
> Before following the guide, download the latest source code of this documentation from the releases page.

## Requirement
- Windows 11 (Extremlely sad that Windows 10 doesn't support much of Mica's functionality)

## [Rectify11](https://rectify11.net/home)

> The ultimate Windows 11 customization tool

Rectify11 is a tool that allows you to customize your Windows 11 experience and make it more consistent. Rectify11 v3.2 includes a full dark theme, updated icons and control panel, better context menus, transparency (using MicaForEveryone) and more!

1. Download the tool from the website.
2. Install it using the installer
3. Open the Rectify11 Control Center.exe from Desktop
4. Choose the theme 'Rectify11 Dark Theme with Mica.
   
![explorer_Y47rJYUdsf](https://github.com/user-attachments/assets/176005b8-5782-4f0f-b482-3e9746c05826)


Enjoy the new experience, from a stunning new Explorer with amazing animations!

## [Mica For Everyone](https://github.com/MicaForEveryone/MicaForEveryone)
> Mica For Everyone is a tool to enable backdrop effects on the title bars of Win32 apps on Windows 11.

The tool that will enable a blurred transparency over all the other apps starting from here. An absolute need and cannot be missed to have the makeover.

1. Install the app from the latest [releases](https://github.com/MicaForEveryone/MicaForEveryone/releases). Always choose the MicaForEveryone.appinstaller.
2. Open the app and choose 'Global' rule.
3. Set it according to the following:
   
   ![MicaForEveryone App_RWt0IKvofZ](https://github.com/user-attachments/assets/511b47b5-3bd4-45da-b314-8359e5855cc5)

Done!

> [!WARNING]
> Some apps may have weird looks using Mica, obviously it's not meant for all apps but for most. This can easily be solved by doing this:
> 1. Add new rule.
> 2. Add process rule.
> 3. Type out the app name
> 4. Open the app rule
> 5. Set the settings to this:
>    - Backdrop Type = Mica
>    - Disable 'Extend frame into client area'
>    - Disable 'Blur behind'

## [Windhawk](https://windhawk.net/)
> The customization marketplace for Windows and programs

1. Install the app and go to 'Explore'
2. Install all the mods mentioned in the Windhawk Folder
   - Folders = Only install matching the name on the store
   - txt = Install the mod and add the customized css in the mod page
Here's a tutorial on how to do this:

https://github.com/user-attachments/assets/18c404c5-29d8-430f-a59a-77cc3b29832f

You're done!

## [Nilesoft Shell](https://nilesoft.org/)

> Powerful, free, open source context menu manager

1. Install the app
2. Shift + Right Click on Taskbar > Shell > Directory > Import
3. Keep that tab and go to the 'Nilesoft Shell' of the downloaded source code of this repo.
4. Copy 'theme.nss' and paste it to your 'import' folder
5. Ctrl + Right Click on the desktop, it reloads Nilesoft Shell in your desktop.
6. In case of confusion, follow the video guide below:

https://github.com/user-attachments/assets/e2d93323-7355-4182-be82-ea6851dc128a

You're done!


> [!NOTE]
> We're done with the system level applications now. As we proceed, now there will be apps that either acts as a better alternative to your default applications or just add new functionaility! It is a must that you have Mica For Everyone installed or the transparency might not work.

## [One Commander](https://onecommander.com/)

> OneCommander is a modern file manager for Windows 11 and Windows 10. Features include tabs, dual-pane browsers, columns navigation, built-in preview, editable themes, color tags, and much more.

It replaces your default File Explorer in case you want to.

1. Install the app
3. Follow the video below to achieve transparency:

https://github.com/user-attachments/assets/e1170f25-6b59-4df7-bf80-c8e4458640ad

You're done!

## [Warp](https://www.warp.dev/)

> Become a command line power user on day one. Warp combines AI and your dev team’s knowledge in one fast, intuitive terminal.

It replaces your Terminal in case you want to. It comes packed with features as well as Powershell integration.

1. Install the app
2. Follow the video guide below:

https://github.com/user-attachments/assets/272b34df-59dc-46d4-a68e-29b7d279dbd1

## [Zen Browser](https://zen-browser.app/)

> Beautifully designed, privacy-focused, and packed with features. We care about your experience, not your data.

In my humble opinion, the best browser on the internet in terms of customization! It can be a tad bit hassle to setup, but worth the shot for a greater internet experience.

1. Install the browser
2. Go through the onboarding experience.
3. Type 'about:support' and enter.
4. Click 'Open Folder' beside the 'Profile Folder' option. It will redirect you to a folder with lots of stuff. Don't worry.
5. Create a 'chrome' folder (You shouldn't already have one if you're new, however if it's there, perfectly fine.
6. Copy the chrome content from the downloaded source code of my repo from releases, then paste it into your own chrome folder.
7. Go back to 'about:support' in the browser and click 'Clear Startup Cache'. It wil restart the browser with the new customization.
8. Install the [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) extension. Open it and make it fetch the latest styles. This is the goated extension to make your websites look transparent
9. For the final touch, we will go to 'about:config'

### About:config settings
Do it in this order
- `browser.tabs.allow_transparent_browser` = true
- `zen.workspaces.show-workspace-indicator` = false
- `zen.widget.windows.acrylic` = false
- `natsumi.experiments.rounded-pip` = true
- `natsumi.navbar.float` = true
- `natsumi.navbar.glass-effect`  = true
- `natsumi.pdfjs.compact` = false
- `natsumi.sidebar.blur-zen-sidebar` = true
- `natsumi.sidebar.containers-no-inactive-border` = true
- `natsumi.sidebar.floating-panel` = true
- `natsumi.sidebar.panel-glass-effect` = true
- `natsumi.sidebar.tabs-glass-effect` = true
- `natsumi.sidebar.zen-sidebar-glass-effect` = true
- `natsumi.theme.clip-path-force-polygon` = true
- `pf.use.natsumi-tweaks` = true

In case of confusion, follow the video guide below:


https://github.com/user-attachments/assets/03cf9d45-bb25-4d0f-87c8-205319da831c


### How to pin extensions

1. Pin your extension
2. Right click on sidebar > Customise Toolbar
3. Drag your extension over the Essentials
4. Follow the below video guide if confused:

https://github.com/user-attachments/assets/e716ffb5-a637-4a4e-a25a-9e547dc1940c

You're done!





