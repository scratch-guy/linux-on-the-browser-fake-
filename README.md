# JS Fake Linux Shell

A tiny **interactive Linux shell simulation** built entirely in JavaScript and HTML.  
This project simulates a fake Linux boot process and allows you to interact with a minimal filesystem in the browser.
check out [the page to this project](https://scratch-guy.github.io/linux-on-the-browser-fake-/)
---

## Features

- Fake Linux boot sequence (`vmlinuz`, `initrd.img`, `/init`)  
- Interactive shell prompt (`$`) using an input box  
- Base64-encoded “ELF files” decoded with a custom `execute()` function  
- Simple fake filesystem (`fs`) with files and directories  
- Command not found handling (`ash: <command>: command not found`)  
- `load_backup()` function to restore the original filesystem  

---

## Files

- `index.html` — main HTML page with terminal interface   

---

## Usage

1. Open `index.html` in a modern web browser.  
2. The boot sequence will automatically run:  

