# zeioth-meta
A futile attempt to have a resume of all my projects on a single page. 



## Content I should write here?


* Pipy packages
* Npm packages
* Startups y subproyectos de estas. Experiencia y roles.
* Also, count how many issues and PR you have reported in total.

## TODO:

* ✅ Copy here the same of all your repositories. 
* Delete what is not relevant. 
* Add descriptions and photos.

## Startup projects

Projects listed here were developed for startups i've been cofounder of. 

**Jinn.es**: The interactive traveling guide. National alternative to foursquare. Winner startup of the 1º edition of Think Big Telefonica Spain. Mentorized by the Banesto foundation (Yuzz progam). My role on this company was both CTO and Full Stack Programmer. I managed a team of 2 programmers and 2 designers, as well as the project architecture.

* Web: The main purpose of the site was to give to the user information about the top places to visit around in the city. We achieved this bu showing a list of points of interest in the specified city (web version). It also counted with a search funtionality. 
* Custom admin panel: We had different kinds of ures: "Writer", "admins" and "superusers", where an user could add points of interest, an admin could approve or reject them, and the superuser could add/delete any of the other roles.
* Login system: I implemented from scrath both fronentend and backend of a complete login system, including email system, password recovery, error control, interactive password strenght check, and login/registraion through Google/Facebook. All this proved to be a big technical challenge that took many months, but it was ultimately achieved.
* Product design: In the initial stages of the project, I designed 5 different corporative identities. Later on, I created mockups for every screen of the page. The smartphone app, and the logo of Jinn.es were designed by a people wehired.
* Database: I designed a relation postgresql+postgis database capable of managing geopositional data at big data level.
* Native Android/IOS application: While I didn't code the applications themselves, I coded the REST services that allowed the apps to communicate with the database using Django Rest Framework.
* POST-MORTEM: This was my first project acting as CTO/Softwate Architect. It took us 1.5 years to complete the project. A titanic task for such an small team! It took a big toll on our health, but the satisfaction of having our product on the market made it worth it. Comertially was not a success, since we lacked the necessary knowledge on marketing, but we were satisfied, and part ways happily with the knowledge we obtained.

**GameMetrics.com**: Analytics for game developers. Website that through the use of web crawling, statistics, and our own internal API, provided crucial market data to videogame developers. Incubated in ImpactHub Bucharest (Romania) and Polo Digital (Málaga). During the first years of the project I acted once more as CTO/Architect. On the second half on the project I stepped up as CEO.

