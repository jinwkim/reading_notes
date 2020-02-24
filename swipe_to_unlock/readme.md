# Swipe to Unlock
Authors: Aditya Agashe, Neel Mehta, and Parth Detroja
Recommended book for understanding high-level ideas of product management, latest tech trends

## Chapter 1 - Software Development
* Google - Search
    * Indexing and crawling (10)
    * 90s - keyword density
    * Page and Brin - PageRank/popularity/credibility (12)
* Spotify - Recommender
    * Collaborative filtering (16)
    * Taste profile (16)
    * “Switching cost” to move to Apple Music and get the app to learn your tastes all over again, retain users
    * It’s easy to buy up a huge music library, need personalized recommender to attract users and retain them
* Facebook
    * What shows up on news feed can influence our thoughts and decisions
    * News feed visibility = Creator x Post x Type x Recency (18)
    * Tried to maximize engagement, probability that you’ll hit like or comment => the more you engage, the more you scroll, more ads to show (19)
    * Fake news trap - FB’s algorithm didn’t consider how true or accurate a post is, only maximized engagement in 2016 election (21)
* Uber / Yelp / Pokémon Go
    * Leverage existing Google Map to build, already well-established (vs. Apple Map that sucks) (22)
    * No need to reinvent the wheel
    * Use of Google Map APIs (application programming interfaces to let apps talk)
        * Feature APIs - outsource your another app to solve a problem (I.e. Venmo uses APIs to send confirmation emails)
        * Data APIs - query another app for info (I.e. subway wait times)
        * Hardware APIs - access features of physical devices (i.e. camera to take pictures, geolocation API, accelerometer)
    * API can lead to hostage situation - what if Google stopped Map service for Uber? What if eliminate FB SSO for Tinder?
* Tinder (26)
    * Facebook SSO API to prevent empty or fake accounts, gather existing data to match (and train its algorithm)
    * Facebook also gets info that you use Tinder (or other apps), which can help target better individualized ads (28-29)
* Washington Post / Buzzfeed - “Bandito” A/B testing framework
    * 2 headlines for article to maximize number of clicks and reads, display the more popular one
        * Article A gets 3.3%, B gets 3.9% => B gets 18% more
        * Display the winning version, the more “clickbaighty” headline
    * A / B testing - 2 variations of the same feature
    * Decent vs “perfected” headline - 1k vs 1M views
    * Statistical p value - if p<0.05, less than 5% chance that the difference was random => meaningful and statistically significant

## Chapter 2 - OS
* BlackBerry - initial dominant smartphone
    * Mainly targeted business users, QWERTY keyboard to communicate (34)
    * iPhones sold directly to consumers, employers started to let people use personal phones for work - “consumerization of the enterprise”
    * Also fell behind in “app economy”, lack of flexibility to develop apps consumers wanted
    * BlackBerry didn’t catch emerging trends (36)
* Google’s free & open-source Android
    * Free for likes of LG and Samsung to deploy, Google makes $31B a year - force Google search bar, default Google apps (YouTube, Maps), Google app purchases (take 30% cut) (37)
    * Google pays Apple $12B/year to make Google Search the default engine on iOS -> no need to pay with Android
    * i.e. custom Android - LineageOS for improved features and performance
    * Android built around “kernel” of Linux OS -> kernel is software that facilitates communication between software and hardware components (i.e. read/write files, connect to keyboard, etc.) -> kernel is like a car’s engine (39)
* Bloatware apps pre-installed on Android
    * i.e. Verizon Navigator (clone of Google Maps, $5/month), NFL Mobile, Samsung Pay, etc. (41)
    * Smartphone/data plans markets are pretty much saturated
        * Need to generate revenue - Verizon can install big companies’ apps for $1-2 per install, so if a phone comes with 10 bloatware apps, Verizon made $20 off you (43) => commission
        * Try to get consumers to use pricey knockoff apps that are pre-installed
            * Apple Maps is predominant on iPhones since Apple Maps is installed by default (44)
        * Typical average American downloads 0 apps a month (43)
        * Apple doesn’t need to install bloatware - most of the revenue comes from selling hardware
        * Google’s Pixel 3 and up are free of bloatware (Verizon, AT&T can’t install their bloatware)
