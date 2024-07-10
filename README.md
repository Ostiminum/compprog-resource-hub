# Reimu's Competitive Programming Resource Shrine
This is a collection of various resources that I found while training for competitive programming that I want to share. Please do keep in mind that this resource hub is primarily targeted for Filipino high school students (especially to my fellow PSHS-SRC peeps) in preparation for programming competitions such as the National Olympiad of Informatics Philippines (NOI.PH). There may be specific resources that may not be less applicable or useful for your situation, however you can still use this resource hub as you may like.

If you believe there's something that you wish to be included here, feel free to share it to me or make a pull request for your edits. I would really appreciate your help!

You can start by browsing the different topics that will be covered here in the Table of Contents below.

## Table of Contents
- [Programming Languages](#programming-languages)
- [Language Documentation](#language-documentation)
- [Text Editors/IDEs](#text-editorsides)
- Problem Sets/Archives
- Recommended Beginner Contests
- Recommended Youtube Channels/Series
- Resource Hubs/Websites
- Books/Readings
- Math Resources
- Sources for Advices/Tips
- Miscellaneous

## Programming Languages
To be honest, you can use any language for competitive programming, as long as it is supported to the contest that you are participating. In other words, your choice of programming language is up to your preferences. However, I'd recommend to learn the following languages due to the amount of support in contests and certain reasons.

1. **C++**
- C++ is pretty much the standard language for competitive programming. C++ code runs really fast, the Standard Template Library (STL) contains a lot of useful utility functions, and is available in a lot of contest platforms. One downside I would say is that you do need to have some idea with its technicalities, and that you might struggle with implementation because of that.
2. **Python**
- Although Python is not really recommended if you really want to be serious with competitive programming, it is a good starting language for beginners. It is a very simple language to learn, and you can write code really fast with it. And because of that, you can focus more on thinking about your solution. Personally, switching to Python has made me learn much more faster, however I did switch back to C++. One major downside which makes it not viable at all times is its speed. Even if your code has the intended running time for the problem or that the problem has tight input bounds, your code most likely will not pass due to time limit exceeded. In that case, you might be better off using a faster language like C++. You can still find value with it as it is a really good language if you want to quickly write bruteforce solutions or test case generators or any utility scripts. 
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
Similar to programming languages, your choice of text editor/IDE is up to your preferences. Unlike actual development projects, competitive programming is not that demanding for what tools you need. With that, I will mostly be recommending light-weight text editors, but I will also list some IDEs here and there. 

Here are some editors that I have used:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/)
- [Geany](https://www.geany.org/)
- [IDLE](https://www.python.org/downloads/)
- [DevC++](https://www.bloodshed.net/)
- [NetBeans](https://netbeans.apache.org/front/main/index.html)
- [Eclipse](https://eclipseide.org/)
- [Vim](https://www.vim.org/)/[Neovim](https://github.com/neovim/neovim)
- [gVim](https://www.vim.org/)

The following editors are editors that I haven't tried yet, but will include in here to let you explore them and see if it's for you:
- [PyCharm](https://www.jetbrains.com/pycharm/download/)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Code::Blocks](https://www.codeblocks.org/)
- [Kate](https://kate-editor.org/)

I strongly wouldn't recommend using an online editor, as it can make your code prone to leaks. But if you really do need one, there's [CodeChef's Online Compiler](https://www.codechef.com/ide) and [Codeforces' Custom Test](https://codeforces.com/problemset/customtest) (requires Codeforces account).