* Generic Scraper: C# solution that consist in a set of cusomizable crawlers and scrapers written from scratch. It provides a config file that allow to configure the HTML strings to crawl/scrap. This makes it a generic scraper that can easily be adapted to any website to extract information. I also designed and implemented both, the MongoDB database, and the class that perform async operations to the database, with full error control, and retry management. The scrapers have the ability to run multi thread and multi process in perfect syncrony. It can also seamlessly recover in case internet conection is loss. It uses both curl and selenium, to allow scraping even pages that check il the user is human. We used this in-house tools to extract all the (legally available) information from GooglePlay, IOS, and other sources, to compute this data using data science and generate relevant predictive market data for our users. I currently own and manage the rights of this softwate. This project took a full year to develop.
* Demo: I coded an incomplete internal version of the project, to show to investors. It also aided me to convince the other founders. Architecture, backend, frontend and mongodb database were designed and progammed by me.
* Corporative documents: I was responsable for redacting and maintaining the business documents. Among others, the business plan (70 pages, coached by Alba Escobar Yus, from the university of Zaragoza), finantial plan, investor deck, one pager, pitching, value reseach, and negotiation with investors, for which I researched, redacted, and classified a list of the top 300 business angels and business fonds of Spain, as for this project we had the need of external growth. During our stance in Polo Digital we have the chance to speas with hundreds of game developers to further validate our hypotesis.
* Interactive product design: For this project, You can check it [here](https://marvelapp.com/prototype/8g31ga1/screen/56679718).

**BRAND PROTECTED BY CONFIDENCIALITY - Insurance broking company**
I accepted this project in order to finance the development of GameMetrics. The requirements of this project were to develop a website that during the registration process, ask for certain data to the user, to later use it to offer him the best available insurance companies and offers for his particular case. The project was connected to a national database widely used by broking companies, accessed through SOAP. This project was particulary challenging, due to multiple requirements changes during development that considerable changed the foundations of the project. The development took 6 months, using Django and AngularJS. I only designed the architecture, database, and coded backend and frontend, as a good part of the product design was provided to me. The rest of the team kept working on GameMetrics meanwhile.

## International companies I've worked on

**[PackageMedia (Finland)](https://www.packagemedia.com/en/)**: I was hired to code a campaign for the finnish food brand saarioinen. The purpose was to create a landing page where people see a box saarioinen, and a text box under it. As the user writes the message, he sees it appear over the box of food. Once he submit the message, and its moderated by the team, this messages were phisically printer in the boxes of food. The concept was like "A message in a bottle", similar to cocacola where you can find your name in the bottle, but using actual messages written by our users. I mostly coded the frontend for this project using Vue.js. The challenging part of this project was to make it responsive, as the visual elements were very artistic.

**[EpicElite (Dubai)](https://epicelite.com/home)**: A service for musicians to upload their musid to multiple services at the same time, negotiate their copyright, manage their workflow, and more. I was hired as a full stack developer, writing the website in GraphQL, mostly frontend javascript map reduces and backend business logic. For this project we used React, having to migrate some parts from AngularJS too. About 50% of the project, I was also used for other purposes, writing automatized tests using cypress. I also aided to write the devops scripts necessary to migrate and refactor the legacy database into a sanitized pseudo-normalized new one. And other devops scripts for deployment during the transition to kubernetes.

## Remarkable projects


* [zeioth-qmk](https://github.com/Zeioth/zeioth-qmk): I coded this C driver for a wired wireless keyboard I built. I use it for coding when I'm not at home with my pocket computer. [More info](https://github.com/Zeioth/zeioth-keyboard-firmware).
* [zeioth-zmk](https://github.com/Zeioth/zeioth-zmk): I coded this C driver for a bluetooth wireless keyboard I built. I use it for coding when I'm not at home with my pocket computer. Because this version is wireless, it uses a different technology, so this is a new driver I wrote from scratch. [More info](https://github.com/Zeioth/zeioth-keyboard-firmware).
* [wofi-emoji](https://github.com/Zeioth/wofi-emoji): Emoji selector for Linux based on WOfi. The original author abandoned the project, so I continued it and fixed some bugs.![screenshot_2023-02-08_21-48-40_829722436](https://user-images.githubusercontent.com/3357792/217647818-1f710289-6032-4d3e-be83-4020e86fcf66.png)
* [wofi-calc](https://github.com/Zeioth/wofi-calc): Linux calculator with a list of previous operations. Selecting one will copy it to the clipboard. Available on GitHub and ArchLinux AUR.
![screenshot_2023-02-11_21-31-36_246220057](https://user-images.githubusercontent.com/3357792/218279937-edab1c36-053c-4147-a4f4-51053b557645.png)
* [manjaro-sway](https://github.com/manjaro-sway/manjaro-sway): [Credited developer](https://github.com/manjaro-sway/manjaro-sway#contributors-) of the Linux Distribution 'Manjaro Sway'. I contributed to the desktop taskbar widgets, solving, and reporting bugs.
![Manjaro sway](https://user-images.githubusercontent.com/3357792/218281847-18177729-04ba-4054-8fb7-281ed90d6040.png)
* [adrian-innotopic-test](https://github.com/Zeioth/adrian-innotopic-test) Real time coding skill test I had to pass in order to be hired by a previous company. Without any previous knowledge about the technology, I had 2h (extended to 4h) to setup a graphql/apollo project. The purpose of the test was to evaluate my decesion making and performance under stress.


## Personal/fun projects
* [Brros](https://github.com/Zeioth/BrrrOS): My personal non distributable linux dirtribution, for personal usage. It's an installer that you run in a clean arch linux environment. It will install hundreds of packages and custom configurations in an automated way. It allows me to reinstall my system in a matter of minutes.
![screenshot_2023-02-11_21-49-07_340866431](https://user-images.githubusercontent.com/3357792/218280583-88c8e871-f61d-4292-98b3-a3dd1ea0c317.png)
* Automated cloud backups: Bash script that encrypt and upload all my (safe) personal files to the cloud through a programmed task. It allow me to recover from any potential problem in my computer in a matter of minutes. I haven't made this one public, because it is 100% custom.
![screenshot_2023-02-11_21-38-23_163064731](https://user-images.githubusercontent.com/3357792/218280171-8de5fe5b-9e67-4d28-aa5c-2482cb917a6b.png)
* [i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) I wrote a volume widget for [I3](https://github.com/i3/i3) desktop environment taskbar, compatible with [pipewire](https://pipewire.org/). It is used daily by thousands of people (see screenshot of the prev. entry).


## Bug reports
* [Wob](https://github.com/francma/wob): Volume bar for Linux. 
![screenshot_2023-02-11_21-28-34_120481289](https://user-images.githubusercontent.com/3357792/218279822-cc3c44ce-4302-4ca5-b4b5-003f937a4214.png)
* [vimium-c](https://github.com/gdh1995/vimium-c): Browser extension that add VIM keybindings. I reported a critical bug preventing some pages to be opened correctly. And a few minor ones.
* [MangoHud](https://github.com/flightlessmango/MangoHud): An overlay that shows diverse hardware information. Recently adopted by Valve's SteamDeck. Bug reports.






* [django-email-blacklist](https://github.com/Zeioth/django-email-blacklist): I wrote this python module that can be installed using pip. It is a backend class that allow you to compare an introduced email against a list of blacklisted providers, you can write. In pactice it prevent users from register in the your website using an internet fake email generator.
* [rofi-shortcuts](https://github.com/Zeioth/rofi-shortcuts): I coded this project to help me memorize the 300+ keyboard shortcuts I use. To my surprise, the community loved this project. Likely, because it is very easy to customize.
![screenshot_2023-02-11_23-55-27_650860851](https://user-images.githubusercontent.com/3357792/218284556-1a75f16b-8153-4fd8-a04e-87f850a2b379.png)
* [rofi-zeal](https://github.com/Zeioth/rofi-zeal): An assistant for programmers, where you can insert a class, and receive instant documentation about it. It work with all major languages. This project was also very well received.
![zeal](https://user-images.githubusercontent.com/3357792/218284504-0efe76de-ba0e-4cd8-a8cf-be3e86477b7d.png)
* [atom-visual-studio-code-ui](https://github.com/Zeioth/atom-visual-studio-code-ui): I designed and coded a visual theme for the Atom text editor, based on visual studio code. It was challenging to achieve a high quality result because the GUI of both editors is esentially quite different.
* [atom-visual-studio-code-light-ui](https://github.com/Zeioth/atom-visual-studio-code-light-ui): Due to its popularity I released a second version, in light colors.
* [optimus-manager-qt](https://github.com/Askannz/optimus-manager): This small utility is used to chose and configure graphic cards on laptops where you have more than one in an easy way. I asissted the main developer during the initial phases of testing, reported bugs, and translated/added the spanish language.
* [dxvk-cache-pool](https://github.com/rcpoison/dxvk-cache-pool): This is a procursor of the system Valve currently uses for Steam to distribute shader cache files. It lacked a way to validate a shader cache file in a safe way, so a system where users could vote was implemented via TUI. It was finally discontinued, as Valve took it as reference to design their own system. I asissted the main developer during the initial phases of testing, and reported bugs.
* [GameMetrics landing](https://zeioth.github.io/gamemetrics-landing-2/): This market research was performed in order to find the top valued features by our users, before spending more oney in further developing the product. Three Landing pages were associated with 3 different digital marketing campaigns. By judging the number of leads and GoogleAnalytics metrics we were able to determine in which order we should develop our features. This strategy, was tought to us by the mentors of ImpactHub bucharest, advised by the CEO of [GeenHorse](https://www.greenhorsegames.com/) studios, and further reinforced with the statictical methodologies teached in the university of Bucharest (again, through our mentors). One of tests [can still be visited](https://zeioth.github.io/gamemetrics-landing-2/).
* [XFCE-Wacom-Settings ](https://github.com/Zeioth/XFCE-Wacom-Settings): I coded this package to make possible installing Gnome's WACOM control panel in the XFCE desktop environment. It worked for many years until Gnome changed its architecture, further integrating all its components into mutter, so we had to drop the support. To this day, XFCE haven't had an alternative to this project.
![wac](https://user-images.githubusercontent.com/3357792/218285332-1a3fef99-5289-447d-8f27-bec1544f2b63.png)
* [TwitterFollowBot](https://github.com/rhiever/TwitterFollowBot): I personally automated this twitter bot to act as a worked of our startup in order to get followXFollow traffic based on certain user profile and criteria. The strategy proved to be successful, and our community manager regulary maintained [our community of 2500+ followers](https://twitter.com/game_metrics).
* [Doxigen-bootstrapped](https://github.com/Velron/doxygen-bootstrapped): A visual theme for the documentation generator doxigen based on bootstrap. I coded multiple bugfixes and improvemens, that ultimately allowed our team to read and generate documentation more effectively.
* [Django-ses](https://github.com/Zeioth/django-ses): This is a Django helper for amazon SES email service. The project was temporary abandoned so I coded the support for Python 3+.
* [Git-cola](https://github.com/git-cola/git-cola): I proposed a couple improvemens. The developers agreed and implemented them in less than 24h, so I contributed by improving the spanish translation of the project, fixing new features lacking a proper translation.
* [NoRecaptcha-python3](https://github.com/Zeioth/norecaptcha-python3): I coded this wrapper that allow to use the first version of Google NoRecaptcha on python3+.
* [angular-no-captcha](https://github.com/Zeioth/angular-no-captcha): I also implemented this Angular directive to use Google NoRecaptcha on the frontend.
* [angular-satellizer](https://github.com/Zeioth/satellizer): I implemented this frontend collection of API calls as base for our registration system. It offered an boilerplate skeletong to the frontend registration system of Jinn.es
* [Djoser](https://github.com/sunscrapers/djoser) I took this backend registration API reference and extended it with multiple features like custom registration emai, user registration using Facebook/Google, and many, many custom operations specific to our system in Jinn.es
* Google PlayStoreCrawler (Closed source)
* AppleStoreCrawler (Closed souce)
* [password-meter-tutorial](https://github.com/Zeioth/password-meter-tutorial)

## Others

* [Lutris](https://github.com/lutris): Website/application that allows a player to install any windows videogame on linux in a single click. In the past I've written a good amount of game installers. I currently give support to the community, report bugs, and help closing redundant issues.


![screenshot_2023-02-11_21-55-27_593015469](https://user-images.githubusercontent.com/3357792/218280814-6e2f556c-b3b1-409c-a51c-c50e2abd0fd2.png)

## About third party data protection
Please, understand that out of respect to my contractors, I can't disclose detailed information about projects I've woked on for third party companies. In most cases this include screenshots, and/or implementation details.
