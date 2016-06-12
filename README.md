# Welcome to AskTanmay!
![Image of Yaktocat](http://www.tanmaybakshi.com/asktanmaylogo5.png)

This repository contains the complete source code for AskTanmay.
### Current Versions
(Beta) 2.0


----------
## What is AskTanmay?
AskTanmay is a Natural Language Question-Answering system (NLQA system), built in Swift, Java, and Python (though the eventual aim is to have it solely in Swift). The goal of AskTanmay is to allow developers to have a foundation to start off of, if they'd like to implement their own NLQA systems, but don't know where to start.


----------
## Build instructions
In order to build AskTanmay, you must have the following dependencies:

 - Python 2.7.10
 - Java 8
 - Xcode 7.3.1 (latest stable Xcode)
 - Mac OS X

***NOTE! Do not build AskTanmay from Xcode! It is not designed for this, though with a bit of modification, can run. While it will build successfully, it won't work in the later stages, as the Python and Java components have not been added. However, you can use Xcode as an IDE, and Build ("CMD+B"), not Run ("CMD+R"), to check your code, and save it.***

Now, the build instructions:

 1. Go into Terminal
 2. Navigate into the directory for the project (the directory
        containing "TanmayQA.xcodeproj")
 3. Run this bash command: `sh buildTQA.sh`
 
Done! This should compile AskTanmay and the Python & Java dependencies.

In order to run the binary, do this:

 1. From that project directory, navigate to "build/Release"
 2. Run AskTanmay with a question: `./TanmayQA "<QUESTION>"`

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">AskTanmay (codename: TanmayQA)</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Tanmay Bakshi</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
