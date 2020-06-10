# How to start as a Beginner

Cybersecurity is actually a very broad term. There's a broad range of professions you can choose to target such as exploit development, consulting, analyst, adminstration or penetration testing. Obviously, each role has different skills that you may need to know but in general, it is important to know the basic vulnerabilities. Some of these vulnerabilities include XSS, Buffer Overflow and SQL Injection. These are just basic vulnerabilities but are a great way to get introduced to the Web category (XSS, SQL Injection) and the Binary Exploitation category (Buffer Overflow). There are alot more vulnerabilities that will introduce you to other categories and that's what CTF is really useful for. CTFs will have different categories that require different skillsets and is good to find what categories you would like to specialise in whilst knowing what the other categories are like. CTFs are all about experience and practice so don't be disheartened if you can't solve any challenges on your first attempt. More than likely, you will need some sort of pre-requisite knowledge, HOWEVER, challenges may actually still be doable through the use of researching. This is where the golden statement comes into place. Google is your best friend. 

What are the categories?

- Binary Exploitation
- Web
- Forensics
- OSINT
- Cryptography
- Reversing
- Miscellaneous
- OSINT

You will experience what these categories are about through experience. Now I will introduce some sites that will get you started with CTF challenges.

**Beginnner CTF Sites**

Some sites will be harder than other so make sure to go through each resource to see what site suits your starting level. They will obviously have hard challenges as well so if you're beginner I would probably just skip those.

When you're doing the challenges don't be afraid to look up walkthroughs for the challenge when you get stuck. The process for learning is to practice the way to logically go through problems as well as building your hacker toolbox where you record what tools you use and always write notes. There is so many technologies to learn and it is basically impossible to remember every little detail so keeping notes is essential.

Links:

- PicoCTF: https://picoctf.com/
- Overthewire (Natas): https://overthewire.org/wargames/natas/
- Overthewire (Bandit): https://overthewire.org/wargames/bandit/
- AngstromCTF: https://angstromctf.com/
- Hacker101 CTF: https://ctf.hacker101.com/
- PentesterLab: https://pentesterlab.com/


## Moving on from introductory challenges

When you're starting to get the hang of challenges of some the challenges and you start encountering tools that you may need to use such as burp, curl, wget, gobuster or wfuzz, it is good to create a hacking environment to keep your tools all in one place and to not mess with your host environment which you would use for personal stuff or for university work.

A way of doing this is the use of Virtual Machines. They are basically a virtual computer that exists within your current computer, taking a subset of the resources from your host and will act as another computer. Kali will be the OS that you will use for your Virtual Machine as it contains most of the tools you already need while also being a Linux distribution (useful for praciting CLI usage).

Personally I use [VirtualBox](https://www.virtualbox.org/) and import [Virtual Machine Image from Offensive Security](https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/).

**Guides to setting up Kali**

- https://itsfoss.com/install-kali-linux-virtualbox/ (I use this one)
- https://phoenixnap.com/kb/how-to-install-kali-linux-on-virtualbox

## Learning to use Kali

Once you have setup your Kali Virtual Machine, it's time to start learning the command line. This is a REALLY important skill to know as it makes going through challenges alot quicker (especially if you're a fast typer). Alot fo tools that you will use is also only on the CLI and may not have a GUI.

To start learning how to use the CLI, you can start here http://linuxcommand.org/ or https://ubuntu.com/tutorials/command-line-for-beginners#1-overview.

There are alot of other resources out there so feel free to just google "Linux Command Line Tutorials" and find youtube tutorials as well.

Actually learning how to use the tools installed in Kali will be dependent on when you actually need to use them. So all the tools on Kali you probably won't use but it's worth having them already installed so when you come upon a challenge say "crack this hash", there is a tool called John or Hashcat which are already installed in Kali which you can use straight away after googling some tutorials on how to "crack hashes in Kali".


## Happy hacking!

Feel free to message on the MACs discord channel #cybersec if you need help with a challenge or stuck on setting up or using a tool. 

[Find discord server and contact details here](../../README.md)

That's all I have for now in terms of beginner resources. I may add more in the future so make sure to follow this repository.

To add:
- Vulnhub
- CTFTime
- Category Specific Information