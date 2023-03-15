# zeioth-meta
In this page I give more detain about some of the projects I've participated on. Mostly personal, and FOSS projects, in order to respect confidenciality.

## Startup projects

Projects listed here were developed for startups I've been cofounder of. 

**Jinn.es**: The interactive traveling guide. National alternative to foursquare. Winner startup of the 1º edition of Think Big Telefonica Spain. Mentorized by the Banesto foundation (Yuzz progam). My role on this company was both CTO and Full Stack Programmer. I managed a team of 2 programmers and 2 designers, as well as the project architecture.

* Web: The main purpose of the site was to give to the user information about the top places to visit around in the city. We achieved this bu showing a list of points of interest in the specified city (web version). It also counted with a search funtionality. 
* Custom admin panel: We had different kinds of ures: "Writer", "admins" and "superusers", where an user could add points of interest, an admin could approve or reject them, and the superuser could add/delete any of the other roles.
* Login system: I implemented from scrath both fronentend and backend of a complete login system, including email system, password recovery, error control, interactive password strenght check, and login/registraion through Google/Facebook. All this proved to be a big technical challenge that took many months, but it was ultimately achieved.
* Product design: In the initial stages of the project, I designed 5 different corporative identities. Later on, I created mockups for every screen of the page. The smartphone app, and the logo of Jinn.es were designed by a people wehired.
* Database: I designed a relation postgresql+postgis database capable of managing geopositional data at big data level.
* Native Android/IOS application: While I didn't code the applications themselves, I coded the REST services that allowed the apps to communicate with the database using Django Rest Framework.
* POST-MORTEM: This was my first project acting as CTO/Softwate Architect. It took us 1.5 years to complete the project. A titanic task for such an small team! It took a big toll on our health, but the satisfaction of having our product on the market made it worth it. Comertially was not a success, since we lacked the necessary knowledge on marketing, but we were satisfied, and part ways happily with the knowledge we obtained.

