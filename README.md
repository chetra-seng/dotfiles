# dotfiles
Personal dotfiles for linux and macos configurations, so I won't lose it on accident.

## Usage
In order to use each dot file, just create a symbolic link with full path, then source each file accordingly.

## Sync notes
- Install unison and fswatch via homebroew
- Copy sync_notes.prf to `~/Library/Application\ Support/Unison`
- Copy sync-notes to `./local/script/sync-notes`

### Yabai for MacOS
**Disable "Automatically rearrange Spaces based on most recent use"**  
Go to System Settings → Desktop & Dock → uncheck "Automatically rearrange Spaces based on most recent use".  
This prevents macOS from reordering spaces, which helps keep space numbers stable.
