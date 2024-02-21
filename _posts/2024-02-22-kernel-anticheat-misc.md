---
title: "Miscellaneous stuff for Kernel-level Anti-cheats on Windows"
published: true
---

Run either `Command Prompt` or `Terminal` as an administrator.

Driver names for kernel-level anti-cheats:
- xhunter1 - XIGNCODE3
- mhyprot2 - Genshin Impact
- unifairy - Honkai: Star Rail
- EasyAntiCheat_EOS - Easy Anti-Cheat

Commands:

**Check the status of an anti-cheat driver:**

```
sc query DRIVER_NAME
```

**Stop an anti-cheat driver:**

```
sc stop DRIVER_NAME
```

**Completely delete/uninstall an anti-cheat driver:**

```
sc delete DRIVER_NAME
```
