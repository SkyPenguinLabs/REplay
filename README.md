![SkyPenguinCTFBanner.PNG](B2.PNG)

# Intro To REplay
REplay is a high-end and low-profile gutted game cheat written in C++20 that was designed to toss people into real-life environments to practice software cracking. This project was designed and developed due to the lack of playgrounds and projects to practice reverse engineering outside of smaller command line based environments. For example- small crackmes are amazing for beginners, but when you transition into the real world, oftentimes, you sit through thousands of symbols, functions, and more. So we thought, why not develop something semi-real world. 

This is a game cheat, but after development, a copy of the source was made, driver code & exploit code was **mostly** removed and the mass amount of security systems were removed and replaced with basic checks. We then inserted the code with sets of sensitive information, hardcoded passkeys, algorithms, and more that can be used to practice reverse engineering. 

# Running the CTF
This GUI needs specific files to load (because the developer, Totally_Not_A_Haxxer) was lazy and did not rip out the offset requirement system. So, run the exe once and CMD will appear, then re run the file in the same exact directory before and then you should see the GUI pop up if the files exist in the directory. 

These files are 

* `client.dll.json`
* `offsets.json`


# Playing the CTF
The CTF is simple to play. Simply load the EXE up and toss it into IDA or Ghidra for static analysis and a tool of your choice for dynamic analysis. Of course, we could not leave you without information. So here are some things you should know.

## Scenario 
In this scenario, you are a reverse engineer who cracks black-hat frameworks (unethical frameworks such as DDoS panels) for a living and re sells them. You come across a game cheat that you want to crack, crack it, and also document specific information about the program including an undocumented button that shuts down the menu. Many users as we have also seen, complained that when pressing tab exits the menu conflicting with other options- find this virtual key and modify it to become another key. When you are done with both main tasks, go on a hunt to see what else you can find about this cheat.

## Other information
For more information, such as writeups, documentation, information, extra docs and more- check out the GitBook.

https://skypeguinsolutions.gitbook.io/replay-reverse-engineering-playground/