* 3rd largest mobile OS - KaiOS
    * Lightweight OS for internet-connected feature phones
    * Targeted at India - 2nd most popular OS there (47)
        * 70% Android, 15% KaiOS, 10% iOS
        * Jio (48) - got people to sign up for super cheap voice/Internet plans, gave out non-touch Jio Phones for $20 (get back after 3 years) -> provided first taste of modern tech to many Indians
        * KaiOS to run on Jio phones, built on Firefox OS -> iOS and Android too bulky for lightweight phones (though, Firefox OS needed touchscreens)
* Macs - no viruses?
        * Windows has ~90% of desktop OS market share
        * Macs not immune to viruses, but by “sandboxing”, a virus in one part of computer can’t spread. Also, user permissions need to be given to run, and non-Apple approved can’t usually run (52)
        * 2012 “Flashback” largest Mac epidemic to date, 600,000 Macs infected

## Chapter 3 - App Economics
* App economy ~$100B market size despite most apps being free (only 6% of all downloaded apps on iOS are paid for) -> “monetization” strategies (56)
* Freemium: more features at a price
    * Tinder: more swipes through monthly subscription
    * Dropbox: free to get started, subscribe for more storage
    * In-app purchases
        * Extra lives on Candy Crush, new skins for Fortnite, custom geofilters for Snapchat, pay to remove ads
        * Once app is out, revenue is pure profit
    * Paid subscriptions
        * i.e. LinkedIn Premium, Spotify to remove ads and download music offline
        * Steady source of revenue, maximizing “lifetime value” of customers instead of one-time purchase
    * Pareto principle - 80-20 rule where 20% of “whale” customers will generate 80% of your revenue (61)
* Targeted ads - FB and Google
    * Apps and websites can charge advertisers a small fee every time someone views an ad - “Pay-Per-Impression (PPI)” (63) - Cost-Per-Mille (CPM for every 1,000)
    * CPC - cost per click
    * Every time a visitor loads a webpage, advertisers face off in an instant auction and the winner’s ad gets shown (64) - Google and Facebook optimize to maximize engagement, meaning more chance of earning commission
    * Google and Facebook know a lot about what you like, can use this massive data to do “ad targeting” (65)
    * Amazon - 3rd largest ad platform after Google (1st) and Facebook (66)
* Sponsored content / native ads
    * Posts/articles that look legitimate but are ads, “dressed-up” advertising (68)
    * Much more effective than banner ads, powerful revenue stream for news publications
    * Snap, Instagram, NYTimes, CNN, WSJ
    * Makes it difficult for readers to distinguish facts from marketing/advertising
    * Blurs the line between journalists and business marketing, may be impacting journalistic integrity
* Airbnb/Amazon/Uber - marketplace/platform apps
    * Connect buyers to sellers and earn commission by sneaking fees into purchases (71)
* Robinhood
    * Buy and sell stocks without an commission
    * Employ freemium model to sell subscription
    * Earn interest from unused money sitting in users’ accounts
* Grow first, monetize later (74)
    * Venmo first grew out user base by offering free service, then later rolled out Venmo debit card and ability to pay for Uber (75)

## Chapter 4 - The Internet
* Decoding URL
    * https://www.google.com
    * https:// -> protocol, how browser should connect to the website. 2 main protocols - HTTP (hypertext transfer protocol) vs HTTPS (HTTP secure, encrypt info) (80)
    * www -> like the +1 in 1-615-124-1411
    * google.com -> domain name
    * Everything after the domain name is the path (i.e. /maps)
