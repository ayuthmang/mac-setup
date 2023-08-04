# mac-setup

## Trackpad Setup

![all trackpad setting](./docs/trackpad-setting-all.png)

### Enable dragging with three fingers

![enable three finger drag in system settings](./docs/trackpad-setting-enable-three-finger-drag.png)

1. Open System Settings
2. Click the Accessibility tab
3. Click the "Trackpad Options" button
4. Enable the checkbox "Use trackpad for dragging"
   - Dragging style -> Three Finger Drag

### Install necessary applications

1. Install [Homebrew](https://brew.sh/).
2. Install these applications:
   - Tap the `homebrew-cask` via:
      - `brew tap homebrew/cask-versions`
   - Install essential apps:
      - `brew install --cask 1password brave-browser raycast`.
   - Install development apps
      - `brew install --cask visual-studio-code`.

### Configurations

#### 

#### 1Password

👉 Config Password for [1Password for SSH & Git](https://developer.1password.com/docs/ssh/).

#### Raycast

Replace spotlight search with raycast

1. Open System Settings
2. Click the Keyboard tab
3. Click the Keyboard Shortcuts... button
4. Click the Spotlight tab
5. Uncheck following:
   - [ ] Show Spotlight search
   - [ ] Show Finder search window
6. Click Done
