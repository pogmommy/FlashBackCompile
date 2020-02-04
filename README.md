# FlashBackCompile
FlashBack Compile Repo

This is the compilation setup portion of the Jailbreak utility "FlashBack"
To compile FlashBack as a deb:
1. build **https://github.com/MPG13/FlashBack** and copy the .app to **[FlashBackCompile/FlashBack/Applications/FlashBack.app]**.
2. Copy the script binaries from **https://github.com/MPG13/FlashBackScripts** to **[FlashBackCompile/FlashBack/usr/bin]**
3. Navigate to FlashBackCompile in a terminal, and run 

    dpkg -b FlashBack FlashBack.deb

