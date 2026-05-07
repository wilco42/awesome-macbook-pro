# awesome-macbook-pro [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated for my needs awesome list of things for a Macbook Pro.

## AI
- Cloud LLM
    - Anthropic
        - [Claude Code](https://claude.com/product/claude-code) - Claude Code CLI
        - [Claude Code IDE Extension](https://code.claude.com/docs/en/vs-code) - Visual Studio Code IDE extension
    - OpenAI
        - [Codex Desktop](https://chatgpt.com/codex/) - Desktop app with vision-based automation
        - [Codex CLI](https://developers.openai.com/codex/cli) - Codex CLI - OpenAI's version of Claude Code
        - [Codex IDE Extension](https://developers.openai.com/codex/quickstart?setup=ide) - Visual Studio Code IDE extension
- Local LLM
    - [Jan](https://jan.ai/) - open source ChatGPT-alternative running your choice of local LLMs 100% offline, also provides an OpenAI compatible local server
    - [Ollama](https://ollama.com/) - local LLM runner
    - [Continue](https://www.continue.dev/) - VS Code extension that enables AI code assistance

## Applications
- [Affinity](https://www.affinity.studio/) - Photo/Vector/Layout Editor
- 3D Printing
    - [Bambu Studio](https://bambulab.com/en-us/download/studio)
    - [Orca Slicer](https://github.com/SoftFever/OrcaSlicer)
    - [UltiMaker Cura](https://ultimaker.com/software/ultimaker-cura/)
- Browsers
    - [Brave Browser](https://brave.com/) - Privacy focused Chromium web browser
    - [Firefox](https://www.mozilla.org/en-US/firefox/) - Firefox web browser, a non-Chromium option
    - Extensions
        - [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html) - Ad blocker
        - [Bitwarden](https://bitwarden.com/) - Password Manager extension
        - [Window Resizer](https://chromewebstore.google.com/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh)
- [Slack<sup>+</sup>](https://slack.com/downloads/mac) - Slack messaging app

## Gaming
- [Crossover*](https://www.codeweavers.com/crossover) - Run Windows applications on Mac
    - [Heroic Games Launcher](https://heroicgameslauncher.com/) - Epic, GOG, Amazon Prime game alternative launcher
        - [Discussion on how to get Crossover to find Heroic Bottle](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/discussions/1567) - tldr; `cd ~/Library/Application\ Support/CrossOver/Bottles; ln -s ~/CXPBottles/Heroic`
    - [Steam](https://store.steampowered.com/)
        - [Ballionaire fix](https://www.reddit.com/r/macgaming/comments/1hdx3kv/only_background_loading_with_porting_toolkit/) - fix to get passed loading screen with Crossover
            - `--rendering-driver vulkan` in launch options
- [Discord](https://discord.com/) - Gaming messaging app

## macOS enhancements
- [BentoBox*](https://bentoboxapp.com/) - Window Manager a la Windows PowerToys FancyZones
- [flex-markdown](https://github.com/xykong/flux-markdown) - Markdown Preview in Finder
- [Ice<sup>+</sup>](https://icemenubar.app/) - Menu Bar management tool
- [Hammerspoon](https://www.hammerspoon.org/) - macOS automation framework
    - [LG TV Control](https://github.com/cmer/lg-tv-control-macos/) - LG TV Control for macOS - better integration of LG OLED TV with Macbook Pro
    - [Bluetooth Control](https://github.com/Hammerspoon/hammerspoon/issues/793) - Bluetooth control
- [ProNotes](https://www.pronotes.app/) - Apple Notes extension to add editing in Markdown
- [Raycast](https://www.raycast.com/) - Spotlight replacement, clipboard manager, emoji app
- [Rectangle](https://rectangleapp.com/) - Another Window Manager that has Windows-like keyboard shortcuts
- [Witch*](https://manytricks.com/witch/) - Enhanced macOS app switcher
    - [DockDoor](https://dockdoor.net/) - potential free replacement

## Security Applications
- [Bitwarden](https://bitwarden.com/) - Password Manager
- [cloudflared](https://formulae.brew.sh/formula/cloudflared) - [macOS DNS over HTTPS](https://blog.smittytone.net/2022/05/07/how-to-do-dns-over-https-on-macos/) on local AdGuard Home DNS servers
- [NordVPN*](https://www.nordvpn.com/) - NordVPN - current VPN of choice

## Programming Applications
- [Homebrew](https://brew.sh/) - Package manager for macOS
- IDEs
    - [Cursor<sup>+</sup>](https://www.cursor.com/) - the AI Code Editor
    - [Visual Studio Code](https://code.visualstudio.com/) - Visual Studio Code editor
    - [Xcode](https://developer.apple.com/xcode/)
        - Command Line Tools - `xcode-select --install`
        - [Device Simulators](https://developer.apple.com/documentation/safari-developer-tools/installing-xcode-and-simulators)
- [iTerm2](https://iterm2.com/) - Terminal replacement
- [nvm](https://github.com/nvm-sh/nvm) - Node Version Manager
- [Oh My Zsh](https://ohmyz.sh/) - supercharge zsh, but really make it act like [fish shell](https://fishshell.com/)
    - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
    - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
    - [powerlevel10k](https://github.com/romkatv/powerlevel10k) - theme for zsh

\* Paid application<br />
<sup>+</sup> Freemium