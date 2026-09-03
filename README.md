# Flaky Shell

A small, modular, and (hopefully) efficient shell targetting NixOS first.

# Goals / Problem to Solve

**I have no idea if all of these are possible yet but I'm hoping**

- The goal is to have a shell where you only grab what you need via the NixOS configuration.
- I'd also like to make it configurable via toml for convience, and to avoid double-configuration.
- Eventually I'd like to have a cache server so people don't have to compile it themselves.

# Features / Roadmap

I want to try to do all of this while trying to minimize dependencies, using Qt, and Quickshell

## Compositor Shell

- [ ] Basic layout configuration for components
  - (Padding, spacing, anchoring, etc)
- [ ] Settings/config app
  - [ ] Settings exporter
- [ ] Power usage info
- [ ] Basic bar
  - [ ] Bar widgets
    - [ ] Clock
    - [ ] Date
    - [ ] Workspaces
    - [ ] Launcher
    - [ ] Power menu
    - [ ] Notifications
    - [ ] Audio options
    - [ ] Battery/charging
    - [ ] System info
- [ ] Desktop
  - [ ] Wallpaper management
  - [ ] Theme management
    - (With wallpaper-based themes)
  - [ ] Desktop widgets
    - [ ] See bar widgets
- [ ] Notifications
- [ ] Audio management
- [ ] Lockscreen
- [ ] Screen capture/recording
- [ ] Wi-Fi/internet management
- [ ] Bluetooth management
- [ ] Export themes to apps
  - Should be exported in an easy to parse format so it can be converted easily after

# Greeter

- [ ] Basic login
- [ ] Use themes from shell
