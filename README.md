# El Chapo
A simple tool for managing SSH tunnels from the terminal

---

I got tired of copying my SSH tunnel commands from a text file and pasting them into my terminal. So, I created this simple little bash script to manage them. 

Requires Bash version 4 or higher.

Usage:
1. Copy/move `tunnels.sample` to `$HOME/.tunnels`
2. Add your tunnels to that file in the specified format
3. `elchapo <tunnel_name> <action>`


**Bring tunnel up**
```bash
elchapo <name> up
```

**Bring tunnel down**
```bash
elchapo <name> down
```

**Check status of tunnel**
```bash
elchapo <name> status
```


