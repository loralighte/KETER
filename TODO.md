> I followed all Markdown syntax properly but I know GitHub is bad at reading Markdown, so everything is in order *just in case GitHub screws Markdown up!*

# Random-People Team for Keter
This is a project we can work on together. Before we release it I want to make a few things clear before we release. A table on how this will be set up is below. Now please note anyone can see this as we aren't a paid group, so we can't make it private but avoid spreading news about it until the HIGH PRIORITY items are done.

> Do these in whatever order:

- [ ] Rewrite compiler in Keter - HIGH PRIORITY - [INFO](#compiler-in-keter)
- [ ] Packaged Binaries for Linux / Windows - HIGH PRIORITY - [INFO](#linux-windows-binaries)
- [ ] Packaged for Package Managers on Linux - HIGH PRIORITY - [INFO](#linux-windows-binaries)
- [ ] Basic Keter Functionality - HIGH PRIORITY - [INFO](#functionality)
- [ ] Basic Documentation - HIGH PRIORITY [INFO](#docs)
- [ ] Libraries - MEDIUM PRIORITY - [INFO](#libs)
- [ ] Packaged Binaries for Mac / FreeBSD - MEDIUM PRIORITY - [INFO](#other-bins)
- [ ] Packaged Binaries for HaikuOS / NetBSD / OpenBSD / Solaris - LOW PRIORITY - [INFO](#other-bins)


> Note the list can change any time

# Basic information
First we will need to decide the original compiler, this isn't a massively important step but it is something we will do. I propose Golang or C++ as they are the languages I think we are all mostly associated with. Even though we will use this language at first, it won't stay the language of choice for the compiler, that will be Keter. More on that later.

Secondly we need to decide on any syntax changes sooner rather than later. Overall I will keep as the final say to changes, unless I am unanimously voted against by all involved.

Thirdly I want to make sure that everyone knows this is a ***compiled*** language, and this is the ***compiler***. This gives us far more control and hopefully speed in the end. 

Fourth item is about the fact we will have 0 dependancies from other languages in the binaries. Standard libs will not count as we will surpass them.

Fifth order of business, and final order, we will have a website for the project BUT it will be a subdomain of my kaix.live domain, unless someone absolutely wants to buy the domain.

## Keter Compiler Rewrite {#compiler-in-keter}
The reason I want the compiler in the language we develop to be in the language we make is for control and survival. It will make life easier as even the most popular programming languages can stop development any time they so wish. Now I mentioned how we will do this before, with a original language to do this. We need a compiled language as we absolutely will need that such binary to work, we can decide that before I start development. As I said in short we make the original compiler in some language, and then we use that language to create a binary. Then we rewrite the original compiler in Keter, try to keep it line-for-line exact, that way the binary will compile the new binary and is how we will continue development. I will not accept keeping the original language forever, and not past release as it gives us a lot of control.

## Linux / Windows Binaries {#linux-windows-binaries}
We will basically get 100% of our userbase this way. Although yes Linux is less popular than Windows, the Linux binaries are not optional and any vote to ignore them will be vetoed. I use Linux, many of my friends use Linux, millions of people use Linux so we need to at least have **some** Linux binaries. Mostly keep it to deb and rpm packages, a general installer, and packages for Snapcraft, Flatpak, Pacman (Arch and KaOS package manager), APT (at least aim for Ubuntu PPAs), and any others you feel like doing. Absolute minimum:
- PACMAN
- FLATPAK
- GENERAL INSTALLER
- PPA / APT
- DEB PACKAGE

## Basic Funcionality {#functionality}
Terminal I/O, file I/O, package requirement scripts, while/for loops, functions, variables, other things you see in a normal programming language. Our inspiration should come from Python, Crystal, and V language. Everything I design is at least semi-inspired by them.

## Documentation {#docs}
This is so people can use our language. The examples folder can be enough for this but prior to release I do want a WIKI on GitHub and a website (which both can come after public release)

## Libraries {#libs}
In short, UI Lib, Regex Lib. These features I 100% want, but do not 100% need. Doing this can also help us decide how to do packages and libraries.

## Other Binaries {#other-bins}
When we start doing other binaries, start with Mac and FreeBSD first, as they are part of the top 4 operating systems (Linux counted as a whole group). They will basically give everyone usabilty. Then focus on NetBSD, OpenBSD, HaikuOS, and Solaris. I want to have all of them with binaries at varying releases, but I do want them. Again, focus on Windows and Linux binaries
