# Built-in features for lantern-party-os

Purpose: LAN gaming

1. **prepare racing and game notes** — run lantern-party-os-workspace. It creates ~/Documents/lantern-party-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run lantern-party-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/lantern-party-os-session-plans/.
3. **check game and controller readiness** — run lantern-party-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/lantern-party-os-workspace features/lantern-party-os-plan features/lantern-party-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for LAN gaming:

1. **Heroic Games Launcher** — com.heroicgameslauncher.hgl
2. **Lutris** — net.lutris.Lutris
3. **Bottles** — com.usebottles.bottles

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