* Domain Name Service (DNS)
    * Convert a domain name (google.com) to IP address (81)
    * Every website has at least 1 IP address
    * Like a giant address book. Your computer keeps a list of recent domain name-IP address pairs on hard drive, but otherwise, asks Internet Service Provider (ISP) like Verizon
    * google.com/maps -> 216.58.219.206/maps
* Request/response
    * Browser packages up “request” (google.com->216.58.219.206) and sends to “servers” powering Google website
    * Servers gather code (HTML, CSS, JS)
    * Servers send back code to your browser as “response”
* TCP (Transmission Control Protocol) / IP (Internet Protocol)
    * Websites typically too big to send at once, TCP splits them into little “packets” and attaches labels to keep track (85)
    * Servers use DNS to figure out your IP address to send back packets
    * IP sends each packet across the world in “hops” across various channels till they get to your computer, different routes may be taken (several intermediate shipments)
        * Packets of information hop from one computer to another till reaching final destination, like making stops on flights till final destination (88)
        * Packets can’t magically fly across the country, they have to travel across physical cables
    * Once packets arrive, TCP reassembles them in proper order and verify all received. If any missing, asks website to send the missing packets again
    * HTTP / HTTPS - Typically built on top of TCP/IP (86)
    * HTTP/HTTPS are like you placing an order for an item, TCP is like employee splitting up and packaging your items, and IP is like postal service making shipments and making delivery
* Internet cables
    * Information travels through underground cables when information is sent across the Internet via IP (90)
    * When sending information from your computer to another, we need to move 1’s and 0’s over the cables - tiny flashes of light (91)
    * Fiber-optic cable - made of pure glass, no thicker than human hair, clear. Information can travel at 2/3 speed of light, incredibly fast
    * Near straight line fiber-optic cable laid between Chicago and NYC to take advantage of arbitrage ($1.00 in NYC, sell for $1.01 in Chicago) for high frequency traders. Needed fast internet connection, maximized internet speed between 2 financial capitals

## Chapter 5 - Cloud Computing
* “The cloud” is just someone else’s computer (96)
    * Google Drive, Gmail -> done on Google’s servers in its “data centers” which need to be cooled to avoid overheating
    * Security issue - you are trusting someone else to keep your info safe
    * Privacy issue - what if Google or Microsoft read it? What if courts try to access it?
    * Connectivity issue - no Internet, no/limited access
* Software-as-a-service business model
    * Leasing a car instead of buying it (101)
    * Adobe - you used to be able to purchase the perpetual PhotoShop license, but now only a monthly subscription. Only checking the license uses the cloud
    * More consistent revenue for Adobe
    * Possible to make more frequent upgrades, resolve security issues quicker - “agile” development
    * In one year, Adobe boosted revenue 70% and doubled stock price
* Microsoft Office
    * “Frozen-in-time” versions released every 3 years, no updates in between (106)
    * Office 365 was a software-as-a-service, constant updates and new features, cloud storage on OneDrive
    * Office 365 more lucrative, can easily upsell to other subscription services like Azure
* AWS
    * Example of cloud computing services that saves people the hassle of getting their own data centers set up (107)
    * EC2 - Elastic Compute Cloud
    * S3 - Simple Storage Service
    * Cost to own/maintain significantly lower due to economics of scale with other users (108)
    * AWS keeps multiple copies of apps and data on different data centers around the world, so if one goes down, your data is still there
    * vs. on-prem - buy their own servers to run apps, avoid risk of AWS going down -2017 outage (20% of Internet down) (114)
* SaaS, IaaS, PaaS (110)
    * IaaS - infrastructre-as-a-service, let people borrow servers to run apps on
    * SaaS - software-as-a-service, let people run osftware
    * PaaS - platform-as-a-service, in between SaaS and IaaS - on top of IaaS, useful features like DB, analytics, OS
* Netflix
    * In 2008, Netflix owned its own servers, but moved to AWS by 2016 (111)
    * Elasticity - If there is a 30% spike in user utilization and need more servers, AWS will instantly grow/shrink computing power as necessary. You only pay for as much as you need
    * Scalability - If your application gets more users, instead of physically installing new servers all the time, let AWS do it automatically
    * Redundancy - AWS keeps multiple copies of the same code with many data centers

