# Bedrock Addon Manager

_**Whilst this application is geared towards private server maintainers, the feature set expands to all Minecraft players.**_

Manage all your Minecraft Bedrock addons in one place before importing them into the game.

- Update target API version for abandoned addons, giving you self-reliance.
- Verify addon integrity by scanning for common known issues.
- Disable experimental feature requirement on addons when they are needlessly requested.
- Customize addon metadata to your liking, such as:
  - Removing unnecessary information from pack names and descriptions.
  - Correcting actual module versions to match the version in the title.
  - Enforcing dependencies between RPs and BPs, so they import into a world together.
- Rebundle RPs and BPs that were provided as separate files into a single `.mcaddon` file.

## Disclaimer
**The creators who spend countless hours pouring their heart and soul into these addons deserve the utmost appreciation and respect**. This app does not aim to undermine their work; rather, it empowers users to curate addons and structure them in a clear, readable way — while providing additional features for a more robust and well-rounded experience.

This project spawned out of my love for Minecraft and experimenting with different addons. I play with my son and run some private servers, and I found myself spending a lot of time curating addon files: renaming addon names to a uniform structure like "{name} - {author} {version}" or updating description text to include useful commands for behavior packs, or adding missing source links. Even going as far as to tweak API versions to bring back old addons. Eventually, I realized I was spending too much time on this, so I started developing an app to save time in the long run; **and get back to whats really important, punching trees 🌳**

## Development Goal

This project is a rebuild of [BedrockAddonTidy](https://github.com/harley-codes/BedrockAddonTidy), which only supported Windows and was an experiment built over three days. My goal is to deliver the best possible user experience, with easy app updates and full cross-platform compatibility. The new application will be availible on Windows, MacOS, Android and iOS.
