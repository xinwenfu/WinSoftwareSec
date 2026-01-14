# Windows Advanced Memory Corruption Attack and Defense Teaching Modules

## Lab Environment 

### Windows
* All labs work on Windows 10/11.
* Minimum requirement. [Vunerable Chat (VChat) Server: VChat.exe, Essfun.dll](https://github.com/xinwenfu/vchat/tree/main/Server). VChat GUI.exe can start VChat.exe as a background process although not really needed. If our Windows VM is used, VChat is installed by default.
  * C:\Tools\vchat\VChat.exe
  * If VChat.exe is accidentally removed, copy from C:\Tools\vchat\Backup
* Disable Windows Firewall by default
* Disable all Exploit Protection features by default

### Kali
Our [Customized Kali VM](https://www.cs.uml.edu/~xinwenfu/Tools/Kali-40G-2025.ova) is installed with tools Kali does not ship by default and also our own tools.
* boffuzz
* Customized Armitage
* Vunerable Chat (VChat) client: /home/kali/GenCyber/vchat/Client/client.py

## Defense modules
1. [Control Flow Guard (CFG)](https://github.com/DaintyJet/VChat_CFG)
2. [Address Space Layout Randomization (ASLR)](https://github.com/DaintyJet/VChat_ASLR_Intro)
3. [Data Execution Protection (DEP)](https://github.com/DaintyJet/VChat_DEP_Intro)
4. [Structured Exception Handling (SEH) Defenses](https://github.com/DaintyJet/VChat_SEH)
5. [Security Cookies/Buffer Security Checks](https://github.com/DaintyJet/VChat_Security_Cookies)
6. [Validate Heap Integrity](https://github.com/DaintyJet/VChat_Heap_Defense)

## Attack modules
1. [VChat TRUN - Basic Buffer Overflow](https://github.com/xinwenfu/VChat_TRUN)
2. [VChat GTER - Egg Hunters](https://github.com/xinwenfu/VChat_GTER_EggHunter)
3. [VChat GTER - Code Reuse](https://github.com/xinwenfu/VChat_GTER_CodeReuse)
4. [VChat GMON - Structured Exception Handling (SEH)](https://github.com/xinwenfu/VChat_GMON_SEH)
5. [VCHAT KSTET - Multistage Shellcode (recv)](https://github.com/xinwenfu/VChat_KSTET_Multi)
6. [VChat KSTET - Multistage Shellcode (DLL)](https://github.com/xinwenfu/VChat_KSTET_DLL)
7. [VChat LTER - Bad Characters](https://github.com/xinwenfu/VChat_LTER)
8. [VChat TRUN - Introduction to Data Execution Prevention (DEP)](https://github.com/xinwenfu/VChat_DEP)
9. [VChat TRUN - Understanding ROP](https://github.com/xinwenfu/VChat_ROP_INTRO)
10. [VChat TRUN - ROP Attack](https://github.com/xinwenfu/VChat_TRUN_ROP)
11. [VChat TRUN - Brute Force: DEP & ASLR Bypass](https://github.com/xinwenfu/VChat_Brute_Force)
12. [Heap Overflow Examples](https://github.com/DaintyJet/Heap-Overflow-Example)
13. [VChat - Heap Overflows](https://github.com/DaintyJet/VChat_Heap_Exploit)

<img src="imgs/NSF_logo.png" height=100>