## Chapter 6 - Big Data
* Many stores use “savings cards” or “loyalty” cards to track your buying habits to create targeted offers
    * Walmart and Target instead keep a unique code to each credit card to understand a customer’s purchase history (119)
    * Use of public records (age, ethnicity, marriage, kids), guess salary, etc.
    * Boosts likelihood of purchase, better than random
* Target’s predictive analytics for pregnancy
    * ~87% confidence, might even predict approximate date of delivery (120)
    * Identified a group of ~25 buying habits to assign a “pregnancy prediction” score
    * i.e. Suddenly buying large amounts of unscented lotion, supplements/vitamins
    * Coming off as creepy? So throw in “random” seeming coupons too (121)
* Analyzing big data
    * Data is too massive to store or analyze on even a supercomputer (122)
    * Key is to break down data and computation into more manageable chunks that can be handled by an army of commodity computers and combine results
    * Google’s MapReduce algorithm - “Map” is to delegate to have your friends count each neighborhood population, “Reduce” is to combine the results to get a final total (123)
    * Hadoop uses MapReduce to store all your data on a bunch of normal-sized servers, no expensive supercomputers. Then run Hadoop software to crunch the numbers. Just add more computers to accommodate more data as necessary
* Amazon’s pricing
    * Amazon updates pricing on average every 10 minutes (124)
    * Analyzes customer’s shopping patterns, competitor prices, profit margins, etc. to choose new prices and squeeze out more profit
    * i.e. Discount bestselling products to lure customers, but upsell on more obscure products. Customers assume Amazon has better pricing
    * Data-driven suggestions - “frequently bought together” to recommend items based on yours and other customers’ purchase histories
    * “Anticipatory Shipping Model” - Amazon predicts what you might buy in the near future so they ship that item to a warehouse near you. When you do buy it, you get it quickly and cheaply (126)

## Chapter 7 - Hacking & Security
* Malware - dangerous software that can infect computers and harm people
    * WannaCry - Ransomware that invades your computer, locks up files, and threatens to trash it unless you pay up. In May 2017, WannaCry infected computers in 150 countries, including Britain’s National Health Service (130)… This attack was linked to North Korea
    * Can be downloaded onto your computer, exploit a flaw in the OS, and encrypt all your personal files to become unusable. Can decrypt with a “key” that you need to pay for
    * Often ask for payment in Bitcoin to remain anonymous
* Deep web
    * Includes all the information on the Internet that you can’t find through a Google search (136)
    * i.e. Google Drive files, medical records, FB posts
* Dark web
    * Subset of deep web that you can’t access… without special software that encrypts communications and anonymizes your IP address (136)
    * Example software - Tor encrypts and anonymizes… layers of encryption and bounces communication around many intermediate “relay” computers like the onion-style described below - privacy enhancing web browser!
    * Used to make sure all activity on the site is untraceable
    * Often end in “.onion”… communication is literally an onion (137)
    * i.e. Sending a box from Seattle to Philly… outermost box Seattle to Denver, 2nd outer box Denver to Houston, Houston to Miami, Miami to Philly… No post office knows exactly who is sending to who
    * Silk Road (Amazon-like) was taken down since the centralized “escrow” account to hold BTC between sellers and buyers was traced by programming mistakes, physical location of its servers seized (140)
    * OpenBazaar - new marketplace like flea market for shoppers and merchants to exchange directly, no centralized escrow (141)… harder to take down
* Facebook and dark web
    * Facebook started offering dark websites to protect its users like political dissidents in countries where FB is restricted like China (142)
