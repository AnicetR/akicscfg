# CS Config Installation Guide

This guide explains how to install your custom config for Counter-Strike using your Steam user ID.

## Steps
  
  - Open File Explorer.
  - Navigate to:
    ```
    C:\Program Files (x86)\Steam\userdata\895250177\730\local\cfg
    ```
    - `895250177` is your Steam user ID.
    - `730` is the app ID for CS:GO/CS2.

1. **Copy Your Configuration Files**

  - Place your configuration files (such as `autoexec.cfg`, `config.cfg`, or any custom `.vcfg` files) into the `cfg` folder mentioned above.
  2. **Understanding and Using `autoexec.cfg`**
  - To ensure it loads, add the following launch option in Steam:
      ```
      +exec autoexec.cfg
      ```
  - To edit `autoexec.cfg`, open it with a text editor (like Notepad), make your changes, and save the file in the `cfg` folder.
  - You can also open the console and run `exec autoexec.cfg`
  
---

**Need help?**
Refer to the [Steam Support](https://support.steampowered.com/) page for more info.
