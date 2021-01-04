# WIDC
[W]indows [I]s [D]evelopment [C]apable , is a command line tool for developers who work on windows.
It is a tool like [wget](https://www.gnu.org/software/wget/) and [curl](https://curl.se/) used to download files concurrently from a server or a url . 

There's a story behind its development : 
 - I usually work on my laptop which has windows 10 on it . Often a file is needed to which I know the url but switching between command line for which I use [Cmder](https://cmder.net/) and brwoser window frequently is very time expensive.
  - I sometimes use [Gitpod](https://gitpod.io/) or [Ubuntu](https://ubuntu.com/) / [Kali](https://www.kali.org/) on live boot using a pendrive , which have wget utility available but it always isn't feasable to switch between windows and linux in between of developing and testing.
  - No ports for wget are still there for windows and curl is unbearably slow compared to wget
  - I saw the librery for python named [rich](https://github.com/willmcgugan/rich) (Special thanks to the developer as he did most of the work) which has an example for progress bar , I took it and modified it for downloading files.
  - I compared the speed of wget and WIDC and the latter is slightly faster at downloading. Though the compatibility with servers is better in wget.
 
It has a beautiful and colourful look instead of the ascii progress bar of wget and is quite reliable