* WhatsApp
    * Typically the web uses HTTP to encrypt information sent between your computer and a website’s servers, but the encrypted info may be decrypted like when Amazon wants to decrypt and read your credit card number, Google used to read your Gmail to target ads until 2017 (143)… even governments can
    * Asymmetric encryption/public key cryptography - WhatsApp used “end-to-end” encryption to only let you and your recipient decrypt messages, WhatsApp/Facebook cannot figure out what you are saying (145)
    * Every user is given a public key and a private key… every message is encrypted using the recipient’s public key and can only be decrypted using the private key and computations
* Apple’s iPhone encryption
    * Before 2016, Apple had a forced-bypass feature in iPhones to unlock iPhones, but with iOS8 and up, removed it so even Apple couldn’t unlock iPhones (147)… sued by FBI
    * UID technology - Now the iPhone is hashed and compares the computed hash for your password combined with the phone’s UID (256-bit code), can’t reverse engineer
    * Only way to get in is to brute-force passwords, but iPhones wipe out after 10 failed attempts
* If you connect to phony WiFi networks, hackers can see and manipulate every message you exchange with websites
    * “Man-in-the-middle” attack - HTTPS should encrypt all communications, but if they use SSLStrip, they can fool your computer into talking with a server over HTTP instead of HTTPS (149) - can intercept your login information and impersonate you
* Virtual Private Network (VPN)
    * Create a sort of end-to-end encryption between you and the websites you are visiting so your router can’t harm you
    * Create a direct, secure “tunnel” between you and websites, turning public Wi-Fi networks into private ones

## Chapter 8 - Hardware and Photos
* Central Processing Unit (CPU)
    * Small square chip - “Brains of the operation”, carries out all computations to run device (157)
    * Made up of smaller sections “cores”
    * Clock speed - number of calculations per second (GHz) - 1 GHz = billion calculations per second
    * 2 major types: ARM (cheaper, use less battery) vs Intel (x86; more powerful) - traditionally, phones used ARM while computers used Intel. Now ARM ~ Intel, similar
* Storage: long-term memory
    * Hard drive (HDD) - spinning metal plate coated with a layer of magnets to store info, read/write arm (159) - prone to break down, noisy, heavy, use lots of power
    * Solid-state drive (SSD) - no moving parts, stores info in a huge grid of cells (0s and 1s), more efficient, lighter - instance of “flash memory” designed for computers
    * Phones/tablets/cameras can only use flash memory
* RAM: Short-term memory
    * Random-access memory - each app you run, each browser tab you open, each Word document you write utilizes RAM; RAM is much faster than hard drive/SSD (162)
    * If you don’t save, the RAM is cleared
    * RAM helps computer do many computations at once, in limited amount
* Apple & “Planned Obsolescence”
    * Apple was deliberately designing phones to slow down older iPhones to reduce peak power usage, in an attempt to reduce chances of crashes and improve battery life. Older phones have declining battery capacity while newer apps demand more power (164)
    * People thought Apple was forcing “planned obsolescence” to force people to upgrade to new phones
    * Apple provided $29 battery replacements (original $79) and people saw rejuvenated phones, leading to fewer phone upgrades and $7 billion lower than expected upgrades (XR, XS)
* Unlocking phones
    * Optical scanning - oldest method of fingerprint scanning to take a picture of your fingerprint, generate high-contrast version of your print, and compare to internal DB (166)
    * Capacitive scanning - Capacitors to change capacitance where ridges are, identify fingerprints
    * Biometrics - facial recognition
    * Not all hack-proof
* Apple Pay
    * Built off NFC - near-field communication, exchange information using radio waves when touched together (168)
    * Use very little (or no) energy - i.e. subway cards
    * Strengthened security to encrypt credit card number into a 16-digit token, also verify payment with fingerprint/facial recognition
* Augmented reality
    * i.e. Pokemon Go - overlay Pokemon on your immediate environment (172)
    * Estimated $90 billion market by 2020
* Amazon and 1-hour (half-hour) deliveries
    * People and robots working together with algorithms like Anticipatory Shipping Model for geographic locations and people’s tendencies (175)
    * Amazon Prime Air to use automated drones, but FAA regulations make it tough (178)

