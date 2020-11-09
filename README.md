----
**<h1 align="center">Vigilante-Toolset</h1>**
**<h2 align="center">11/9/2020 update: Installer fixed, Missing files uploaded</h2>**
**<h2 align="center">Will now run with newest versions of Kali and Parrot OS. If you have already installed Vigilante-Toolset please re-read the installation documentation and reinstall the program.</h2>**

----
<br />
<p align="center">  
<a href="https://youtu.be/aD8f5_Y3tsI"><img border="0" alt="DEMO/TUTORIAL" src="https://github.com/MBHudson/Vigilante-Toolset/blob/master/VigilanteVideoThumb.png" width="500" height="300" align="middle">
</a>

<p align="center">
TOR hacking toolkit designed specifically to combat illegal child exploitation websites. !!!Vigilante-Toolset is for EDUCATIONAL PURPOSES ONLY and should NEVER BE USED ILLEGALLY!!!
<br />
<a href="https://www.youtube.com/watch?v=-UL2hAGz8_0"><strong>Proof of Concept/Tutorial Videos »</strong></a>
<br />
<br />
<p align="center">  
<a href="https://github.com/MBHudson/repo">Manual</a>
·
<a href="https://github.com/MBHudosn/repo/issues">Report Bug</a>
·
<a href="https://github.com/MBHudosn/repo/issues">Request Feature</a>
</p>
</p>

>> 
## Table of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Manifesto](#manifesto)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)




## About The Project

~#: Vigilante-Toolset is a project with the goal in stopping the spread of child exploitation through TOR by finding, disabling and reporting child exploitation websites. The Concept works by proxying TOR through a localhost and then using an arsenal of the very same tools you've come to love, along with some super effective modded and original tools, against TOR websites. Every tool is automated and geared towards ease of use along with the project's specific purpose in mind. All attacks can be deployed in 7 key strokes or less. Automation designed so that anyone novice to pro can volunteer and make a difference. Don't let this tool set's easy of use fool you though, as you'll see from our YouTube channel, Vigilante-Toolset takes out TOR sites in real world situations with ease. 

**Tools** **Include** <i>more coming soon</i>

* Automated Proxy/Socket/Tor Handling
* Nmap
* SQLmap
* Nikito
* Full Port Scan added 1/08/2020
* Custom Port Scan  added 1/08/2020
* Custom Proxy  added 1/08/2020
* Uniscan
* Automated Brute Force w/word lists
* XerXes DDoS
* DDoSx4
* IPgeolocate
* Anonymous File Share
* Anonymous E-Mail

### MORE TO COME:

* XSSer
* XSStrike
* Payload Generator/Handler
* Crawler
* ClickJacking
* Metasploit
* BeEF
* Site Cloner
* Phishing/Social Engineering Bundles 
* Apache2/Struts Exploitation Automation
* Bot Net Manager w/ready made UFONet bot networks
* and more...


### Built With

