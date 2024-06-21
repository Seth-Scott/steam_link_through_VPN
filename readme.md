# Steam Link through VPN

[CODE SOURCE](https://www.reddit.com/r/Steam_Link/comments/uiq2w9/steam_link_on_a_locked_pc/i7i84tj/)

I want to use Steam Link on another computer outside of my network through a VPN, but I need to RDP into my PC to launch Steam in Big Picture Mode. **If I don't do the following, I will get snagged on a Windows login screen and will be unable to login/enter passwords/pin.**

## Steps:
1. Lanuch WireGuard/VPN software on external client machine and connect to home VPN
2. Open RDP software on external client machine (Microsoft Remote Desktop on Macbook in my case) and connect to Steam host PC (Windows 11 Pro in my case)
3. Start Steam, enter big picture mode
4. Minimize Steam (there's a minimize button in the power settings)
5. launch `disco.bat` as admin
6. Get booted from RDP session. You will remain logged in, but the RDP session will be terminated. 
7. Launch Steam Link on external client machine (which of course, is still connected to VPN)
8. Enjoy Steam Link from outside of your network

## Why not just game with RDP? 
Refresh rate too low