## Chapter 9 - Business Motives
* Nordstrom and WiFi triangulation
    * In 2012, Nordstrom realized they can offer “FREE WI-FI” and track which Wi-Fi hotspots shoppers were connected to and pinpoint shoppers’ locations (183)
    * When you turn on Wi-Fi on a phone, it sends out a radio signal to routers that let you connect to the internet. The radio signals sent out by phones include a unique code embedded in the phone “MAC address” and router’s owner can see your MAC address, which they can remember to see if you reconnect
    * Triangulate by using 3 hotspots to track the same MAC Address (you) and measure the strength of radio signal from phone to each router. Where the circles from routers intersect - your location (184)
    * Use user data to see where they shop the most, what items they spend most time looking, what days/times are busiest, how much time people spend outside looking into stores => turn into data
    * Paired with video cameras of stores or email offers for coupons, MAC Address can potentially be used to identify users (186)
* Amazon and free Prime shipping
    * 2/3 of all American households are on Prime for $119/year, and Amazon loses over $8 billion/year from its free 2-day shipping (188)
    * Amazon focused on increasing revenue than profits, re-invest revenue back into company
    * Prime is a powerful loyalty program getting people to feel “instant gratification” and justify spending with $119 already paid, get Amazon shopping to become a habit
    * “Race to the bottom” to get competitors forced to offer free 2-day shipping (190)
* Uber & self-driving cars
    * Uber loses over $1 billion/year, keeps re-investing revenue in expensive areas like food delivery and electric scooters, failed expansions in China/Russia (192)
    * 4% driver retention rate within a year - needs to keep offering bonuses and incentives to keep drivers
    * Uber takes ~20% profits on each ride - need to cater to both riders (cheaper rides) and drivers (give enough pay)
    * Self-driving solution - no need to worry about driver retention/pay for drivers, may only cost 1/10 with self-driving of current costs
* Microsoft’s acquisition of LinkedIn
    * MS’s largest acquisition to date in 2016 - $26.2 billion (195)
    * New mission for MS since 2015 - “to empower every person and every organization on the planet to achieve more” - CEO Satya Nadella
    * LinkedIn acquisition cemented MS’s place as a leader in the enterprise space
    * “Economic graph” to combine its data on business workers (Outlook, MS Office) and LinkedIn data (worker relationships with colleagues, past jobs)
    * Wanted to keep LinkedIn’s valuable data and user base away from competitors (i.e. Salesforce)
* Facebook’s acquisition of Instagram for $1 billion in 2012
    * Instagram was largely unprofitable and had 0 revenue, but Facebook acquired Instagram for “mobile photos” (200)
    * Facebook started as a desktop web company, didn’t really have a way to monetize mobile at all. Instagram changed this
    * Instagram grew from 30 million users in 2012 to 1+ billion in 2018
    * Instagram ads bring in $8+ billion/year (201)
* Facebook’s acquisition of WhatsApp
    * Acquired for $19 billion in 2014. Similar to Facebook Messenger, but WhatsApp had a strong international market especially in developing countries where FB Messenger was weak (202)
    * Bring in more data on users for targeted ads and services
    * In 2014, WhatsApp users sent more pictures than FB and Instagram combined
    * 91% of FB’s ad revenues come from mobile, so without mobile OS like Apple and Google, FB realized it needed to control as as many popular apps as possible - WhatsApp was most popular app on both Android and iOS (203)
    * WhatsApp filled FB’s gaps in developing countries, user data, mobile, and photos

## Chapter 10 - Emerging Markets
* In 2018, Facebook had flatlined growth in US/Canada, began shrinking in Europe - most of the growth was coming from the developing world - China, India, Latin America, Africa, Southeast Asia (206)
    * Too late for China, too early for Africa
* China’s Great Firewall and restrictions on the Internet are obstacles to Western companies, favorable to Chinese homegrown tech companies that mirror US giants (208)
* Apple’s Exception in China
    * Apple has managed to succeed in China by selling more iPhones in China than in the US (208)
    * Prone to competition from Xiaomi and political tensions
