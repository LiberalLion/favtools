# MЧ fЧv0Г17Э 1337 H4Ж0Я T00Lz + everyday ones (:

Hope y'all like this repo cuz these are tha best ayyy

# Hacking TOOLS with links
PROGRAM | DESCRIPTION
--- | ---
[Apktool](https://github.com/iBotPeaches/Apktool) | Apk reversing
[Burp Suite](https://portswigger.net/burp/communitydownload) | Best proxy
[Crunch](https://github.com/crunchsec/crunch) | Custom wordlist generator
[Cutter](https://github.com/radareorg/cutter) | Radare2(reversing tool) gui
[Dirsearch](https://github.com/maurosoria/dirsearch) | Directory, file fuzzing on web servers
[Enum4Linux](https://github.com/portcullislabs/enum4linux) | Windows, smb enumeration
[Ffuf](https://github.com/ffuf/ffuf) | **F**ast as **FU**ck web **F**uzzer (**written in go** btw)
[Ghidra](https://ghidra-sre.org) | NSA Reversing tool(**very good** btw)
[GitRob](https://github.com/michenriksen/gitrob) | Scan some1's github profile for creds
[GTFO](https://github.com/mzfr/gtfo) | [GTFOBins](https://gtfobins.github.io) **cli** fetcher(my **favorite** one)
[Hash Identifier](https://github.com/psypanda/hashID) | Identify hashes
[Httprobe](https://github.com/tomnomnom/httprobe) | Scan a list of **domains** if `http` {and,or} `https` is working
[LinEnum](https://github.com/rebootuser/LinEnum) | Linux privesc checker
[{Lin,Win}Peas](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite) | **New generation** linux, windows privesc checker
[RsaCtfTool](https://github.com/Ganapati/RsaCtfTool) | Get those keys boii
[SecLists](https://github.com/danielmiessler/SecLists) | **HUGE** repo of wordlist
[Pentestmonkey php-reverse-shell](https://github.com/pentestmonkey/php-reverse-shell) | Php revshell yes.. if u dont know whats the use of this learn more about hacking *dont be a skid*
[SqlMap](https://github.com/sqlmapproject/sqlmap) | Sql injection fuzzer, checker
[Subfinder](https://github.com/projectdiscovery/subfinder) | Passive subdomain discovery tool(**faster** than `Sublist3r` btw)
[Sublist3r](https://github.com/aboul3la/Sublist3r) | Subdomain lister from search engines
[Stego-Toolkit](https://github.com/DominicBreuker/stego-toolkit) | Best for stego challs
[Unfurl](https://github.com/tomnomnom/unfurl) | Returns only the *domain* of **long** ass **urls**
[Waybackurls](https://github.com/tomnomnom/waybackurls) | Fetch the wayback machine for known urls of a domain


# Password manager
PROGRAM | DESCRIPTION
--- | ---
[Bitwarden](https://bitwarden.com) | Just a pw manager very casual


# Desktop
PROGRAM | DESCRIPTION
--- | ---
[dwm](https://dwm.suckless.org) | Best wm, **written in c**, what else do u need?!
[dmenu](https://tools.suckless.org/dmenu) | Best fkin program in the whole universe (Just take a look at my [scripts repo](https://github.com/matesz44/scripts) :D)
[slstatus](https://tools.suckless.org/slstatus) | Statusbar for dwm
[nnn](https://github.com/jarun/nnn) | Best filemanager (**written in c** btw)
[sxiv](https://github.com/muennich/sxiv) |  Image viewer **written in c** like every good program
[wmname](https://tools.suckless.org/x/wmname) | Rescale fixer for java apps


## My builds
- [My build of dwm](https://github.com/matesz44/dwm)
- [My build of slstatus](https://github.com/matesz44/slstatus)


# Tips n tricks

## Extra tips, shortcuts
- Fast start `stego-toolkit` in **current dir**:
  ```
  sudo docker run -it --rm -v $(pwd):/data dominicbreuker/stego-toolkit /bin/bash
  ```

## Bug fixes for java programs in `window managers`
- If u want to use automatic rescale in **java** apps like `burp` u will need [this](https://superuser.com/questions/400766/netbeans-java-shows-empty-window-in-tiling-window-manager-awesome-wm): 
  ```
  wmname LG3D
  ```
- **FIX** for ghidra(java app btw) blank window in window managers:
  ```
  export _JAVA_AWT_WM_NONREPARENTING=1
  ```
- **FIX** for weird fonts in java apps:
  ```
  export _JAVA_OPTIONS='-Dawt.useSystemAAFontSettings=lcd'
  ```


# Other bash scripts
LINK | DESCRIPTION
--- | ---
[scripts](https://github.com/matesz44/scripts) | Some very useful dmenu scripts that I use daily


# Other wordlists
[dirbuster directory-list-2.3-](https://github.com/daviddias/node-dirbuster/tree/master/lists)  
- [directory-list-2.3-small.txt](wordlists/directory-list-2.3-small.txt)
- [directory-list-2.3-medium.txt](wordlists/directory-list-2.3-medium.txt)
- [directory-list-2.3-big.txt](wordlists/directory-list-2.3-big.txt)  

[dirbust common.txt](wordlists/common.txt)


# Arch install
LINK | DESCRIPTION
--- | ---
[Arcolinux Archway install](https://arcolinuxd.com/5-the-actual-installation-of-arch-linux-phase-1-bios) | A vanilla arch step by step install with explainations