![jinn_clipdrop-enhance](https://user-images.githubusercontent.com/3357792/220610739-57580506-af7e-4bd0-b97c-2cd91d35d3f8.jpg)


**GameMetrics.com**: Analytics for game developers. Website that through the use of web crawling, statistics, and our own internal API, provided crucial market data to videogame developers. Incubated in ImpactHub Bucharest (Romania) and Polo Digital (Málaga). During the first years of the project I acted once more as CTO/Architect. On the second half on the project I stepped up as CEO.

* [GameMetrics landing](https://zeioth.github.io/gamemetrics-landing-2/): This market research was performed in order to find the top valued features by our users, before spending more oney in further developing the product. Three Landing pages were associated with 3 different digital marketing campaigns. By judging the number of leads and GoogleAnalytics metrics we were able to determine in which order we should develop our features. This strategy, was tought to us by the mentors of ImpactHub bucharest, advised by the CEO of [GeenHorse](https://www.greenhorsegames.com/) studios, and further reinforced with the statictical methodologies teached in the university of Bucharest (again, through our mentors). One of tests [can still be visited](https://zeioth.github.io/gamemetrics-landing-2/).
* Demo: I coded an minimum viable version of the project, to show to investors. It also aided me to convince the other founders to join. Architecture, backend, frontend and mongodb database were designed and progammed by me.
* Generic Scraper: C# solution that consist in a set of cusomizable crawlers and scrapers written from scratch. It provides a config file that allow to configure the HTML strings to crawl/scrap. This makes it a generic scraper that can easily be adapted to any website to extract information. I also designed and implemented both, the MongoDB database, and the class that perform async operations to the database, with full error control, and retry management. The scrapers have the ability to run multi thread and multi process in perfect syncrony. It can also seamlessly recover in case internet conection is loss. It uses both curl and selenium, to allow scraping even pages that check il the user is human. We used this in-house tools to extract all the (legally available) information from GooglePlay, IOS, and other sources, to compute this data using data science and generate relevant predictive market data for our users. I currently own and manage the rights of this softwate. This project took a full year to develop.
* Corporative documents: I was responsable for redacting and maintaining the business documents. Among others, the business plan (70 pages, coached by Alba Escobar Yus, from the university of Zaragoza), finantial plan, investor deck, one pager, pitching, value reseach, and negotiation with investors, for which I researched, redacted, and classified a list of the top 300 business angels and business fonds of Spain, as for this project we had the need of external growth. During our stance in Polo Digital we have the chance to speas with hundreds of game developers to further validate our hypotesis.
* DevOps department: Because Kubernetes didn't exist in this point yet, I coded my own kubernetes by using the Amazon AWS API (BOTO). It consisted in a TUI (text user interface) that gave us the ability to deploy automatically at will (continuous delivery). It also offered options to scale the site (spawning more instances/cache) and the database (creating more mongos/balancers for the mongodb cluster). This project was 100% functional and worked in production.
* Prodect design: I was the main product design/product owner of this project. You can check an interactive presentation [here](https://marvelapp.com/prototype/8g31ga1/screen/56679718).
* Team management: I was the scrumm master of this project, as well as responsible for reviewing the performance metrics, the consecution of goals, and the proposal of alternatives to achieve lean, meaningful results, aligned with our objetives and resources.
![screenshot_2023-02-22_12-03-49_733656040](https://user-images.githubusercontent.com/3357792/220602244-1adbdc99-4372-45a3-9519-97284799fe21.png)



**Experimental on demand ecommerces provider platform**: I created a site where an user can create an ecommerce in one click (similar to shopify). 
* **Landing page**: Nothing special here, but I decigned it and coded it.
* **User backend**: Ecommerce where an user can buy an ecommerce (the ecommerce itself was magento too).
* **Kubernetes cluster for Magento ecommerce**: I coded a kubernetes cluster to manage magento ecommerces. With ability to scale Redis cache and Varnish instances for maximum performance.
* **Post-mortem**: Most part of the project was ready, but I was lacking the money and resources necessary to kickstart a business of such complexity, so I came back to work on international companies.

## International companies I've worked on

**Insurance broking company** (Some aspects protected by confidencialify): 
A personalized insurance comparator. I accepted this project in order to raise funds the development of out startup (GameMetrics). The requirements of this project were to develop a website that, during the registration process, ask for certain data to the user, to later use it to offer him the best available insurance companies and offers for his particular case. The project was connected to a national database widely used by broking companies, accessed through SOAP. This project was particulary challenging, due to multiple requirements changes during development that considerable changed the foundations of the project. The development took 6 months, using Django and AngularJS. I only designed the architecture, database, and coded backend and frontend, as a most part of the product design was provided to me by the contractor. The rest of the team kept working on GameMetrics meanwhile.

**[PackageMedia (Finland)](https://www.packagemedia.com/en/)**: I was hired to code a campaign for the finnish food brand saarioinen. The purpose was to create a landing page where people see a box saarioinen, and a text box under it. As the user writes the message, he sees it appear over the box of food. Once he submit the message, and its moderated by the team, this messages were phisically printer in the boxes of food. The concept was like "A message in a bottle", similar to cocacola where you can find your name in the bottle, but using actual messages written by our users. I mostly coded the frontend for this project using Vue.js. The challenging part of this project was to make it responsive, as the visual elements were very artistic.

![sair](https://user-images.githubusercontent.com/3357792/220611367-3bd54b4c-b7d2-471e-93bc-c75f0a94a37f.png)


**[EpicElite (Dubai)](https://epicelite.com/home)**: A service for musicians to upload their musid to multiple services at the same time, negotiate their copyright, manage their workflow, and more. I was hired as a full stack developer, writing the website in GraphQL, mostly frontend javascript map reduces and backend business logic. For this project we used React, having to migrate some parts from AngularJS too. About 50% of the project, I was also used for other purposes, writing automatized tests using cypress. I also aided to write the devops scripts necessary to migrate and refactor the legacy database into a sanitized pseudo-normalized new one. And other devops scripts for deployment during the transition to kubernetes.

![ep](https://user-images.githubusercontent.com/3357792/220613128-b3aa9181-3909-4d10-846f-2f01f1319125.jpeg)


## Remarkable projects


* [zeioth-qmk](https://github.com/Zeioth/zeioth-qmk): I coded this C driver for a wired wireless keyboard I built. I use it for coding when I'm not at home with my pocket computer. [More info](https://github.com/Zeioth/zeioth-keyboard-firmware).
![corne1](https://user-images.githubusercontent.com/3357792/220613737-95f568ae-be30-4fad-b619-03b3293706e9.jpeg)
* [zeioth-zmk](https://github.com/Zeioth/zeioth-zmk): I coded this C driver for a bluetooth wireless keyboard I built. I use it for coding when I'm not at home with my pocket computer. Because this version is wireless, it uses a different technology, so this is a new driver I wrote from scratch. [More info](https://github.com/Zeioth/zeioth-keyboard-firmware).
* [manjaro-sway](https://github.com/manjaro-sway/manjaro-sway): [Credited developer](https://github.com/manjaro-sway/manjaro-sway#contributors-) of the Linux Distribution 'Manjaro Sway'. I coded some of the desktop taskbar widgets, solving, and reporting bugs.
![Manjaro sway](https://user-images.githubusercontent.com/3357792/218281847-18177729-04ba-4054-8fb7-281ed90d6040.png)
![corne2](https://user-images.githubusercontent.com/3357792/220614115-800b2f30-2181-4f6f-abfe-ec5605518fdc.jpg)
* [wofi-emoji](https://github.com/Zeioth/wofi-emoji): Emoji selector for Linux based on Wofi. The original author abandoned the project, so I continued it and fixed some bugs.![screenshot_2023-02-08_21-48-40_829722436](https://user-images.githubusercontent.com/3357792/217647818-1f710289-6032-4d3e-be83-4020e86fcf66.png)
* [wofi-calc](https://github.com/Zeioth/wofi-calc): Linux calculator with a list of previous operations. Selecting one will copy it to the clipboard. Developer and maintainer. Available on GitHub and ArchLinux AUR.
![screenshot_2023-02-11_21-31-36_246220057](https://user-images.githubusercontent.com/3357792/218279937-edab1c36-053c-4147-a4f4-51053b557645.png)
* [adrian-innotopic-test](https://github.com/Zeioth/adrian-innotopic-test) Real time coding skill test I had to pass in order to be hired by a previous company. Without any previous knowledge about the technology, I had 2h (extended to 4h) to setup a graphql/apollo project. The purpose of the test was to evaluate my decesion making and performance under stress.


## Personal/fun projects
* [Brros](https://github.com/Zeioth/BrrrOS): My personal non-distributable Linux distribution, for professional usage. It's an installer that you run in a clean arch linux environment. It will install hundreds of packages and custom configurations in an automated way. It allows me to reinstall my system in a matter of minutes.
![screenshot_2023-02-11_21-49-07_340866431](https://user-images.githubusercontent.com/3357792/218280583-88c8e871-f61d-4292-98b3-a3dd1ea0c317.png)
* Automated cloud backups: Bash script that encrypt and upload all my (safe) personal files to the cloud through a programmed task. It allow me to recover from any potential problem in my computer in a matter of minutes. I haven't made this one public, in order to do not reveal where my files are located, for security.
![screenshot_2023-02-11_21-38-23_163064731](https://user-images.githubusercontent.com/3357792/218280171-8de5fe5b-9e67-4d28-aa5c-2482cb917a6b.png)
* [i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) I wrote a volume widget for [I3](https://github.com/i3/i3) desktop environment taskbar, compatible with [pipewire](https://pipewire.org/). It is used daily by thousands of people (see screenshot of the prev. entry).
* [django-email-blacklist](https://github.com/Zeioth/django-email-blacklist): I wrote this python module that can be installed using pip. It is a backend class that allow you to compare an introduced email against a list of blacklisted providers, you can personalize. In pactice it prevent users from register in the your website using a fake email generator.
* [rofi-shortcuts](https://github.com/Zeioth/rofi-shortcuts): I coded this project to help me memorize the 300+ keyboard shortcuts I use. To my surprise, the community loved this project. Likely, because it is very easy to customize.
![screenshot_2023-02-11_23-55-27_650860851](https://user-images.githubusercontent.com/3357792/218284556-1a75f16b-8153-4fd8-a04e-87f850a2b379.png)
* [rofi-zeal](https://github.com/Zeioth/rofi-zeal): An assistant for programmers, where you can insert a class, and receive instant documentation about it. It work with all major languages. This project was also very well received.
![zeal](https://user-images.githubusercontent.com/3357792/218284504-0efe76de-ba0e-4cd8-a8cf-be3e86477b7d.png)
* [atom-visual-studio-code-ui](https://github.com/Zeioth/atom-visual-studio-code-ui): I designed and coded a visual theme for the Atom text editor, based on visual studio code. It was challenging to achieve a high quality result because the GUI of both editors is esentially quite different.
![screenshot_2023-03-15_20-15-37_956903150](https://user-images.githubusercontent.com/3357792/225419014-7a86ee45-77b8-43c6-958c-9892dd5cebab.png)
* [atom-visual-studio-code-light-ui](https://github.com/Zeioth/atom-visual-studio-code-light-ui): Due to its popularity I released a second version, in light colors.
![screenshot_2023-03-15_20-16-27_195888964](https://user-images.githubusercontent.com/3357792/225419056-e77ad1b0-c6ee-404f-aa8b-2aecca691736.png)
* [optimus-manager-qt](https://github.com/Askannz/optimus-manager): This small utility is used to chose and configure graphic cards on laptops where you have more than one in an easy way. I asissted the main developer during the initial phases of testing, reported bugs, and translated/added the spanish language.
![qt](https://user-images.githubusercontent.com/3357792/225419217-320035e0-a3b2-41ce-a9b0-4f3569aef463.png)
* [dxvk-cache-pool](https://github.com/rcpoison/dxvk-cache-pool): This is a procursor of the system Valve currently uses for Steam to distribute shader cache files. It lacked a way to validate a shader cache file in a safe way, so a system where users could vote was implemented via TUI. It was finally discontinued, as Valve took it as reference to design their own system. I asissted the main developer during the initial phases of testing, and reported bugs.
![land1](https://user-images.githubusercontent.com/3357792/220615621-ff2c4450-1c0c-4c45-9f92-c3a0f52dbad4.png)
* [XFCE-Wacom-Settings ](https://github.com/Zeioth/XFCE-Wacom-Settings): I coded this package to make possible installing Gnome's WACOM control panel in the XFCE desktop environment. It worked for many years until Gnome changed its architecture, further integrating all its components into mutter, so we had to drop the support. To this day, XFCE haven't had an alternative to this project.
![wac](https://user-images.githubusercontent.com/3357792/218285332-1a3fef99-5289-447d-8f27-bec1544f2b63.png)
* [TwitterFollowBot](https://github.com/rhiever/TwitterFollowBot): I personally automated this twitter bot to act as a worker of our startup in order to get followXFollow traffic based on certain user profile and criteria. The strategy proved to be successful, and our community manager regulary maintained [our community of 2500+ followers](https://twitter.com/game_metrics).
* [Doxigen-bootstrapped](https://github.com/Velron/doxygen-bootstrapped): A visual theme for the documentation generator doxigen based on bootstrap. I coded multiple bugfixes and improvemens, that ultimately allowed our team to read and generate documentation more effectively.
* [Django-ses](https://github.com/Zeioth/django-ses): This is a Django helper for amazon SES email service. The project was temporary abandoned so I coded the support for Python 3+.
* [Git-cola](https://github.com/git-cola/git-cola): I proposed a couple improvemens. The developers agreed and implemented them in less than 24h, so I contributed by improving the spanish translation of the project, fixing new features lacking a proper translation.
* [NoRecaptcha-python3](https://github.com/Zeioth/norecaptcha-python3): I coded this wrapper that allow to use the first version of Google NoRecaptcha on python3+.
* [angular-no-captcha](https://github.com/Zeioth/angular-no-captcha): I implemented this Angular directive to use Google NoRecaptcha on the frontend.
* [angular-satellizer](https://github.com/Zeioth/satellizer): I implemented this frontend collection of API calls as base for our registration system. It offered a boilerplate skeleton to the frontend registration system of Jinn.es
* [Djoser](https://github.com/sunscrapers/djoser): I took this backend registration API reference and extended it with multiple features like custom registration email, user registration using Facebook/Google, and many, many custom operations specific to our system in Jinn.es
* [password-meter-tutorial](https://github.com/Zeioth/password-meter-tutorial): I implemented both the backend and the frontend of an interactive password strenght bar in the registration form to guide our users in thinking an strong password.
* [hls-to-rgb-hightweight](https://www.npmjs.com/package/hsl-to-rgb-lightweight) I coded this javascript library to define colors in HLS format, in order to create the color gradings we used for the data charts in GameMetrics. This was the first library out there providing this feature following the ES6+ standar.
* Linux-command-gpt: I maintain the AUR repository of this chatGPT client for the linux terminal. One can ask anything to the terminal in human language, and accept or re-generate the actions to perform. For example: "List the name of every .txt file in this directory and print the last 3 lines of each."
![screenshot_2023-03-15_21-10-57_521507280](https://user-images.githubusercontent.com/3357792/225430955-b3782bf6-f757-425e-96af-de281df3097b.png)

## Bug reports
Through the years I've opened around 1000 issues in github. Some recent ones are:

* [Wob](https://github.com/francma/wob): Volume bar for Linux. 
![screenshot_2023-02-11_21-28-34_120481289](https://user-images.githubusercontent.com/3357792/218279822-cc3c44ce-4302-4ca5-b4b5-003f937a4214.png)
* [vimium-c](https://github.com/gdh1995/vimium-c): Browser extension that add VIM keybindings. I reported a critical bug preventing some pages to be opened correctly. And a few minor ones.
* [MangoHud](https://github.com/flightlessmango/MangoHud): An overlay that shows diverse hardware information. Recently adopted by Valve's SteamDeck. Bug reports.


## Others

* [Lutris](https://github.com/lutris): Website/application that allows a player to install any windows videogame on linux in a single click. In the past I've written a good amount of game installers. I currently give support to the community, report bugs, and help closing redundant issues.

![screenshot_2023-02-11_21-55-27_593015469](https://user-images.githubusercontent.com/3357792/218280814-6e2f556c-b3b1-409c-a51c-c50e2abd0fd2.png)

* **Solar ebike**: I built this solar energy system to fuel my ebike in a 100% green way. I also built the ebike myself from scratch. It has a 1000W induction motor, and an autonomy of 10Ah.
![ebike](https://user-images.githubusercontent.com/3357792/220614680-1f072a14-04fc-4f23-83cd-5bc8f7e861d4.jpg)

## Videogame development

* **Super commando fighter**: Along with the 3D artist who created the art of most boxes fox AMD graphic cards in the 2005-2010 period, I coded the system for a 2.5D platformer shooter, similar to "contra". Featuring a power up system. I coded this game while studying coding, so we never completed or released the game, but I learned a lot from it. I used Unity/C#.
* **Destruction in wonderland**: After my first startup failed (jinn.es) I spent 6 months in creating another videogame in Unity/C#. This time I did both the game system, and the art using vectors (inkscape). I also designed 52 different levels for it on paper, of which I only realized one for the technical demo. The concept was similar to "Lemings", where characters move by themselves, and the objective of the player was to guide them to the exit by using explosive weapons, with game mechanics similar to the videogame "worms". The visual aspect was influenced by a mix of "World of goo" and "Kirby". The biggest challenge of this project was to code an dynamic 2D vector system, to draw a curve on screen that transform as the user drag the cursor to assist him during aiming, as at that time unity didn't include such feature. So I kinda had to make the library.
* **Last train**: I coded this project for the VI edition of "Malaga Jam", a competition where people create a game in 72h, with a team of 5 people. My main goal was analyst, but I also coded the main mechanics, as the rest of the team focused on plot, art, and game design. We received a nomination to "Most original game".

## Remarkable participation in events

* **Juzz Banesto**: During my first startup (jinn.es) we attended to this progam, to learn the basics of how to grow a business.
* **Think Big Telefónica**: Also during my first startup (jinn.es) we participated in the first edition of this national contest. I personally gave a speech for an aucience of 100+ potential investors in the main headquarters of telefonica (Madrid).
* **AngularJS Málaga**: After participating in this event in the university of Málaga, the organizers invited me to a hackathlon where we discussed about our startups and projects. This ended in future colaborations and good relationships.
* **Startup weekend**: We attended this event for recluiting developers.
* **Malaga Jam VI**: We attended this event for recluiting developers.
* **EOI Europe**: With our second startup (GameMetrics) we were accepted in this european program for startups of great potential. I were assigned to ImpactHub Bucharest, where I traveled in representation of the company to pitch our project, and receive advanced mentorship in business, product proposition, strategy, and marketing, along with other european startups of similar reach.
* **Startarium**: During EOI Europe I had the oportunity to attend as part of the public to "Startarium", the biggest startups competition of Romania.
* **Digital Polo**: We were incubated for 1.5 years here attending to all kind of events for startups and businesses.
* **EOI Málaga**: We were incubated for 6 months, along with dozens of videogame studios and startups. I received very intensive business related mentorship, and dedicated most of my time here to corporative documents, proposals, and negotiations with investors.
* **500+ language exchanges**: It's worth mentioning, that I've been attending to 1-2 language exchanges per week during the past 10 years, achieving english at native level.

There are others relevant events, but I consider this is enough.

## About third party data protection
Please, understand that out of respect to my contractors, I can't disclose detailed information about projects I've woked on for third party companies. In most cases this include screenshots, and/or implementation details.
