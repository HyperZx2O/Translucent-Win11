<p align="center"> <img src="https://github.com/user-attachments/assets/f95f46e2-002d-4906-b7bb-9f1c430377a3" alt="Logo" width="300" height="300" align="centre"> </p>

# <p align="center"> Translucent Win11 </p>




https://github.com/user-attachments/assets/e84da7f7-7554-46d0-951d-1fec3c70cc40




We all have seen our fair share of Windows ricing along with OG themes like Gruvbox, [Catppuccin](https://catppuccin.com/), [Dracula](https://draculatheme.com/) and much more. Time to feast your eyes upon a whole Translucent Makeover of Windows, starting from changing appearance from the system level to finding alternatives to your default apps, all in one place!

> [!IMPORTANT]
> It is advised that you go through the guide fully at least once! You can always come back to check out specific sections later on.
> Softwares mentioned here works better installed anywhere else your C:\ drive.
> Before following the guide, download the latest source code of this documentation from the releases page.

## Navigating this Guide
As this is quite a long guide, it can be navigated easily using the dropdown shown in the pic below:


![zen_AHxNFGLRKY](https://github.com/user-attachments/assets/6ae23a8a-e6fd-4e39-a05e-8d136be89c45)


## Requirement
- Windows 11 (Extremlely sad that Windows 10 doesn't support much of Mica's functionality)

# System Level Apps
## [Rectify11](https://rectify11.net/home)

> The ultimate Windows 11 customization tool

Rectify11 is a tool that allows you to customize your Windows 11 experience and make it more consistent. Rectify11 v3.2 includes a full dark theme, updated icons and control panel, better context menus, transparency (using MicaForEveryone) and more!

1. Download the tool from the website.
2. Install it using the installer
3. Open the Rectify11 Control Center.exe from Desktop
4. Choose the theme 'Rectify11 Dark Theme with Mica.


![Rectify11](https://github.com/user-attachments/assets/d00db426-1f2c-440c-b228-9794eab6a4b8)


Enjoy the new experience, from a stunning new Explorer with amazing animations!

## [Mica For Everyone](https://github.com/MicaForEveryone/MicaForEveryone)
> Mica For Everyone is a tool to enable backdrop effects on the title bars of Win32 apps on Windows 11.

The tool that will enable a blurred transparency over all the other apps starting from here. An absolute need and cannot be missed to have the makeover.

1. Install the app from the latest [releases](https://github.com/MicaForEveryone/MicaForEveryone/releases). Always choose the MicaForEveryone.appinstaller.
2. Open the app and choose 'Global' rule.
3. Set it according to the following:


![MFE](https://github.com/user-attachments/assets/4bba6ecb-5012-4ba6-ae1a-564e87aee116)

Done!

> [!WARNING]
> Some apps may have weird looks using Mica, obviously it's not meant for all apps but for most. This can easily be solved by doing this:
> 1. Add new rule.
> 2. Add process rule.
> 3. Type out the app name
> 4. Open the app rule
> 5. Set the settings to this:
>    - Backdrop Type = None
>    - Disable 'Extend frame into client area'
>    - Disable 'Blur behind'

## [Windhawk](https://windhawk.net/)
> The customization marketplace for Windows and programs

1. Install the app and go to 'Explore'
2. Install all the mods mentioned in the Windhawk Folder
   - Folders = Only install matching the name on the store
   - txt = Install the mod and add the customized css in the mod page
Here's a tutorial on how to do this:


https://github.com/user-attachments/assets/e4955256-73df-4700-bc42-edb3d2bfb235

You're done!

## [Nilesoft Shell](https://nilesoft.org/)

> Powerful, free, open source context menu manager

1. Install the app
2. Shift + Right Click on Taskbar > Shell > Directory > Import
3. Keep that tab and go to the 'Nilesoft Shell' of the downloaded source code of this repo.
4. Copy 'theme.nss' and paste it to your 'import' folder
5. Ctrl + Right Click on the desktop, it reloads Nilesoft Shell in your desktop.
6. In case of confusion, follow the video guide below:


https://github.com/user-attachments/assets/b9d69d9a-2324-45ae-b385-acaa0942d1ad

You're done!


> [!NOTE]
> We're done with the system level applications now. As we proceed, now there will be apps that either acts as a better alternative to your default applications or just add new functionaility! It is a must that you have Mica For Everyone installed or the transparency might not work.

# Additional/Replacement Apps
## [One Commander](https://onecommander.com/)

> OneCommander is a modern file manager for Windows 11 and Windows 10. Features include tabs, dual-pane browsers, columns navigation, built-in preview, editable themes, color tags, and much more.

It replaces your default File Explorer in case you want to.

1. Install the app
3. Follow the video below to achieve transparency:


https://github.com/user-attachments/assets/d1d2c6f0-7feb-4f2d-b093-0b54989e8b0c

You're done!

## [Warp](https://www.warp.dev/)

> Become a command line power user on day one. Warp combines AI and your dev team’s knowledge in one fast, intuitive terminal.

It replaces your Terminal in case you want to. It comes packed with features as well as Powershell integration.

1. Install the app
2. Follow the video guide below:


https://github.com/user-attachments/assets/711b472d-ada8-40df-84d5-74aefe858b29

## [Zen Browser](https://zen-browser.app/)

> Beautifully designed, privacy-focused, and packed with features. We care about your experience, not your data.

In my humble opinion, the best browser on the internet in terms of customization! It can be a tad bit hassle to setup, but worth the shot for a greater internet experience.

1. Install the browser
2. Go through the onboarding experience.
3. Type 'about:support' and enter.
4. Click 'Open Folder' beside the 'Profile Folder' option. It will redirect you to a folder with lots of stuff. Don't worry.
5. Create a 'chrome' folder (You shouldn't already have one if you're new, however if it's there, perfectly fine).
6. Copy the chrome content from the downloaded source code of my repo from releases, then paste it into your own chrome folder.
7. Go back to 'about:support' in the browser and click 'Clear Startup Cache'. It wil restart the browser with the new customization.
8. Install the [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) extension. Open it and make it fetch the latest styles. This is the goated extension to make your websites look transparent
9. For the final touch, we will go to 'about:config'

### About:config settings
Do it in this order
- `browser.tabs.allow_transparent_browser` = true
- `zen.workspaces.show-workspace-indicator` = false
- `zen.widget.windows.acrylic` = false

In case of confusion, follow the video guide below:


https://github.com/user-attachments/assets/0b2eca09-705e-435f-9a40-9255a23fd252


### How to pin extensions in toolbar

1. Pin your extension in sidebar with right click
2. Right click on sidebar > Customise Toolbar
3. Drag your extension over the Essentials
4. Follow the below video guide if confused:


https://github.com/user-attachments/assets/a9cbc4e5-70fc-4cd9-bfd3-2bdfc0dd9db0


### Zen Mods
- [Animations Plus ](https://zen-browser.app/mods/f4866f39-cfd6-4498-ab92-54213b8279dc/)
- [ Cleaned URL bar ](https://zen-browser.app/mods/a5f6a231-e3c8-4ce8-8a8e-3e93efd6adec/)
- [ Cleaner Extension Menu ](https://zen-browser.app/mods/1e86cf37-a127-4f24-b919-d265b5ce29a0/)
- [ Disable Status Bar ](https://zen-browser.app/mods/b51ff956-6aea-47ab-80c7-d6c047c0d510/)
- [ Erics Zen UI Tweak Box ](https://zen-browser.app/mods/bed8c922-616a-4165-8c86-6822ccf478ad/)
  
  ![Screenshot 2025-03-09 at 15-49-23 Settings](https://github.com/user-attachments/assets/abf6b0d8-8fab-4b40-84d5-4accc09a2e50)

- [ Hide Extension Name ](https://zen-browser.app/mods/cb15abdb-0514-4e09-8ce5-722cf1f4a20f/)
- [ No Gaps ](https://zen-browser.app/mods/bfcc400a-4ecb-4752-bfd2-a68f116a2722/)
- [ No Search Shortcut Icons ](https://zen-browser.app/mods/d7076c31-f6c1-4f28-b2e8-15b95f5a3d6f/)
- [ No Sidebar Scrollbar ](https://zen-browser.app/mods/4ab93b88-151c-451b-a1b7-a1e0e28fa7f8/)
- [Quietify](https://zen-browser.app/mods/fd24f832-a2e6-4ce9-8b19-7aa888eb7f8e/)
- [ Zen Back Forward ](https://zen-browser.app/mods/c8d9e6e6-e702-4e15-8972-3596e57cf398/)
- [ SuperPins ](https://zen-browser.app/mods/ad97bb70-0066-4e42-9b5f-173a5e42c6fc/)
  
![Screenshot 2025-03-09 at 15-54-05 Settings](https://github.com/user-attachments/assets/aed5f25f-aad3-4eee-be92-3397403c7ec8)

- [ Zen Context Menu ](https://zen-browser.app/mods/81fcd6b3-f014-4796-988f-6c3cb3874db8/)
  
![Screenshot 2025-03-09 at 15-55-22 Settings](https://github.com/user-attachments/assets/991b5363-faff-41fc-bae5-48eb6ffb7db6)

- [ Zen Minimal Exit Menu ](https://zen-browser.app/mods/6cd4bca9-f17d-4461-b554-844d69a4887c/)
  
![Screenshot 2025-03-09 at 15-56-22 Settings](https://github.com/user-attachments/assets/e8b7d537-b34c-4a01-8ce0-03b8ddc4d2a4)

- [Transparent Zen](https://zen-browser.app/mods/642854b5-88b4-4c40-b256-e035532109df/)
  
![Screenshot 2025-05-27 at 21-26-51 Settings](https://github.com/user-attachments/assets/51a33b5f-5819-43c8-b5d9-cfc893ed1548)

> [!NOTE]
> An alternative to this would be [Arc-2.0](https://github.com/YashjitPal/Arc-2.0), [Zenppuccin](https://github.com/Mohammed55Z/Zenppuccin) and [Arcline](https://github.com/ferrocyante/Arcline) ! They are very cool looking setups and highly recommended by the community too!


### Additional Customizations
- [fx-autoconfig](https://github.com/MrOtherGuy/fx-autoconfig/tree/master) [Required for javascript mods to work]
- [Bubble pop Deleting](https://github.com/Zylaah/bubble-pop-deleting)
- [Sine](https://github.com/CosmoCreeper/Sine) [Custom mod store, goated]
- [Anom12](https://github.com/Anoms12?tab=repositories)'s Repositories [Zen-Haven, Tidy Downloads, so forth and so on]
  
You're done!

## [ImageGlass](https://imageglass.org/)
>  A lightweight, versatile image viewer

A fantastic replacement to default image viewer

1. Install the app
2. Follow the video guide below:


https://github.com/user-attachments/assets/7e48cd6f-4adc-4f11-af70-bdd51ca3ffc7


## [qBittorrent](https://www.qbittorrent.org/)
One of the best torrent clients out there. Supports custom themes, which makes it so good.

1. Install the app
2. Copy the `fluent-dark.qbtheme` file from the downloaded source code to your qBittorrent installation folder.
3. In qbittorrent, go to settings > Behaviour
4. Check 'Use Custom UI'
5. Redirect it to the qbtheme file.
6. Follow the video guide below if confused:


https://github.com/user-attachments/assets/4f6ac2d6-506e-46ec-b56b-089d4169b300


You're done!

## [YASB Reborn](https://github.com/amnweb/yasb)
> A highly configurable Windows status bar written in Python.

1. Install the app
2. Get Windows 11 Theme in the 'YASB Theme Gallery' app
3. Right click on the YASB icon in taskbar > Open Config
4. Keep the tab and copy the config.yaml and styles.css from the downloaded source code and paste it into your folder.
5. In the YASB icon of taskbar > Reload YASB

You're done!

## [Komorebi](https://github.com/LGUG2Z/komorebi)

> A tiling window manager for Windows

This is not a simple app installation method. It is suggested that you follow the [documentation](https://lgug2z.github.io/komorebi/), however, I can give you a much simpler way to install it here as reading the documentation takes time. Follow me along here:

1. Open Warp (considering you already installed it) or Powershell
2. Paste this command:
   `Set-ItemProperty 'HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -Value 1`
3. Then paste this one:
   `winget install LGUG2Z.komorebi
    winget install LGUG2Z.whkd`
4. Then paste this one:
   `komorebic quickstart`
You're done with the installation! Now you can use it as shown in the main video.
The default start command is `komorebic start --whkd --bar`, meaning, you need to type/autofill it everytime you want to enable komorebi. You can find hotkeys [here](https://lgug2z.github.io/komorebi/example-configurations.html#whkdrc).


# Extras
> [!NOTE]
> These apps not necessarily follow the transparency theory, but they follow well with Microsoft's Fluent Design theory and look cool too. They are totally optional but I suggest doing them anyways.

## [Screenbox Media Player](https://apps.microsoft.com/detail/9ntsnmsvcb5l?hl=en-US&gl=US)

> Screenbox is a modern media player for all your devices, with support for a wide range of file formats.

It is a fork of the OG VLC Media Player. So you get features of VLC with a modern UI, nothing to lose here :smiley:

## [Melosik](https://apps.microsoft.com/detail/9nh759pmh26m?hl=en-US&gl=US)

> Melosik is a beautiful, Modern and easy to use music player specially made for Modern Windows.

Local music players. Looks nice, Only minor downside is an ad popup in the top right, which is totally justified. Not like it interrupts the music experience in any way. Enable the acrylic body and header in Settings > Appearance.

## Spotify
![Spotify_XHOe0isB1S](https://github.com/user-attachments/assets/7cd43b65-dfb9-4e8c-b2a8-9764c3569221)
![Spotify_aXGwruGOpT](https://github.com/user-attachments/assets/85c62972-aae2-4539-bf1f-6e93b83cc5a5)

> Spotify is a digital music service that gives you access to millions of songs.

We are going to modify Spotify through a third party CLI tool, [Spicetify](https://spicetify.app/)!

1. Install it using the command in Warp (also the Marketplace)
2. Install the following:

### Extensions
- Beautiful Lyrics
- Full App Display Modified
- adblockify
- Scannables
- Power Bar
- Smooth Scrolling

### Themes
- Lucid
This theme follows the Windows Fluent Design theory.

### Snippets
- Rounded 'Now Playing' Bar
- Rounded Images
- Fix 'Episodes' Icon
- Fix 'Liked' Icon
- Fix 'DJ' Icon
- Fix main view width
- Fix playlist hover effect
- Smooth Reveal Playlist Gradient
- Remove Connect Bar
- Remove top spacing
- Left alligned heart icons
- Hover panels
- Fix progress bar displacement
- Fix 'Now Playing' Icon color
- Right side cover art
- Pointers
- Hide Sidebar Scrollbar
- Oneko
- Fix Listening On
- Centered Lyrics

## [Tacky Borders](https://github.com/lukeyou05/tacky-borders)
>   Customizable borders for Windows 11 and 10


https://github.com/user-attachments/assets/c5cf82de-84c7-4ff0-83b6-fd8de39aba4f


You're done!

This marks the end of the Windows Makeover. It will likely enhance your Windows and Internet experience way more if you're into glassmorphism and bit. Thanks for staying till the end!

# Acknowledgements

- The app developers for their respective apps!
- [Ahnaf Hasan](https://www.facebook.com/ahnafhasan0110) for the logo!
- [JustAdumbPrsn](https://github.com/JustAdumbPrsn) for [Nebula](https://github.com/JustAdumbPrsn/Zen-Nebula)
- [YouCanTouCan](https://github.com/YouCanTouCan/Zen-Setup/tree/main) for [Toucan Tweaks](https://github.com/YouCanTouCan/Zen-Setup)
- [sameerasw](https://github.com/sameerasw) for [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) Extension.
  .....and others (in the event I missed someone)!

  ## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=HyperZx2O/Translucent-Win11&type=Date)](https://www.star-history.com/#HyperZx2O/Translucent-Win11&Date)











