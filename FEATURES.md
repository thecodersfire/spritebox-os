# Built-in features for spritebox-os

Purpose: pixel art

1. **prepare racing and game notes** — run spritebox-os-workspace. It creates ~/Documents/spritebox-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run spritebox-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/spritebox-os-session-plans/.
3. **check game and controller readiness** — run spritebox-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/spritebox-os-workspace features/spritebox-os-plan features/spritebox-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for pixel art:

1. **Krita** — org.kde.krita
2. **Kdenlive** — org.kde.kdenlive
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