* Facebook still profits from China
    * Chinese companies want to advertise on Facebook (209)
    * China helps make up 1/10 of Facebook’s global revenue
* India
    * World’s largest democracy, over a billion smartphones in the country (209)
    * Jio and it’s dirt-cheap data ($0.15 for 1GB data) fueled India’s growing mobile economy, skipping PC era, and put users in land of YouTube and WhatsApp (210)
    * India remains open to foreign firms, no homegrown titans
    * Localization - India has 29 languages and a myriad of cultures, need to cater to large localized populations
* Southeast Asia
    * Includes countries like Indonesia, Thailand, and the Philippines, 3rd-largest market in terms of internet users (212)
    * Americans spend 2 hours a day, SEA spends 4 hours a day on phones
    * Open to development, lots of opportunities
    * Unlike India where the region has a unified set of laws, different countries make up SEA
* Latin America
    * “While the best time to get into India was yesterday, and the best time to get into Southeast Asia is today, the best time to get into Latin America is definitely tomorrow” (213)
    * Latin America has a GDP almost as big as China
    * Brazil - 4th place in terms of most internet users
* Africa
    * Not yet developed enough, internet infrastructure is below-par, and Internet penetration in Africa is ~50% of worldwide average (214)
    * Feature phones like those using KaiOS (from India’s Jio) help fuel feature phones
    * Facebook (Free Basics internet.org project) is helping put up internet infrastructure to grow internet connectivity - i.e. access FB apps for free (215)
        * Banned in India for violating net neutrality -  principle that Internet service providers should enable access to all content and applications regardless of the source, and without favoring or blocking particular products or websites
* Kenya is “world’s unlikely leader in mobile payments”
    * Mobile banking has taken off in developing countries since many don’t have bank accounts, lack financial literacy (216)
    * ~2 billion people mostly in developing countries do not have bank accounts
    * “M-Pesa” is a money-transfer service that lets people send money with texting, 25% of Kenyan GDP flows through it, 2/3 of Kenyan population uses it (217) - Venmo minus smartphones/internet/bank account
    * Simplest technologies to power mobile payments, available since 2007 (earlier than Venmo - 2009)
* WeChat - China’s “Official” app
    * Do everything from maps, paying, booking appointments, calling cabs (220)
    * ~900 million users
    * Kicked off with fun, viral features - “hongbao” to send random amounts of money to friends, first to open in a group chat gets it - people connected bank accounts, and got hooked onto WeChat’s payment system (221)
    * Hongbao took WeChat from ~30 million users up to ~100 million
    * Now more than just a messaging app
    * WeChat also worked closely with the Chinese government, hands over user data
    * WeChat is like an “Operating System” for users - link identity, payment information that can be reused in all kinds of apps, unlike in US where you have separate apps (223)
* Paying with QR code in Asia
    * Unlike M-Pesa in Africa, WeChat Pay/Alipay (combined 1.4 billion users) require bank accounts, phone numbers, smartphones, and official IDs. But unlike Africa, most in China have smartphones (225)
    * Grab (Alibaba in Singapore) and Go-Jek (Tencent in Indonesia) started off with ride-sharing, get people to store payment information, and now start selling them anything and everything (226)
    * Uber lost out to Grab, had to sell its stake go Grab
* Paytm in India
    * When Indian government demonetized 500- and 1000-rupee notes, this forced people to experiment with cashless payment systems like Paytm, a mobile payment system (228)
    * Paytm is trying to become the next WeChat and dominate India’s tech scene
* Western vs Eastern tech companies’ strategies
    * Western companies expand into emerging markets through existing apps and models
    * Eastern/Chinese companies invest in local businesses that create apps and business models custom-tailored for local markets (230)
    * Chinese companies tend to let entrepreneurs in respective countries build tailored companies and buy them once they are ready
    * Various pros and cons… (232)

