# Big Awesome List of TODOs 

This repo is a main place to keep track of things I want to work on and store in github. Mainly for learning and POC purposes. I have every intention of doing all these things.

---

* icmp rootkit that allows pilfering data and knocking for a shell targeting linux and freebsd. I love the idea of leveraging icmp and it would help me get rolling in hacking kernels.
    * PoCs: https://github.com/silaspsadia/mischief https://github.com/m0nad/Diamorphine https://github.com/ljcusack/freebsd-rootkit
    * Books: "Designing BSD Rootkits" from NoStarchPress

* software for nanopi r1 and r2s, that allows it to be a transparent ethernet cable plant. mainly for pilfering data, hoping to find creds. It should apply multiple measures to remain invisible, which I'm not entirely sure of yet, but I thinking it should at least change the mac address to masquerade as the original machine. (a)-(b) -> (a)-(b:nanopi r1:a)-(b). 
    * possibly check out https://github.com/bettercap/bettercap
    * also get a label maker, for that "DO NOT REMOVE" label adding a touch of realism (thanks https://twitter.com/heavhacker for making me labels). Buy asset tag stickers, too?! Full-on larping these things right now. 

* provisioning to create labs in vmware, done as automatically as possible

* slide decks for presentations (teaching others is a good way to prove you learned stuff, also teaching stuff is rewarding for its own sake):
    * embracing being a scrub
    * learning from failure
    * learning to shut up and listen and actually learn things from other humans
    * buffer overflows
    * reverse engineering with ghidra
    * reverse engineering and binary exploitation with rizin
    * using gef+gdb
    * writing scripts for rizin
    * teaching how to hack into machines
    * teaching how to hack into AD
    * teaching how to hack into AWS
    * teaching how to hack into Azure AD
    * attacking application supply chains
    * how to welcome new hacking friends into the fold and help them out, everyone is welcome, there's no special handshake (if there is, I don't know it)

* get gud with c, write a personal port of "blackhat python"/"blackhat go" (nostarchpress) but for c 

* write a command and control client and server in C and python, possibly with a with an irc/slack/discord bot(s)?! 
    * https://github.com/sogonsec/ori


* write N-day exploits, not for all that sweet N-day glory but to figure out the problem and write it, should be a good learning experience

* training course for hacking stuff? That's a big one, probably shouldn't be in here. teaching stuff, etc.

* rogue "canary" plant, but instead of raising alarms, steal creds and ship them off to a remote location. Also delete all trace of transfer as much as possible (delete transfer info/logs... possible secure delete/erase the device/sd card, be sure be mindful of cached data in ram or other buffers)

* do writeups:
    * SQLi basics, mainly stuff used in CTF challenges/competitions
    * XSS basics, mainly stuff used in CTF challenges/competitions
    * VulnHub series (VMs that are from the same author and collection, like digitalworld.local) walkthroughs and pentest report example