* Tested on  [Kali Linux](https://www.kali.org/)
* Written in [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell))
* Written in [C](https://en.wikipedia.org/wiki/C_(programming_language))
* Written in [Python](https://en.wikipedia.org/wiki/Python_(programming_language))



<!-- GETTING STARTED -->
## Getting Started

!!!MAKE SURE TO INSTALL VIGILANTE-TOOLKIT FOLDER IN YOUR ROOT DIRECTORY!!!

### Prerequisites

* Terminator
* Etherape
* TOR
* TOR Browser
* SoCat
* python3-pip
* Proxychains4
* Docker
* python3

These should be the only things the installer downloads as Kali should have the rest.

### Installation

----
If you are installing from .Zip file rename "Vigilante-Toolset-Master" to just "Vigilante-Toolset" and skip to step two

1. Clone the repo
```sh
git clone https://github.com/MBHudson/Vigilante-Toolset.git
```
2. Change Directory
```sh
cd Vigilante-Toolset
```
3. Give Permissions
```sh
chmod +x ./install.sh
```
4. Edit Installer
```sh
Open "install.sh" and replace ALL "PUT_USER_NAME_HERE" strings to with the username of the session you installed to. ex: kali
```

5. Run Installer
```sh
./install.sh
```
6. Run Vigilante-Toolset
```sh
./Vigilante
```
<!-- USAGE EXAMPLES -->

## Usage

### Run the Script

Make sure you are in the Vigilant-Toolkit directory or
```sh
cd Vigilante-Toolset
```
Run Vigilante-Toolset
```sh
./Vigilante
```

### Main Menu

<a href="https://github.com/MBHudson/Vigilante-Toolset/blob/master/README.md#usage"><img border="0" alt="DEMO/TUTORIAL" src="https://github.com/MBHudson/Vigilante-Toolset/blob/master/mainsmall.png" width="350" height="150" align="middle"> </a>

For each menu a corresponding number, from left to right, 1, 2, 3. You confirm your selection by the ENTER key. Typing, without quotes, "help" will always bring you back to the usage page. Type the letter "q" to quit from main menu.

### Menu "1"

<a href="https://github.com/MBHudson/Vigilante-Toolset/blob/master/README.md#usage"><img border="0" alt="DEMO/TUTORIAL" src="https://github.com/MBHudson/Vigilante-Toolset/blob/master/menu1.png" width="350" height="150" align="middle"> </a>

Option "1" should be your first step, this connects to TOR and sets up the proxy. A seperate terminal will open and prompt you to enter a URL. COPY and PASTE your TARGET URL. without the HTTP:// or / at the end, into the terminal and press ENTER.

Press the letter "t" in any menu to access your TARGET notes. To save notes press CTRL+X (at the same time) followed by the letter "Y" and then ENTER. Press the letter "b" in any menu to go back to the main menu.

### Menu "2"

<a href="https://github.com/MBHudson/Vigilante-Toolset/blob/master/README.md#usage"><img border="0" alt="DEMO/TUTORIAL" src="https://github.com/MBHudson/Vigilante-Toolset/blob/master/menu2.png" width="350" height="150" align="middle"> </a>

Here we have many different tools most I'm sure you are familur with, everything is clearly labeled. For stragity and how to use these tool specificaly see [Manifesto](#Manifesto)

### Menu "3"

<a href="https://github.com/MBHudson/Vigilante-Toolset/blob/master/README.md#usage"><img border="0" alt="DEMO/TUTORIAL" src="https://github.com/MBHudson/Vigilante-Toolset/blob/master/menu3.png" width="350" height="150" align="middle"> </a>

The hope is to gather info leading to the identity of the server's owner; reporting all evidence collected to the proper authorities in that person's jurisdiction thorugh anonymous file sharing/e-mail.


More to come later, sorry

See the [Tutorial Video](https://www.youtube.com/watch?v=-UL2hAGz8_0) for features (and how to use them) More to come soon.



<!-- MANIFESTO-->
## Manifesto

I have found that most of these types of sites are usually ran from an older Windows machine, sometimes a Raspberry Pi3 and not often updated. Minimal in power they are usually very easy to take down with DdoS attacks. I'm  working on the port scanner (update: I have added a port scanner now, customize what ports or do them all + decide what port to proxy 8000) and crawler but for now everything is based off of what would normaly be port 80. Menu 2 Option 4 finds admin logins and other pages that sometimes lead to the identity of who owns the server. Brute forcing is always an option, Option 5 I believe, but I would suggest supplemental word lists. Sometimes you can get lucky when searching through pages found from the directory scan and happen upon a SQL server. In such a case there are instructions within all terminal prompts guiding you as to what information is needed. 

See the [Tutorial Video](https://www.youtube.com/watch?v=-UL2hAGz8_0) for features (and how to use them) More to come soon.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

To be honest I have no idea how this whole licensing part works. If there is any issue please [E-mail](VgilanteToolset@gmail.com) me and I'm sure we can figure something out. Thank you



<!-- CONTACT -->
## Contact

* [E-mail](VigilanteToolset@gmail.com) VigilanteToolset@gmail.com

* [Facebook](Https://fb.me/VigilanteToolset) Https://fb.me/VigilanteToolset

* [Twitter](Https://www.twitter.com/vigilantetools/) Https://www.twitter.com/vigilantetools/


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgments

* CyberXCodder
* [@xer0dayz](http://xerosecurity.com)
* [Miroslav Stampar](http://sqlmap.org/)
* and many more to be added later. Until then creatits may be found spread out within the source code.





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
