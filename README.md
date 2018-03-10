# ConFoo MTL 2018 Speaker decks

Lists below all speaker decks from [ConFoo MTL 2018](https://confoo.ca).

Please correct any missing links or errors by opening a PR.

Inspired by https://github.com/dav-m85/confoo-mtl-2017-decks.

I'm way too lazy to fill the session and speaker name manually, so I just used this small script on https://confoo.ca/en/yul2018/schedule:

```javascript
$('.slot').each(function () {
    const $session = $(this).find('.session');
    const sessionTitle = $session.text().trim();
    const sessionUrl = $session.find('a').attr('href');
    console.log(`#### [${sessionTitle}](https://confoo.ca${sessionUrl})`);

    const $speaker = $(this).find('.speaker');
    const speakerName = $speaker.text().trim();
    const speakerUrl = $speaker.find('a').attr('href');
    console.log(`By [${speakerName}](https://confoo.ca${speakerUrl})`);
});
```

```
By ...
Deck [deck type](deck link)
Twitter [@account](https://twitter.com/account)
Github [user](https://github.com/user)
```

## Table of content

- [ConFoo MTL 2018 Speaker decks](#confoo-mtl-2018-speaker-decks)
  * [Wednesday](#wednesday)
    + [10:00-10:45](#1000-1045)
    + [11:00-11:45](#1100-1145)
    + [13:00-13:45](#1300-1345)
    + [14:00-14:45](#1400-1445)
    + [15:00-15:45](#1500-1545)
    + [16:00-16:30](#1600-1630)
  * [Thursday](#thursday)
    + [9:00-9:25](#900-925)
    + [9:25-9:50](#925-950)
    + [10:00-10:45](#1000-1045-1)
    + [11:00-11:45](#1100-1145-1)
    + [13:00-13:45](#1300-1345-1)
    + [14:00-14:45](#1400-1445-1)
    + [15:00-15:45](#1500-1545-1)
    + [16:00-16:45](#1600-1645)
  * [Friday](#friday)
    + [09:00-09:45](#0900-0945)
    + [10:00-10:45](#1000-1045-2)
    + [11:00-11:45](#1100-1145-2)
    + [13:00-13:45](#1300-1345-2)
    + [14:00-14:45](#1400-1445-2)
    + [15:00-15:45](#1500-1545-2)

## Wednesday
### 10:00-10:45
#### [Think Async in NodeJS](https://confoo.ca/en/yul2018/session/think-async-in-nodejs)
By [Adam L Barrett](https://confoo.ca/en/speaker/adam-l-barrett)

Twitter [@adamlbarrett](https://twitter.com/adamlbarrett)

Joind in [comment](https://joind.in/event/confoo-montreal-2018/think-async-in-nodejs)

#### [Small intro to Big Data](https://confoo.ca/en/yul2018/session/small-intro-to-big-data)
By [Michał Matłoka](https://confoo.ca/en/speaker/michal-matloka)

#### [How I learned to stop worrying and love Regular Expressions](https://confoo.ca/en/yul2018/session/how-i-learned-to-stop-worrying-and-love-regular-expressions)
By [Jordi Boggiano](https://confoo.ca/en/speaker/jordi-boggiano)

#### [Scale search powered apps with Elasticsearch, k8s and go](https://confoo.ca/en/yul2018/session/scale-search-powered-apps-with-elasticsearch-k8s-and-go)
By [Maxime Boisvert](https://confoo.ca/en/speaker/maxime-boisvert-1)

#### [Extracting data from the Internet with Scrapy](https://confoo.ca/en/yul2018/session/extracting-data-from-the-internet-with-scrapy)
By [Israël Hallé](https://confoo.ca/en/speaker/israel-halle)

#### [Accessibility Foundations](https://confoo.ca/en/yul2018/session/accessibility-foundations)
By [Sean Yo](https://confoo.ca/en/speaker/sean-yo)

#### [IoC container beyond constructor injection](https://confoo.ca/en/yul2018/session/ioc-container-beyond-constructor-injection)
By [Hannes Van De Vreken](https://confoo.ca/en/speaker/hannes-van-de-vreken)

#### [Speed Date With An SEO / SEM / WPO Specialist](https://confoo.ca/en/yul2018/session/speed-date-with-an-seo-sem-wpo-specialist)
By [Marc Perez](https://confoo.ca/en/speaker/marc-perez)

#### [Java EE 8 & HTTP/2](https://confoo.ca/en/yul2018/session/java-ee-8-http-2)
By [Ryan Cuprak](https://confoo.ca/en/speaker/ryan-cuprak)

### 11:00-11:45

#### [Designing for Users: How to Create a Better User Experience](https://confoo.ca/en/yul2018/session/designing-for-users-how-to-create-a-better-user-experience-1)
By [Clarissa Peterson](https://confoo.ca/en/speaker/clarissa-peterson)

#### [ReST 3.0 – a Lap around HTTP APIs’ next Generation](https://confoo.ca/en/yul2018/session/rest-3-a-lap-around-http-apis-next-generation)
By [Sebastien Lambla](https://confoo.ca/en/speaker/sebastien-lambla)

#### [Why and How Instagram Built for Mobile Web](https://confoo.ca/en/yul2018/session/why-and-how-instagram-built-for-mobile-web)
By [Jennifer Lin](https://confoo.ca/en/speaker/jennifer-lin)

#### [Automatic web requests clustering for latency analysis](https://confoo.ca/en/yul2018/session/automatic-web-requests-clustering-for-latency-analysis)
By [Naser Ezzati Jivan](https://confoo.ca/en/speaker/naser-ezzati-jivan)

#### [Harnessing the power of AWS using .NET Core](https://confoo.ca/en/yul2018/session/harnessing-the-power-of-aws-using-net-core)
By [Dror Helper](https://confoo.ca/en/speaker/dror-helper)

#### [Database schema migrations with zero downtime](https://confoo.ca/en/yul2018/session/database-schema-migrations-with-zero-downtime)
By [Michiel Rook](https://confoo.ca/en/speaker/michiel-rook)

#### [Ruby for Non-Rubyists](https://confoo.ca/en/yul2018/session/ruby-for-non-rubyists)
By [Brad Urani](https://confoo.ca/en/speaker/brad-urani)

#### [Ecommerçants, augmentez votre taux de conversion.](https://confoo.ca/en/yul2018/session/ecommercants-augmentez-votre-taux-de-conversion)
By [Thomas Deneulin](https://confoo.ca/en/speaker/thomas-deneulin)

#### [Java EE 8 is final! Now what?](https://confoo.ca/en/yul2018/session/java-ee-8-is-final-now-what)
By [David Delabassee](https://confoo.ca/en/speaker/david-delabassee)

### 13:00-13:45

#### [Modern jQuery: Refactoring and Testing the Way Forward](https://confoo.ca/en/yul2018/session/modern-jquery-refactoring-and-testing-the-way-forward)
By [Ken Dale](https://confoo.ca/en/speaker/ken-dale)

#### [There's more to performance than meets the eye](https://confoo.ca/en/yul2018/session/there-s-more-to-performance-than-meets-the-eye)
By [Léonie Watson](https://confoo.ca/en/speaker/leonie-watson)

#### [Gentle introduction to SSL/TLS, certificates, and TLS 1.3](https://confoo.ca/en/yul2018/session/gentle-introduction-to-ssl-tls-certificates-and-tls-1-3)
By [Christian Heimes](https://confoo.ca/en/speaker/christian-heimes)

#### [Ingest node: enriching documents within Elasticsearch](https://confoo.ca/en/yul2018/session/ingest-node-enriching-documents-within-elasticsearch-1)
By [David Pilato](https://confoo.ca/en/speaker/david-pilato)

#### [Designing a DSL with Kotlin](https://confoo.ca/en/yul2018/session/designing-a-dsl-with-kotlin)
By [Nicolas Fränkel](https://confoo.ca/en/speaker/nicolas-fraenkel)

#### [Atteindre les étoiles avec PHP et Symfony](https://confoo.ca/en/yul2018/session/atteindre-les-etoiles-avec-php-et-symfony)
By [Mikael Randy](https://confoo.ca/en/speaker/mikael-randy)

#### [Building chat bots with Bot Framework in Node.js](https://confoo.ca/en/yul2018/session/building-chat-bots-with-bot-framework-in-node-js-1)
By [Christopher Harrison](https://confoo.ca/en/speaker/christopher-harrison)

#### [Build your own cryptocurrency for fun and fractional profit](https://confoo.ca/en/yul2018/session/build-your-own-cryptocurrency-for-fun-and-fractional-profit)
By [Andrew Lombardi](https://confoo.ca/en/speaker/andrew-lombardi)

#### [An Introduction of Interator Pattern in Ruby](https://confoo.ca/en/yul2018/session/an-introduction-of-interator-pattern-in-ruby)
By [Weihang Jian](https://confoo.ca/en/speaker/weihang-jian)

### 14:00-14:45

#### [Asynchronicity: concurrency. A tale of](https://confoo.ca/en/yul2018/session/asynchronicity-concurrency-a-tale-of)
By [Joel Lord](https://confoo.ca/en/speaker/joel-lord)

#### [A simple Node checklist to follow](https://confoo.ca/en/yul2018/session/a-simple-node-checklist-to-follow)
By [Gleb Bahmutov](https://confoo.ca/en/speaker/gleb-bahmutov)

#### [Does it NEED to be a PWA?](https://confoo.ca/en/yul2018/session/does-it-need-to-be-a-pwa)
By [Tara Z. Manicsic](https://confoo.ca/en/speaker/tara-z-manicsic)

#### [Building Distributed Systems in Distributed Teams](https://confoo.ca/en/yul2018/session/building-distributed-systems-in-distributed-teams)
By [Philipp Krenn](https://confoo.ca/en/speaker/philipp-krenn)

#### [The B-Tree,  the biggest problem of Ai?](https://confoo.ca/en/yul2018/session/the-b-tree-the-biggest-problem-of-ai)
By [Jonathan Duquette](https://confoo.ca/en/speaker/jonathan-duquette)

#### [Strong crypto for everyone - libsodium in PHP 7.2](https://confoo.ca/en/yul2018/session/strong-crypto-for-everyone-libsodium-in-php-7-2)
By [Marcus Bointon](https://confoo.ca/en/speaker/marcus-bointon)

#### [Integrate your Machine Learning algorithm with Elasticsearch](https://confoo.ca/en/yul2018/session/integrate-your-machine-learning-algorithm-with-elasticsearch)
By [Loic Bertron](https://confoo.ca/en/speaker/loic-bertron)

#### [Papa, je veux déployer dans les nuages](https://confoo.ca/en/yul2018/session/papa-je-veux-deployer-dans-les-nuages)
By [Henri Tremblay](https://confoo.ca/en/speaker/henri-tremblay)

#### [A Deep Dive into New Ruby Features](https://confoo.ca/en/yul2018/session/a-deep-dive-into-new-ruby-features)
By [Shannon Skipper](https://confoo.ca/en/speaker/shannon-skipper)

### 15:00-15:45

#### [Building intelligent apps for lazy coders](https://confoo.ca/en/yul2018/session/building-intelligent-apps-for-lazy-coders-1)
By [Susan Ibach](https://confoo.ca/en/speaker/susan-ibach)

#### [You're only supposed to blow the bloody doors off!](https://confoo.ca/en/yul2018/session/you-re-only-supposed-to-blow-the-bloody-doors-off)
By [Léonie Watson](https://confoo.ca/en/speaker/leonie-watson)

#### [Produce the key DevOps metrics that management understands](https://confoo.ca/en/yul2018/session/produce-the-key-devops-metrics-that-management-understands)
By [Olivier Gourment](https://confoo.ca/en/speaker/olivier-gourment)

#### [Behat: Why and How?](https://confoo.ca/en/yul2018/session/behat-why-and-how)
By [Anna Filina](https://confoo.ca/en/speaker/anna-filina)

#### [Writing Viruses for Fun, not Profit](https://confoo.ca/en/yul2018/session/writing-viruses-for-fun-not-profit)
By [Ben Dechrai](https://confoo.ca/en/speaker/ben-dechrai)

#### [Demystifying Asynchronous Programming in .Net](https://confoo.ca/en/yul2018/session/demystifying-asynchronous-programming-in-net)
By [Pierre-Luc Maheu](https://confoo.ca/en/speaker/pierre-luc-maheu)

#### [Composing Music in the Cloud](https://confoo.ca/en/yul2018/session/composing-music-in-the-cloud)
By [James Weaver](https://confoo.ca/en/speaker/james-weaver)

### 16:00-16:30

#### [Innovating is not about technology, but psychology](https://confoo.ca/en/yul2018/session/innovating-is-not-about-technology-but-psychology)
By [Alyssa Nicoll](https://confoo.ca/en/speaker/alyssa-nicoll)

## Thursday
### 9:00-9:25

#### [The Myth of Culture](https://confoo.ca/en/yul2018/session/the-myth-of-culture)
By [Ken Coar](https://confoo.ca/en/speaker/ken-coar-1)

### 9:25-9:50

#### [Code Is Not Neutral: the Ethics of Programming](https://confoo.ca/en/yul2018/session/code-is-not-neutral-the-ethics-of-programming)
By [Clarissa Peterson](https://confoo.ca/en/speaker/clarissa-peterson)

### 10:00-10:45

#### [Faire de la revue de code comme un pro](https://confoo.ca/en/yul2018/session/faire-de-la-revue-de-code-comme-un-pro)
By [Marc-Antoine Aubé](https://confoo.ca/en/speaker/marc-antoine-aube-1)

#### [Creating and Distributing Custom Web Components](https://confoo.ca/en/yul2018/session/creating-and-distributing-custom-web-components)
By [Ken Dale](https://confoo.ca/en/speaker/ken-dale)

#### [So you are not using an ORM yet ?](https://confoo.ca/en/yul2018/session/so-you-are-not-using-an-orm-yet-1)
By [Michael Simonson](https://confoo.ca/en/speaker/michael-simonson-1)

#### [Add Machine Learning to your iOS App with Core ML](https://confoo.ca/en/yul2018/session/add-machine-learning-to-your-ios-app-with-core-ml)
By [Jean-Luc David](https://confoo.ca/en/speaker/jean-luc-david-1)

#### [Trace Against the Clock: Tracing Frameworks and Methodology](https://confoo.ca/en/yul2018/session/trace-against-the-clock-tracing-frameworks-and-methodology)
By [Brent Shaffer](https://confoo.ca/en/speaker/brent-shaffer)

#### [Developing multi-platform microservices using .NET core](https://confoo.ca/en/yul2018/session/developing-multi-platform-microservices-using-net-core)
By [Dror Helper](https://confoo.ca/en/speaker/dror-helper)

#### [Functional approach in software design](https://confoo.ca/en/yul2018/session/functional-approach-in-software-design)
By [Tomasz Kowalczyk](https://confoo.ca/en/speaker/tomasz-kowalczyk-1)

#### [More Secrets of Cryptography](https://confoo.ca/en/yul2018/session/more-secrets-of-cryptography)
By [Christopher Riley](https://confoo.ca/en/speaker/christopher-riley)

#### [Using Ruby to Get out of Debt](https://confoo.ca/en/yul2018/session/using-ruby-to-get-out-of-debt)
By [Jason Charnes](https://confoo.ca/en/speaker/jason-charnes)

### 11:00-11:45

#### [Hot Reloading Everywhere](https://confoo.ca/en/yul2018/session/hot-reloading-everywhere)
By [Christophe Porteneuve](https://confoo.ca/en/speaker/christophe-porteneuve)

#### [API Development with Laravel](https://confoo.ca/en/yul2018/session/api-development-with-laravel)
By [Michael Peacock](https://confoo.ca/en/speaker/michael-peacock)

#### [What's new in PostgreSQL 10](https://confoo.ca/en/yul2018/session/what-s-new-in-postgresql-10)
By [Magnus Hagander](https://confoo.ca/en/speaker/magnus-hagander)

#### [Authentication: passwords, 2FA, Kerberos, OpenIDC, and more](https://confoo.ca/en/yul2018/session/authentication-passwords-2fa-kerberos-openidc-and-more)
By [Christian Heimes](https://confoo.ca/en/speaker/christian-heimes)

#### [Spark 101](https://confoo.ca/en/yul2018/session/spark-101)
By [Francis Toth](https://confoo.ca/en/speaker/francis-toth-1)

#### [Exploring .NET’s memory management – a trip down memory lane](https://confoo.ca/en/yul2018/session/exploring-net-s-memory-management-a-trip-down-memory-lane-1)
By [Maarten Balliauw](https://confoo.ca/en/speaker/maarten-balliauw)

#### [Optimize Prime: More Pixels Than Meets The Eye](https://confoo.ca/en/yul2018/session/optimize-prime-more-pixels-than-meets-the-eye)
By [Henri Helvetica](https://confoo.ca/en/speaker/henri-helvetica)

#### [How the role of data science evolves in a startup](https://confoo.ca/en/yul2018/session/how-the-role-of-data-science-evolves-in-a-startup)
By [Frederic Thouin](https://confoo.ca/en/speaker/frederic-thouin)

#### [Extracting A Gem From Your Rails App](https://confoo.ca/en/yul2018/session/extracting-a-gem-from-your-rails-app-1)
By [Sophie Déziel](https://confoo.ca/en/speaker/sophie-deziel)

### 13:00-13:45

#### [Techniques to Design Better Object Oriented Softwares](https://confoo.ca/en/yul2018/session/techniques-to-design-better-object-oriented-softwares)
By [Hugo Hamon](https://confoo.ca/en/speaker/hugo-hamon)

#### [Fighting JavaScript with JavaScript](https://confoo.ca/en/yul2018/session/front-end-localization)
By [Karim Baaba](https://confoo.ca/en/speaker/karim-baaba)

#### [Build & deploy in the Cloud with Packer, Ansible & Terraform](https://confoo.ca/en/yul2018/session/build-deploy-in-the-cloud-with-packer-ansible-terraform)
By [Thijs Feryn](https://confoo.ca/en/speaker/thijs-feryn)

#### [Advanced search for your legacy application](https://confoo.ca/en/yul2018/session/advanced-search-for-your-legacy-application-1)
By [David Pilato](https://confoo.ca/en/speaker/david-pilato)

#### [Un meilleur taux de succès de cache avec l'IA](https://confoo.ca/en/yul2018/session/un-meilleur-taux-de-succes-de-cache-avec-l-ia)
By [Michael Gradek](https://confoo.ca/en/speaker/michael-gradek)

#### [What’s new in Java 9](https://confoo.ca/en/yul2018/session/what-s-new-in-java-9)
By [Ryan Cuprak](https://confoo.ca/en/speaker/ryan-cuprak)

#### [How to leverage WebSocket in the real world](https://confoo.ca/en/yul2018/session/how-to-leverage-websocket-in-the-real-world)
By [Andrew Lombardi](https://confoo.ca/en/speaker/andrew-lombardi)

#### [Practical tools for Web Accessibility testing](https://confoo.ca/en/yul2018/session/practical-tools-for-web-accessibility-testing)
By [Toufic Sbeiti](https://confoo.ca/en/speaker/toufic-sbeiti)

#### [Être pragmatique](https://confoo.ca/en/yul2018/session/etre-pragmatique)
By [Henri Tremblay](https://confoo.ca/en/speaker/henri-tremblay)

### 14:00-14:45

#### [360° Monitoring of Your PHP Application](https://confoo.ca/en/yul2018/session/36-monitoring-of-your-php-application)
By [Philipp Krenn](https://confoo.ca/en/speaker/philipp-krenn)

#### [How to onboard a junior developer](https://confoo.ca/en/yul2018/session/how-to-onboard-a-junior-developer)
By [Christophe Philemotte](https://confoo.ca/en/speaker/christophe-philemotte)

#### [Caching in Applications Still Matters!](https://confoo.ca/en/yul2018/session/caching-in-applications-still-matters-1)
By [Anthony Dahanne](https://confoo.ca/en/speaker/anthony-dahanne)

#### [To SQL or NoSQL, That Is the Question](https://confoo.ca/en/yul2018/session/to-sql-or-nosql-that-is-the-question)
By [David Ostrovsky](https://confoo.ca/en/speaker/david-ostrovsky)

#### [Improve Cookie-based Session with Decorator Pattern](https://confoo.ca/en/yul2018/session/improve-cookie-based-session-with-decorator-pattern)
By [Weihang Jian](https://confoo.ca/en/speaker/weihang-jian)

#### [Moving from legacy to event-driven with Kafka](https://confoo.ca/en/yul2018/session/moving-from-legacy-to-event-driven-with-kafka)
By [Jeroen v.d. Gulik](https://confoo.ca/en/speaker/jeroen-v-d-gulik)

#### [En quoi le Big Data et l'I.A. sont révolutionnaires ?](https://confoo.ca/en/yul2018/session/en-quoi-le-big-data-et-l-i-a-sont-revolutionnaires)
By [Laurent Magnin](https://confoo.ca/en/speaker/laurent-magnin)

#### [Fn Project, an open source Java friendly serverless platform](https://confoo.ca/en/yul2018/session/fn-project-an-open-source-java-friendly-serverless-platform)
By [David Delabassee](https://confoo.ca/en/speaker/david-delabassee)

#### [NuGet beyond Hello World](https://confoo.ca/en/yul2018/session/nuget-beyond-hello-world-1)
By [Maarten Balliauw](https://confoo.ca/en/speaker/maarten-balliauw)

### 15:00-15:45

#### [Monitoring Jenkins -- Someone has to watch over the Butler!](https://confoo.ca/en/yul2018/session/monitoring-jenkins-someone-has-to-watch-over-the-butler)
By [Tom Chavez](https://confoo.ca/en/speaker/tom-chavez)

#### [How to build your own CDN](https://confoo.ca/en/yul2018/session/how-to-build-your-own-cdn)
By [Leonard Teo](https://confoo.ca/en/speaker/leonard-teo)

#### [PHP 7.2: Onward and Upwards](https://confoo.ca/en/yul2018/session/php-7-2-onward-and-upwards)
By [John Coggeshall](https://confoo.ca/en/speaker/john-coggeshall)

#### [WordPress Code Security](https://confoo.ca/en/yul2018/session/wordpress-code-security)
By [Stéphane Boisvert](https://confoo.ca/en/speaker/stephane-boisvert)

#### [The Growing Importance of Optimizing for UC Browser](https://confoo.ca/en/yul2018/session/the-growing-importance-of-optimizing-for-uc-browser)
By [Jennifer Lin](https://confoo.ca/en/speaker/jennifer-lin)

#### [Navigate All the Knowledge](https://confoo.ca/en/yul2018/session/navigate-all-the-knowledge)
By [James Weaver](https://confoo.ca/en/speaker/james-weaver)

#### [Modern Engineer’s troubleshooting tools, techniques & tricks](https://confoo.ca/en/yul2018/session/modern-engineer-s-troubleshooting-tools-techniques-tricks)
By [Ram  Lakshmanan](https://confoo.ca/en/speaker/ram-lakshmanan-1)

#### [MariaDB ColumnStore - An Open Source Analytics Solution](https://confoo.ca/en/yul2018/session/mariadb-columnstore-an-open-source-analytics-solution)
By [Jonathan Day](https://confoo.ca/en/speaker/jonathan-day)

#### [ASP.NET in Linux and Windows containers](https://confoo.ca/en/yul2018/session/asp-net-in-linux-and-windows-containers)
By [Rob Richardson](https://confoo.ca/en/speaker/rob-richardson)

### 16:00-16:45

#### [What is Domain Driven Design and Why it Matters](https://confoo.ca/en/yul2018/session/what-is-domain-driven-design-and-why-it-matters)
By [Pierre-Luc Maheu](https://confoo.ca/en/speaker/pierre-luc-maheu)

#### [Workers of the world, unite!](https://confoo.ca/en/yul2018/session/workers-of-the-world-unite)
By [Gleb Bahmutov](https://confoo.ca/en/speaker/gleb-bahmutov)

#### [Security boot camp for .NET developers](https://confoo.ca/en/yul2018/session/security-boot-camp-for-net-developers-1)
By [Philippe Arteau](https://confoo.ca/en/speaker/philippe-arteau)

#### [Reactive data: Stop blocking with Spring Data & Reactive DBs](https://confoo.ca/en/yul2018/session/reactive-data-stop-blocking-with-spring-data-reactive-dbs)
By [Mark Heckler](https://confoo.ca/en/speaker/mark-heckler)

#### [Help! My boss says I need to learn data science!](https://confoo.ca/en/yul2018/session/help-my-boss-says-i-need-to-learn-data-science-1)
By [Susan Ibach](https://confoo.ca/en/speaker/susan-ibach)

#### [Au-delà du top 10 de l’OWASP](https://confoo.ca/en/yul2018/session/au-dela-du-top-aa-de-l-owasp)
By [Gérôme Dieu](https://confoo.ca/en/speaker/gerome-dieu)

#### [The Big C in CSS](https://confoo.ca/en/yul2018/session/the-big-c-in-css)
By [Jen Kramer](https://confoo.ca/en/speaker/jen-kramer)

#### [Heads down to Heads Up, Transitioning to Leadership for Devs](https://confoo.ca/en/yul2018/session/heads-down-to-heads-up-transitioning-to-leadership-for-devs)
By [Newman Hunter](https://confoo.ca/en/speaker/newman-hunter)

#### [Using Ruby's Marshal module to checkpoint tasks](https://confoo.ca/en/yul2018/session/using-ruby-s-marshal-module-to-checkpoint-tasks)
By [Ken Coar](https://confoo.ca/en/speaker/ken-coar-1)

## Friday

### 09:00-09:45

#### [JavaScript State of the Union](https://confoo.ca/en/yul2018/session/javascript-state-of-the-union)
By [Jordi Boggiano](https://confoo.ca/en/speaker/jordi-boggiano)

#### [TypeScript for JavaScript developers](https://confoo.ca/en/yul2018/session/typescript-for-javascript-developers-1)
By [Christopher Harrison](https://confoo.ca/en/speaker/christopher-harrison)

#### [Your Views Know Too Much](https://confoo.ca/en/yul2018/session/your-views-know-too-much)
By [Jason Charnes](https://confoo.ca/en/speaker/jason-charnes)

#### [Distributed Stream Data Processing](https://confoo.ca/en/yul2018/session/distributed-stream-data-processing)
By [David Ostrovsky](https://confoo.ca/en/speaker/david-ostrovsky)

#### [Cassandra - how to fail?](https://confoo.ca/en/yul2018/session/cassandra-how-to-fail)
By [Michał Matłoka](https://confoo.ca/en/speaker/michal-matloka)

#### [Tales from the wrong end](https://confoo.ca/en/yul2018/session/tales-from-the-wrong-end)
By [Marcus Bointon](https://confoo.ca/en/speaker/marcus-bointon)

#### [Deploy Scalable and Secure Applications with Kubernetes](https://confoo.ca/en/yul2018/session/deploy-scalable-and-secure-applications-with-kubernetes)
By [Brent Shaffer](https://confoo.ca/en/speaker/brent-shaffer)

#### [We all benefit from Accessibility, said a Netflix fan](https://confoo.ca/en/yul2018/session/we-all-benefit-from-accessibility-said-a-house-of-cards-fan)
By [Toufic Sbeiti](https://confoo.ca/en/speaker/toufic-sbeiti)

#### [Escape from Jar Hell (with Java 9 Modularity)](https://confoo.ca/en/yul2018/session/escape-from-jar-hell-with-java-9-modularity-1)
By [Nick Maiorano](https://confoo.ca/en/speaker/nick-maiorano)

### 10:00-10:45

#### [Developing cacheable PHP applications](https://confoo.ca/en/yul2018/session/developing-cacheable-php-applications)
By [Thijs Feryn](https://confoo.ca/en/speaker/thijs-feryn)

#### [10 things the media hasn't told you about React Native](https://confoo.ca/en/yul2018/session/10-things-the-media-hasn-t-told-you-about-react-native)
By [Nicolas Cuillery](https://confoo.ca/en/speaker/nicolas-cuillery)

#### [Curious about DevOps? You've got the right attitude!](https://confoo.ca/en/yul2018/session/curious-about-devops-you-ve-got-the-right-attitude)
By [Olivier Gourment](https://confoo.ca/en/speaker/olivier-gourment)

#### [A DIY Data Lake and Lab](https://confoo.ca/en/yul2018/session/a-diy-data-lake-and-lab)
By [Christophe Philemotte](https://confoo.ca/en/speaker/christophe-philemotte)

#### [Alexa, let's make a skill](https://confoo.ca/en/yul2018/session/alexa-let-s-make-a-skill)
By [Michael Peacock](https://confoo.ca/en/speaker/michael-peacock)

#### [Comment répondre plus rapidement à vos clients avec l'IA](https://confoo.ca/en/yul2018/session/comment-repondre-plus-rapidement-a-vos-clients-avec-l-ia)
By [Michael Gradek](https://confoo.ca/en/speaker/michael-gradek)

#### [Mutation Testing to the rescue of your Tests](https://confoo.ca/en/yul2018/session/mutation-testing-to-the-rescue-of-your-tests)
By [Nicolas Fränkel](https://confoo.ca/en/speaker/nicolas-fraenkel)

#### [CQRS & Event Sourcing in the wild](https://confoo.ca/en/yul2018/session/cqrs-event-sourcing-in-the-wild)
By [Michiel Rook](https://confoo.ca/en/speaker/michiel-rook)

#### [Vertical Feature Slices, not Layers!](https://confoo.ca/en/yul2018/session/vertical-feature-slices-not-layers)
By [Derek Comartin](https://confoo.ca/en/speaker/derek-comartin)

### 11:00-11:45

#### [Event driven development](https://confoo.ca/en/yul2018/session/event-driven-development)
By [Christopher Riley](https://confoo.ca/en/speaker/christopher-riley)

#### [Unbreakable unit tests](https://confoo.ca/en/yul2018/session/unbreakable-unit-tests-1)
By [Michael Simonson](https://confoo.ca/en/speaker/michael-simonson-1)

#### [AMA: I'm a Seed Stage VC](https://confoo.ca/en/yul2018/session/i-m-a-seed-stage-vc-investing-in-ai-startups-ask-me-anything)
By [Sylvain Carle](https://confoo.ca/en/speaker/sylvain-carle)

#### [Building truly Universal apps with Azure, Xamarin and MVVM](https://confoo.ca/en/yul2018/session/building-truly-universal-apps-with-azure-xamarin-and-mvvm)
By [Laurent Bugnion](https://confoo.ca/en/speaker/laurent-bugnion)

#### [Anatomy of a Web Request](https://confoo.ca/en/yul2018/session/anatomy-of-a-web-request)
By [Rob Richardson](https://confoo.ca/en/speaker/rob-richardson)

#### [PHP PSR-7 HTTP messages in the wild](https://confoo.ca/en/yul2018/session/php-psr-7-http-messages-in-the-wild)
By [Hannes Van De Vreken](https://confoo.ca/en/speaker/hannes-van-de-vreken)

#### [Use Positive Communication, Increase Positive Results!](https://confoo.ca/en/yul2018/session/use-positive-communication-increase-positive-results)
By [Sonia Di Maulo](https://confoo.ca/en/speaker/sonia-di-maulo-1)

#### [New Features in MariaDB 10.2 and 10.3](https://confoo.ca/en/yul2018/session/new-features-in-mariadb-10-2-and-10-3)
By [Jonathan Day](https://confoo.ca/en/speaker/jonathan-day)

#### [The easiest way to secure your JAM Stack apps user data](https://confoo.ca/en/yul2018/session/the-easiest-way-to-secure-your-jam-stack-apps-user-data)
By [Adam L Barrett](https://confoo.ca/en/speaker/adam-l-barrett)

### 13:00-13:45

#### [Building Cross Platform Progressive Web Apps](https://confoo.ca/en/yul2018/session/building-cross-platform-progressive-web-apps)
By [Simon MacDonald](https://confoo.ca/en/speaker/simon-macdonald)

#### [Dive deep into blockchain](https://confoo.ca/en/yul2018/session/dive-deep-into-blockchain)
By [Tomasz Kowalczyk](https://confoo.ca/en/speaker/tomasz-kowalczyk-1)

#### [Advanced CSS tricks and techniques](https://confoo.ca/en/yul2018/session/advanced-css-tricks-and-techniques-1)
By [Robert Richelieu](https://confoo.ca/en/speaker/robert-richelieu-1)

#### [Le moteur de template, un nouveau vecteur d'attaque](https://confoo.ca/en/yul2018/session/le-moteur-de-template-un-nouveau-vecteur-d-attaque)
By [Gérôme Dieu](https://confoo.ca/en/speaker/gerome-dieu)

#### [We're doing it all wrong](https://confoo.ca/en/yul2018/session/we-re-doing-it-all-wrong)
By [Sebastien Lambla](https://confoo.ca/en/speaker/sebastien-lambla)

#### [Sylius, un framework e-commerce basé sur Symfony](https://confoo.ca/en/yul2018/session/sylius-un-framework-e-commerce-base-sur-symfony)
By [Mikael Randy](https://confoo.ca/en/speaker/mikael-randy)

#### [PostgreSQL gotchas for app developers](https://confoo.ca/en/yul2018/session/postgresql-gotchas-for-app-developers)
By [Magnus Hagander](https://confoo.ca/en/speaker/magnus-hagander)

#### [Building and running a website at scale with a team of one](https://confoo.ca/en/yul2018/session/building-and-running-a-website-at-scale-with-a-team-of-one)
By [Geoffrey Goodman](https://confoo.ca/en/speaker/geoffrey-goodman)

#### [Infinately Scalable .NET Web Services](https://confoo.ca/en/yul2018/session/infinately-scalable-net-web-services)
By [Newman Hunter](https://confoo.ca/en/speaker/newman-hunter)

### 14:00-14:45

#### [Security and Privacy in a National Security World](https://confoo.ca/en/yul2018/session/security-and-privacy-in-a-national-security-world)
By [Ben Dechrai](https://confoo.ca/en/speaker/ben-dechrai)

#### [So, what’s new in ES2020?](https://confoo.ca/en/yul2018/session/so-what-s-new-in-es2-2)
By [Christophe Porteneuve](https://confoo.ca/en/speaker/christophe-porteneuve)

#### [MJML, le nouveau standard pour écrire nos emails ?](https://confoo.ca/en/yul2018/session/mjml-le-nouveau-standard-pour-ecrire-nos-emails)
By [Thomas Deneulin](https://confoo.ca/en/speaker/thomas-deneulin)

#### [Machine Data Is EVERYWHERE: Use It for Testing!](https://confoo.ca/en/yul2018/session/machine-data-is-everywhere-use-it-for-testing)
By [Tom Chavez](https://confoo.ca/en/speaker/tom-chavez)

#### [Bruce Lee Driven Development](https://confoo.ca/en/yul2018/session/bruce-lee-driven-development)
By [Jeroen v.d. Gulik](https://confoo.ca/en/speaker/jeroen-v-d-gulik)

#### [Advanced State Management using new ngrx v5](https://confoo.ca/en/yul2018/session/advanced-state-management-with-ngrx)
By [Gerard Sans](https://confoo.ca/en/speaker/gerard-sans)

#### [Become a garbage collection hero](https://confoo.ca/en/yul2018/session/become-a-garbage-collection-hero)
By [Ram  Lakshmanan](https://confoo.ca/en/speaker/ram-lakshmanan-1)

#### [Understanding Product Management](https://confoo.ca/en/yul2018/session/understanding-product-management)
By [Sean Yo](https://confoo.ca/en/speaker/sean-yo)

#### [Azure 101](https://confoo.ca/en/yul2018/session/azure-101)
By [Laurent Bugnion](https://confoo.ca/en/speaker/laurent-bugnion)

### 15:00-15:45

#### [CSS Grid: True Layout Finally Arrives](https://confoo.ca/en/yul2018/session/css-grid-true-layout-finally-arrives)
By [Jen Kramer](https://confoo.ca/en/speaker/jen-kramer)

#### [Learning Machine Learning](https://confoo.ca/en/yul2018/session/learning-machine-learning)
By [Joel Lord](https://confoo.ca/en/speaker/joel-lord)

#### [Services Assemble! How to Create Microservices Without Chaos](https://confoo.ca/en/yul2018/session/services-assemble-how-to-create-microservices-without-chaos)
By [Mark Heckler](https://confoo.ca/en/speaker/mark-heckler)

#### [Bulk Automated Image Manipulation with Bash and ImageMagick](https://confoo.ca/en/yul2018/session/bulk-automated-image-manipulation-with-bash-and-imagemagick)
By [Jean-Luc David](https://confoo.ca/en/speaker/jean-luc-david-1)

#### [Building Self Describing Web APIs](https://confoo.ca/en/yul2018/session/building-self-describing-web-apis)
By [Derek Comartin](https://confoo.ca/en/speaker/derek-comartin)

#### [Mental Health: Lessons Learned and Tips and Tricks](https://confoo.ca/en/yul2018/session/mental-health-lessons-learned-and-tips-and-tricks)
By [Stéphane Boisvert](https://confoo.ca/en/speaker/stephane-boisvert)

#### [A Fist Full Of Data: The Rise of Overindulgent Mobile Data](https://confoo.ca/en/yul2018/session/a-fist-full-of-data-the-rise-of-overindulgent-mobile-data)
By [Henri Helvetica](https://confoo.ca/en/speaker/henri-helvetica)

#### [Building Horizontally Scalable Laravel 5.6 applications](https://confoo.ca/en/yul2018/session/building-horizontally-scalable-laravel-5-6-applications)
By [John Coggeshall](https://confoo.ca/en/speaker/john-coggeshall)

#### [Ruby on Rails Anti-Patterns (How Not to Design your DB)](https://confoo.ca/en/yul2018/session/ruby-on-rails-anti-patterns-how-not-to-design-your-db)
By [Brad Urani](https://confoo.ca/en/speaker/brad-urani)
