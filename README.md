# Reimu's Competitive Programming Resource Shrine
This is a collection of various resources that I found while training for competitive programming that I want to share. Please do keep in mind that this resource hub is primarily targeted for Filipino high school students (especially to my fellow PSHS-SRC peeps) in preparation for programming competitions such as the National Olympiad of Informatics Philippines (NOI.PH). There may be specific resources that may not be less applicable or useful for your situation, however you can still use this resource hub as you may like.

If you believe there's something that you wish to be included here, feel free to share it to me or make a pull request for your edits. I would really appreciate your help!

You can start by browsing the different topics that will be covered here in the Table of Contents below.

## Table of Contents
- [Programming Languages](#programming-languages)
- [Language Documentation](#language-documentation)
- [Text Editors/IDEs](#text-editorsides)
- [Problem Sets/Archives](#problem-setsarchives)
- [Recommended Contests](#recommended-contests)
- [Competitions in PH](#competitions-in-ph)
- [Resource Hubs/Websites](#resource-hubswebsites)
- [YouTube Channels/Series](#youtube-channelsseries)
- Books/Readings
- Math Resources
- Sources for Advices/Tips
- Miscellaneous

## Programming Languages
To be honest, you can use any language for competitive programming, as long as it is supported to the contest that you are participating. In other words, your choice of programming language is up to your preferences. However, I'd recommend to learn the following languages due to the amount of support in contests and certain reasons.

1. **C++**
    - C++ is pretty much the standard language for competitive programming. C++ code runs really fast, the Standard Template Library (STL) contains a lot of useful utility functions, and is available in a lot of contest platforms. One downside I would say is that you do need to have some idea with its technicalities, and that you might struggle with implementation because of that.
2. **Python**
    - Although Python is not really recommended if you really want to be serious with competitive programming, it is a good starting language for beginners. It is a very simple language to learn, and you can write code really fast with it. And because of that, you can focus more on thinking about your solution. Personally, switching to Python has made me learn much more faster, however I did switch back to C++. One major downside which makes it not viable at all times is its speed. Even if your code has the intended running time for the problem or that the problem has tight input bounds, your code most likely will not pass due to time limit exceeded. In that case, you might be better off using a faster language like C++. You can still find value with it as it is a really good language if you want to quickly write bruteforce solutions or test case generators or any utility scripts during the contest. 
3. **Java**
    - Java is in the middle ground of both C++ and Python in terms of speed. I don't use Java that much, but from what I vaguely know, it is pretty verbose, especially if you want fast IO. However, if you are already familiar with Java more than the others, then you can still stick with it for competitive programming.

For learning the basics of these languages, some stuff you can check are:
- [W3Schools](https://www.w3schools.com/) for any language really (my go-to place)
- [FreeCodeCamp.org's videos](https://www.youtube.com/@freecodecamp) for any language as well + if you prefer video form
- [LearnCPP](https://www.learncpp.com/) for C++
- [NOI.PH Python Tutorials](https://noi.ph/python-tutorials/) for Python 

For C++ stuff for competitive programming, you can check
- Chapter 1 Section 1 and Section 4 of Laaksonen's book, [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf). 
- NOI.PH team's [C++ for Competitive Programmers Knowing Python](https://docs.google.com/document/d/1c66WJAY8AHIYInEd3roXMS2LBKf6YrcD7O_9Y-cgU2U/edit?usp=sharing) if you want to transition from Python to C++.

To be honest, I learned more from looking at other people's code. One place of this is in the code snippets of contest editorials (like in [Codeforces](https://codeforces.com/)), but you can always check the editorials prepared in any contest that you participated in (if there are any). Even if you solved a problem by yourself, I'd still recommend checking these out for certain techniques.

## Language Documentation
Language documentation is really good if you want to learn more about the various libraries/modules, functions, types, and other technicalities of a language, especially if you're unsure of a certain functionality of what you're about to use. It's usually best to use official documentation for your languages.

For offline documentation, you have:
- [Zeal](https://github.com/zealdocs/zeal) - a really convenient documentation software for a lot of languages.

For language-specific documentation websites:
- [cppreference.com](https://en.cppreference.com/w/) - C++
- [cplusplus.com](https://cplusplus.com/reference/) - C++
- [Official Python documentation](https://docs.python.org/) - Python
- [Oracle's Java documentation](https://docs.oracle.com/javase/8/docs/api/overview-summary.html) - Java

Java also has JavaDoc, which you can directly read through "Javadoc" tab of Eclipse. I'm not sure how to directly access it in NetBeans, sadly.

## Text Editors/IDEs
Similar to programming languages, your choice of text editor/IDE is up to your preferences. Unlike actual development projects, competitive programming is not that demanding for what tools you need. With that, I will mostly be recommending lightweight text editors, but I will also list some IDEs here and there. 

Here are some editors that I have used:
- [Visual Studio Code](https://code.visualstudio.com/)
    - everyone's favorite text editor (I'm currently using this now to write this). Do keep in mind that it is different than Microsoft's [Visual Studio](https://visualstudio.microsoft.com/). That one is too much for competitive programming. VSCode has a lot of support through its massive extension ecosystem, has a lot of features like having a debugger, and can pretty much be used for any language. It also has a good integrated terminal for whenever you need the command line, like compiling and running your code. One thing about it, however, is that it is an Electron app. It can take up a lot of your memory (which is why I didn't use it when I was still using my 4GB RAM laptop). However, it consumes less than an actual IDE. It also has telemetry by default if you really care about privacy (typical Microsoft product), but you can completely turn it off in the settings. 
- [Sublime Text](https://www.sublimetext.com/)
    - another text editor that a lot use. I haven't tried it for competitive programming, but I have used it a lot for personal projects. It is extremely lightweight compared to VSCode, and also has its own plugin ecosystem through its own package manager. It is technically not free though, but you can WinRaR your way out. I would say it's more convenient to setup some stuff in VS Code (like setting up an LSP for autocompletion), but for most of the time, you wouldn't worry about it since we're only focusing on competitive programming.
- [Geany](https://www.geany.org/)
    - another simple and lightweight text editor. This one is what I usually use in my old 4GB RAM laptop for C++. If you care about vim motions (which most likely you don't), its plugin for vim motions is pretty lacking, I would say. But that shouldn't matter for anyone, really.
- [IDLE](https://www.python.org/downloads/)
    - a simple IDE for Python that comes when installing Python. It's my go-to editor whenever I want to use Python because of its simplicity. One thing is that it is very limited in terms of functionality, but it should be good enough for competitive programming.
- [DevC++](https://www.bloodshed.net/)
    - classic C++ lightweight IDE. It's pretty old, though, but that's pretty much it.
- [NetBeans](https://netbeans.apache.org/front/main/index.html)
    - IDE for Java. I don't use Java other than schoolwork, so I have nothing to say. The times I used Java in competitive programming is with VSCode.
- [Eclipse](https://eclipseide.org/)
    - IDE for Java. Again, I have nothing else to say.
- [Vim](https://www.vim.org/)/[Neovim](https://github.com/neovim/neovim)
    - Highly not recommendeded if you're new. Vim is designed to be keyboard-only. As such, it has its own workflow, motions, and keybindings that are different from the typical text editor, which introduces an additional steep learning curve that is really optional to take. Take this up if you feel like learning Vim motions is something that will help you a lot and that you have the willingness and patience to pick it up and set it up.
    - With that said, I am actually using vim motions in VSCode to write this. And Neovim, in particular, is my go-to editor whenever I use my Linux partition in my old laptop. Because of that, I would recommend these if you're a person who wants their workflow to be in the terminal, and out of the two, I would recommend Neovim + [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim). Neovim is essentially Vim improved-ish, and kickstart.nvim lets you have a better out-of-the-box experience with Neovim. If you're a beginner, however, it's just best to ignore vim for now as it's more important to train your actual problem-solving skills than learning some complex keybindings.
- [gVim](https://www.vim.org/)
    - GUI for Vim. It is installed when you install Vim, at least in Windows. Same things as above, really.

The following are editors and IDEs that I haven't tried yet, but will include in here to let you explore them and see if it's for you:
- [PyCharm](https://www.jetbrains.com/pycharm/download/)
    - JetBrains' Python IDE. Community Edition should be good enough for competitive programming. Since it is an IDE, it's quite heavy in your resources.
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
    - JetBrains' Java IDE. Similar to its Python counterpart, it is quite heavy in your resources.
- [Code::Blocks](https://www.codeblocks.org/)
    - classic editor for C++. Sadly, I haven't tried it out ever, so I can't really say anything much about it.
- [Kate](https://kate-editor.org/)
    - a simple and lightweight editor made by KDE.

I strongly wouldn't recommend using an online editor, as it can make your code prone to leaks. But if you really do need one, there's [CodeChef's Online Compiler](https://www.codechef.com/ide) and [Codeforces' Custom Test](https://codeforces.com/problemset/customtest) (requires Codeforces account).

## Problem Sets/Archives
These are some websites where you can get problems to solve:
- [Codeforces](https://codeforces.com)
- [Atcoder](https://atcoder.jp)
- [CSES's Problem Set](https://cses.fi/problemset)
- [oj.uz](https://oj.uz)
- [USACO Guide's Problems](https://usaco.guide/problems/)
- [Kattis](https://open.kattis.com)
    - contains ICPC problems
- [NOI.PH Problem Archive](https://noi.ph/elims-finals-archive/)
- [CodeChef](https://www.codechef.com/)
- [Library-Checker](https://judge.yosupo.jp/)
- [Sphere Online Judge (SPOJ)](https://www.spoj.com/)
- [DMOJ](https://dmoj.ca/)
- [TLX](https://tlx.toki.id/)
- [Project Euler](https://projecteuler.net/)
- [HackerRank](https://www.hackerrank.com/)
- [Online Judge](https://onlinejudge.org/)
- [LeetCode](https://leetcode.com/)

## Recommended Contests
If you're new to competitive programming, here are some contests that I recommend that will give you a good place to start learning how it works and building your knowledge and skills as a beginner. There are also some that I believe are good if you want to practice for NOI.PH. 
- [Abakoda Short Rounds](https://noi.ph/abakoda-2023/)
- [Abakoda Long Contests](https://noi.ph/abakoda-2023/)
- [Atcoder Beginner Contests (ABC)](https://atcoder.jp/contests/)
- [Codeforces Div 2-4 Contests](https://codeforces.com/contests?complete=true)
- [NOI.PH Contests Archive](https://noi.ph/elims-finals-archive/)
- [UP Algolympic Elimination Rounds](https://codeforces.com/group/fDKsZH3HKS/contests)
- [USACO Guide Contests](https://joincpi.org/contests)
- [USACO Contest Archive](https://usaco.org/index.php?page=contests)

## Competitions in PH
Here are some competitions currently or previously hosted in the Philippines that you can join or check for practice. Note that I am a highschooler and are not too familiar with the collegiate scene. And so, I will primarily be including those present for high schoolers.
- [National Olympiad in Informatics - Philippines (NOI.PH)](https://noi.ph)
- [Ateneo de Manila University DISCS Programming Open (PrO)](https://www.facebook.com/admudiscs)
- [Abakoda Short and Long Contests](https://noi.ph/abakoda-2023/)
- [Tool-Assisted Mathematics (TAMa)](https://noi.ph/tama-2023/)
- [University of the Philippines' Algoylympics Series](https://algolympics.upacm.net/2024/)
- [Pisay Competitive Programming Competition](https://www.facebook.com/share/p/qnLQzRiFNmembLHb/)
- [2021 Ateneo de Manila Senior High School Dagitab Programming Contest](https://codeforces.com/contests/102911)
- [ICPC Asia-Manila Regional Contests](https://codeforces.com/gym/104118)

## Resource Hubs/Websites
- [USACO Guide](https://usaco.guide/)
- [CP-Algorithms](https://cp-algorithms.com/)
- [NOI.PH](https://noi.ph/prepare/)
- [Codeforces Catalog and Blogs](https://codeforces.com/catalog)
- [TopCoder Thrive](https://www.topcoder.com/thrive/tracks?track=Competitive%20Programming)

> TODO: add more entries zzz

## YouTube Channels/Series
The following are YouTube channels/series that you can watch to learn more about various data structures, algorithms, techniques, and tips in video form. 
- [Errichto Algorithms](https://www.youtube.com/@Errichto)
- [Colin Galen](https://www.youtube.com/@ColinGalen)
- [Algorithms Live!](https://www.youtube.com/@AlgorithmsLive)
- [SecondThread's AlgorithmsThread](https://youtube.com/playlist?list=PLZU0kmvryb_HZpDW2yfn-H-RxAu_ts6xq&si=nXJkRrwicYJpxqHb)
- [MIT OpenCourseWare's Introduction to Algorithms](https://youtube.com/playlist?list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&si=Nx6prJRjOeh79Yc-)
- [WilliamFiset](https://www.youtube.com/@WilliamFiset-videos)
- [Abdul Bari](https://www.youtube.com/@abdul_bari)
- [CS Dojo's Data Stuctures and Algorithms videos](https://youtube.com/playlist?list=PLBZBJbE_rGRV8D7XZ08LK6z-4zPoWzu5H&si=jGWG_EcaIksHj_CP)
- [Reducible](https://www.youtube.com/@Reducible)