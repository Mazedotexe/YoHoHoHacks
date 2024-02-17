# YoHoHo.io hacks
This repository contains hacks for the browser game YoHoHo.io made by me. The source code is obfuscated, but if you want the pure source, DM me on Discord (@mazedotexe).
### How to run
Go to a script you would like to use (for example, `maxStats.js`) and copy the code. Then, go to YoHoHo.io and hold down the buttons Ctrl, Shift, and J to open the DevTools (Command-Shift-J on Mac.) Paste the code in (Ctrl-V, or Command-V) and press enter. The script should run.

### Alternate running methods
If you can't use DevTools (like if you're on a school computer) you don't have many options. For ChromeOS versions 114 and below, you may be able to use a **bookmarklet** to run the code. To test if you can use a bookmarklet, bookmark any page (New Tab is good), right-click the bookmark, and click "Edit." You can change the name of the bookmark if you want, and then go into the box next to "URL" and paste in the code below.
```
javascript:alert("Hello!")
```
Then, click the Save button and go back to this page. Click the bookmarklet, and if a greeting box appears, bookmarklets are an option. To use the code as bookmarklets, repeat the steps above, except this time, type "javascript:" in the box next to "URL" and then paste the code for the script you want to run. Click the bookmarklet on YoHoHo.io, and if it doesn't work, you can once again contact me through Discord or make an issue on this repository.

Another option is to try to abuse an extension that allows running custom JavaScript on a page. Some schools use the extension uBlock Origin, which [does allow](https://github.com/3kh0/ext-remover?tab=readme-ov-file#urun---bypass-bookmarklet-restrictions-with-ublock) you to run scripts, and my school uses an extension called [Shortkeys](https://chromewebstore.google.com/detail/shortkeys-custom-keyboard/logpjaacgmcbpdkdchjiaagddngobkck?hl=en-US&gl=US&pli=1) which allows you to create keyboard shortcuts with custom actions, such as running JavaScript. If you can't use either of these extensions, and you can't run bookmarklets, it may mean that you can't use the scripts, but you could always just use a different device.
