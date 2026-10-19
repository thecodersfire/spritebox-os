# Built-in features for spritebox-os

Purpose: pixel art

1. **prepare racing and game notes** — run spritebox-os-workspace. It creates ~/Documents/spritebox-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run spritebox-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/spritebox-os-session-plans/.
3. **check game and controller readiness** — run spritebox-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/spritebox-os-workspace features/spritebox-os-plan features/spritebox-os-check "$HOME/.local/bin/"