## Chapter 11 - Technology Policy
* Internet Service Providers
    * ISPs sit between you and every website you visit, they can track your entire browsing history, and then sell this information with demographic info to advertisers (236)
    * In 2017, Congress killed “broadband privacy” regulations so ISPs can sell your information, no more net neutrality
    * ISPs tend to have monopolies in certain regions, they can up-charge you and sell your data, but you have no other options (238)
    * High barrier to entry - Google Fiber had to scale down in 2017
* Zero rating
    * No data charges for using certain apps - AT&T for DirecTV is free (240)
    * One of the hot topics in ongoing debate over net neutrality - principle that ISPs should treat all data equally
    * ISPs control access to the internet… now they get to tilt the playing field for companies that pay them the most for data, making internet lose openness
    * Study on zero rating with 30 EU countries by Epicenter.works - zero rating actually led wireless carriers to increase prices, where banned zero rating brought down prices (243) - once customers get hooked on zero rating agreements, no need to compete
* Net neutrality
    * Principle that Internet service providers should enable access to all content and applications regardless of the source, and without favoring or blocking particular products or websites
* Unfair practices by ISPs (3)
    * “Blocking” - AT&T tried to ban FaceTime for customers on cheaper data plans
    * “Throttling” - ISPs slow down content from competitor websites - Verizon and Comcast slowed down Netflix content to promote their own streaming services (242)
    * “Paid prioritization” - load a website’s information faster than competitors when ISP deals with a website - an example is “zero rating”
* EU “right to be forgotten” law & Google
    * A doctor in England got his past malpractice records removed from Google Search under EU’s privacy law “right to be forgotten”
* US Government and National Weather Service
    * Since 1870, weather on data has been collected by NWS. By selling to private companies to use in their own forecasts, this is valued at $5 billion (249)
    * US government created a $5 billion industry by making data available
* Today, not many companies are too keen on data breaches due to lack of severe consequences, EU tends to be stricter than the US as in General Data Protection Regulation where companies with breached data owe 4% of annual revenue (254)
    * Equifax breach for 143 million (half US population), Yahoo breach for 1 billion users, Anthem hacked and leaked 80 million accounts

## Chapter 12 - Trends Going Forward
* Self-driving cars
    * LIDAR to create a 360 degree model of its surroundings, cameras to tell obstacles apart, ultimately creating a 3D model of the world (259)
    * Driving strategy based on sensors, 3D model, GPS…
    * Machine learning - a computer making predictions based on observed patterns… can’t 100% teach computers how to drive
    * Options for future of rideshare… Waymo One (Google) vs. Uber/Lyft (261) - but Google can always restrict Google Maps APIs, etc.
    * But still have safety, legal, and ethical issues -> need “algorithmic transparency”
* Labor-enabling vs labor-replacing technologies - tech vs labor (265)
    * ATMs were once thought to reduce tellers, but now that it’s cheaper to operate bank branches, more branches were opened, and # tellers in US grew from 300,000 to 600,000 from 1970 to 2010 (266)
* Deepfakes & GANs
    * Video and audio can also be faked using “generative adversarial networks” GANs (270)
    * GANs - 2 neural networks “generator” to make something fake, “discriminator” to see if the generator’s creation is real or not (271)… constantly learning from each other to produce fake things
    * vs. neural networks that takes feedback to learn certain patterns (i.e. autocorrect, translate, reading handwriting, etc.) (271)
* Facebook’s acquisition of Oculus
    * Long-term vision to use VR to experience sports, lectures, doctors appointments, chat with friends (273)
* Amazon advantage over other companies
    * Amazon is an infrastructure company before all (278), in addition to tech, cloud, goods, pills
    * Warehouses and now Whole Foods grocery stores 
    * Amazon displays monopolistic tendencies across multiple verticals that can prevent future start-ups, but current US antitrust laws primarily prevent horizontal mergers (competitors trying to merge like Comcast and Times Warner Cable)