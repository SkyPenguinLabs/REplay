![SkyPenguinCTFBanner.PNG](B2.PNG)

# Intro To REplay
REplay is a high-end and low-profile gutted game cheat written in C++20 that was designed to toss people into real-life environments to practice software cracking. This project was designed and developed due to the lack of playgrounds and projects to practice reverse engineering outside of smaller command line based environments. For example- small crackmes are amazing for beginners, but when you transition into the real world, often times, you sit through thousands of symbols, functions, and more. So we thought, why not develop something semi-real world. 

This is a game cheat, but after development, a copy of the source was made, driver code & exploit code was **mostly** removed and the mass amount of security systems were removed and replaced with basic checks. We then inserted the code with sets of sensitive information, hardcoded passkeys, algorithms, and more that can be used to practice reverse engineering. 

# Playing the CTF
The CTF is simple to play. Simply load the EXE up and toss it into IDA or Ghidra for static analysis and a tool of your choice for dynamic analysis. Of course, we could not leave you without information. So here are some things you should know.

## Technical Information
This CTF is GUI based, written in C++20, and was built using Microsoft Visual Studio with ImGui and D3DX11 implementations.

## Level Information
Currently, we only have one level finished and done, so this is a 'beta-test' you can call it for the entire idea. This level has basic encryption techniques, basic anti-debug techniques, and a plethora of information to gather. This level was designed for beginners. However, in the future there will be other levels which are intermediate and expert levels.

> Intermediate
This level will be for people who know reverse engineering well. It will include many strong anti-analysis techniques, will include many anti-sandboxing techniques and will include stronger encryption and larger logic + more advanced system breaking. We will also require you to know a tad bit of binary auditing to spot flaws in the binaries code.

> Expert/Practitioner 
This will be the hardest level yet. It will compress every level together, lock the programs process down, heavily secure and mask information and data, prevent basic to advanced analyzers, and will require skillsets in binary analysis, binary auditing, exploit development, Windows internals, key generation & algorithm reverse engineering, standard software cracking, logic manipulation, and more. This will be a full fledged highly advanced version of the playground that was designed to be mostly real world.

## What to solve for?
This CTF is an entire playground and there is more to reverse engineer than the defaults we provide. But we did decide that in order to make it fun, there should be some things that you need to do as `goals` for completing each new level. In this case, we decided to create a simple list.

> Here are your goals for the first level

* 1: Find the unencrypted API key 
* 2: Find the HTTP-BasicAuth formatted username and password
* 3: Find the CTF information block
* 4: Find the encrypted API key
* 5: Crack the first login system
* 6: Modify the variable of the hide menu functionality
* 7: Find out what was the authentication server where the HTTP auth was used?
* 8: Find out what protocol was the authentication server in
* 9: Find out what security systems were used in this CTF
* 10: Figure out a base map of the control flow in the programs first login system. Draw out a pseudo code example of how this works.
* 11: Find the integer based key used to compare the input license in the GUI. 
* 12: Figure out where the pre-determined login statement is being made. This is the statement in which is outputted or drawn onto the GUI before the login button and the input box are rendered. 
* 13: Find the hotkey that is used to exit the menu and kill the current process 
