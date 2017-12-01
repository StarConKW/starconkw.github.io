---
layout: page
title: Talks
permalink: /talks/
---

<div class="pretty-links">

# StarCon Talk Lineup

There will be 2 keynotes and 20 lightning talks at StarCon. The full lineup and order/schedule will be announced soon!

## Keynotes

### So you want to be a wizard?

[Julia Evans](/speakers#julia-evans)

<p class="abstract">
I don't always feel like a wizard. I'm not the most experienced member on my team, like most people I sometimes find my work difficult, and I still have a TON TO LEARN.
</p>

<p class="abstract">
But along the way, I have learned a few ways to debug tricky problems, get the information I need from my colleagues, and get my job done. We're going to talk about
</p>

- how asking dumb questions is actually a superpower
- how you can read the source code to programs when all other avenues fail
- debugging tools that make you FEEL like a wizard
- and how understanding what your _organization_ needs can make you amazing

<p class="abstract">
At the end, we'll have a better understanding of how you can get a lot of awesome stuff done even when you're not the highest level wizard on your team.
</p>

## Lightning talks

### Remembering MegaZeux: Concurrent, Assembly-ish Actor-based Programming for Teens

[Josh Bowman-Matthews](/speakers#josh-bowman-matthews)

<p class="abstract">
Investigating programming languages that never went mainstream can help us better appreciate the subtle trade-offs that are required when designing a programming language. In "Remembering MegaZeux: Concurrent, Assembly-ish Actor-based Programming for Teens", we will focus on one such language in particular. In 1994, a small community of teenagers started using Robotic: an unusual, forward-thinking programming language intended for creating computer games inside the game creation system MegaZeux. We’ll examine the design of Robotic and how it compared to academic research and industrial practice at the time, as well as how it reflects current trends and practices. We’ll contemplate the unorthodox choices that Robotic made and how these helped position it as a viable introduction to programming for so many aspiring game developers. Through these examples and comparisons we will better appreciate the broad scope in programming language design that exists outside of the languages that we most commonly experience.
</p>

### The Innerworkings of Ransomware

[Dinah Davis](/speakers#dinah-davis)

<p class="abstract">
This past year was all about large Ransomware hacks like WannaCry, Petya/NotPetya, and CRYPSHED to name a few. In this talk Dinah will detail how it works, how to avoid it, and what is coming next in the world of Ransomware. She will also demonstrate what happens when ransomware is exploded on a computer from the Arctic Wolf labs.
</p>

### Notworking with a Whale: A Tale of Dockers, Networks, and Problem Solving

[Fatema Boxwala](/speakers#fatema-boxwala)

<p class="abstract">
Docker has become an extremely popular tool in the tech industry. Docker containers can be found playing a hugely important role in the infrastructure of companies from the tiniest startup to the giantest of the giants. Despite it's ubiquity, much of the inner-workings of Docker remain shrouded in mystery for developers, even for some people that work with the application regularly.  And a lot of the times, the only way to figure out what's going on is by experimenting and testing yourself. One particularly confusing aspect of Docker, and linux containers in general, is how exactly the networking inside the container works. In my talk: Notworking with a Whale: A Tale of Dockers, Networks, and Problem Solving, I will be giving a short but practical introduction to networking inside Docker and linux containers. The audience will first be introduced to the idea of network namespaces inside linux systems, and how these apply to containers and Docker. They will then be exposed to tools that can be used to interact with and troubleshoot networking issues inside a container. I will introduce these tools by sharing my own, very frustrating, experience with networking and Docker, in a problem-strategy-solution narrative. My talk will present information that will teach listeners information about linux containers, and offer some personal strategies and tools that have worked well for me.
</p>


### Gloom, Doom, and the Internet

[Keefer Rourke](/speakers#keefer-rourke)

<p class="abstract">
Since the advent of the internet, technology has undergone a revolution like no other. It has enabled connectivity on a scale that has never been seen before, enabling free distribution of information, ideas, and independent content. However, in recent years we've seen a turn of events. What was once primarily a mechanism for free expression has given way to multitudes of surveillance machines designed to track your every move. In my talk "Gloom, Doom, and the Internet," I will discuss some of the privacy and security issues with technology today, and explain how you can defend the users of your Next Big Thing(tm). Attendees will be encouraged to rethink how they view internet-enabled technology, with a focus on the importance of privacy, accessibility, and security oriented designs from day one, and they will be shown how new platforms can be made successful simply by respecting their users.
</p>

### Why I Prefer Good Testing Over Excellent Testing

[Tina Fletcher](/speakers#tina-fletcher)

<p class="abstract">
I often used to feel that if we only had more time for testing, we’d find all the bugs and everything would be awesome. But the longer I’ve been working on software projects, the more times I’ve seen that this might not be true. Most of the escaped defects in my recent memory were hiding in the areas I didn’t even know to ask about, in the small differences between our test and production environments, and in the things we depend on but don’t have full control over. So lately, while I will always value doing good testing, it doesn’t feel as useful to spend a lot of time striving for truly excellent coverage. Instead, I prefer to invest in planning for phased roll outs, and gaining confidence in our ability to quickly detect and resolve problems in production. I’d like to share a few stories about defects I missed that I wouldn’t have found with all the time in the world, and about times I have been saved by solid monitoring and roll-back strategies.
</p>

### Formal Methods for Everyone: Practical Tools for Computer-Aided Reasoning

[Murphy Berzish](/speakers#murphy-berzish)

<p class="abstract">
Do you want to write code you can be confident in, and test your programs thoroughly? Formal methods is a powerful discipline of software engineering that uses logic and automated reasoning to prove correctness of programs or find counterexamples to assertions.
<br/><br/>
In this talk, I will describe two useful open source tools that you can start using to help you write better code and find more bugs in your software. I will teach you about the Z3 theorem prover, from Microsoft Research, which can assist you in reasoning about logical formulas and finding test cases to catch bugs. Then, I will talk about the KLEE symbolic execution engine, which is an automated software testing tool that uses principles from formal methods to explore the effects that different inputs have on the flow of your program.
<br/><br/>
This talk will be very applied, with an emphasis on the practical rather than the theoretical. I want this talk, as well as these tools, to be accessible to anyone, even with no background in formal logic.
</p>

### How to make a real-time collaborative text editor in 5 easy steps!

[Rudi Chen](/speakers#rudi-chen)

<p class="abstract">
With the rise of cloud applications, more and more software is becoming collaborative. That is, multiple people can be viewing and editing the same document or information at the same time. This can lead to tricky issues figuring out what the end result should be when two users simultaneously do conflicting operations (e.g. in Google Docs, two users typing in the same place). The conflict-resolution algorithms so solve these problems are increasingly important, but selfdom mentioned in any curriculum. This talk will present a newer approach to build a collaborative text editor easier to understand than common techniques found on the Internet. The technique will be presented one small layer of complexity at the time, such that at every step, the audience can get an intuition for the nature of the solution and be easily be convinced that it works. I’ll also make sure to un-dry the technical aspects talk by using humor and analogies to kiwis and water buffalos.
</p>


### I'm a scientist!

[Omayeli Arenyeka](/speakers#omayeli-arenyeka)

<p class="abstract">
In the 6th grade we were taught the Scientific method. We would ask a question, form a hypothesis, conduct an experiment and then analyze the results and come up with a conclusion. The results, if unambiguous, proved us right or wrong. After I took my last science class in high school, I stopped conducting experiments. If I got curious about something or had a question, I would do research. However, some of the questions I had couldn’t be answered by googling or buying a book. 2 years ago I discovered how I could be a “scientist” without literally being one. In my talk, “I’m a scientist!” I’m going to talk about answering our own questions through data exploration and visualization. I will take the audience through one of my visualization projects at each step of the scientific method. They will be introduced to methods of obtaining data, techniques for data analysis and a brief introduction to data visualization. I believe that everyone should be able to analyze and do basic visualizations of data so we don’t always rely on outside sources (which often are biased) to make conclusions about the world we live in.
</p>


### Dealing with Bad Architecture Decisions: A Case Study

[Claire Janke](/speakers#claire-janke)

<p class="abstract">
Have you ever worked on a project for several months, only to realize right before the end date that there’s a fundamental flaw in your approach? In this talk I’ll tell the story of how our team built a new data management system which started as a fairly straightforward Elasticsearch index but then at the last minute evolved into a Frankenstein-esque database + search index hybrid that is still in use today. I'll also point out where it all went wrong to hopefully help others avoid the same mistakes in the future.
</p>



### Why Lossless Data Compression Is Both Important and Fun

[Alex Rhatushnyak](/speakers#alex-rhatushnyak)

<p class="abstract">
Data compression is highly important for reducing storage costs and transmission times. More than 70% of global Internet traffic is video, and it's compressed video as a rule. Similarly, audio and images more often travel in compressed form. Lossless data compression (LDC) is an important part of a data compression system. Advanced LDC is an application of Data Science and Machine Learning, but basic LDC methods are so simple that you can implement them with zero or little knowledge of ML, DS and even Computer Science. The audience of my talk "Why Lossless Data Compression Is Both Important and Fun" will be introduced to the topic and learn several of the most vital principles. LDC competitions and benchmarks will be pictured as well, with practical advices on how to win thousands of dollars in such competitions. LDC is closely related to the notions of descriptive complexity and entropy. LDC methods can be applied for estimating descriptive complexity, for measuring similarity between files, and so on. At the end of the talk a couple of next big things (supposedly related to descriptive complexity and LDC) will be briefly discussed.
</p>


### Imagining a world with Ethereum

[Anastasia Santasheva](/speakers#anastasia-santasheva)

<p class="abstract">
Cryptocurrencies such as Bitcoin, Ethereum, and others have recently become (in)famous in the news. In my talk, "Imagining a world with Ethereum", I will explore Ethereum's fundamentals by contrasting it with Bitcoin. Then I will show why this technology is powerful and what projects have been established in this space. I'll discuss their impact and lessons learned (especially surrounding hacks and governance), and explore what comes next. Ultimately, I will show you that we need everyone to understand and be involved in cryptocurrency to build a financial system 2.0 (or else someone else will build it for us)!
</p>


### Taking the Fun Out of Everything: Automating Neopets

[Kelly McBride](/speakers#kelly-mcbride)

<p class="abstract">
Neopets is probably one of the Web 1.0’s greatest achievements. The fact that it was created during that time means that its original features rely on older technology that’s more commonly understood now, making it a prime target for automation at the hands of junior programmers. Neopets is a browser game about taking care of virtual pets. Fortunately, it’s comprised of php activities that you interact with by making HTTP requests - something that scripts are great at doing as well as browsers. In my talk, “Taking the Fun Out of Everything: Automating Neopets,” I’ll talk about collaborating with the ghosts of people with similar ideas by forking their abandoned repos, building on frameworks with the aim of applying more technical ideas later, and banging your head against the wall when “they could have just made the game do this.” I’ll close by mentioning some similar games that the audience can take the fun out of for themselves.
</p>


### Of Tracked Changes and Diffs: Moving from Editorial to Engineering

[Breanne Boland](/speakers#breanne-boland)

<p class="abstract">
I worked in online content in varying capacities for more than a decade before I made the shift to software engineering. While my ability to communicate verbally and in writing were early helpers as I completed this transition, the lessons I learned from editorial life were also surprisingly helpful. It turned out that years of workshopping stories, trading edits, laboring over drafts, and seeking buy-in and input are directly applicable to surviving and thriving in code reviews.
<br/><br/>
By the time I was writing my own code, I’d long since divorced my ego from the things I wrote, and it prepared me for my first code reviews. I had learned that solo work is typically incomplete until you get input from someone else in the form of edits or feedback, and that collaboration is what usually enables people to do their best work and learning. I also knew that getting feedback at the right time can be almost as important as getting the right feedback and that processes can make or break a project, no matter how talented those involved are. I’ll conclude with ways that people without editorial backgrounds can bring these lessons into their own work life.
</p>

### Managing Connections with Graphs: Uses and Challenges

[Siddhartha Sahu](/speakers#siddhartha-sahu)

<p class="abstract">
Connections in social networks, financial transactions, and interactions between proteins are just a few examples of real-world data that can be intuitively represented as graphs. In my talk “Managing Connections with Graphs: Uses and Challenges”, I will examine the rising relevance of graph software in managing highly interconnected data. While graph processing is not a new technology, there has been a recent surge of interest in exploring connections in data as a graph, not only for familiar entities such as social data representing friends and what they like but also for entities that are not naturally thought of as graphs. The audience will develop an appreciation for how thinking in terms of graphs helps develop a better understanding of interconnected data. While there are a plethora of graph software in use, these software do not meet all the feature requirements arising from across a variety of domains. The audience will learn about the primary challenges in graph processing and opportunities for developing new ideas and techniques. Graph processing will become increasingly important in the coming years and it is definitely an exciting time to work on graph technology.
</p>


### Remote code execution in your text editor!

[Max Veystman](/speakers#max-veystman)

<p class="abstract">
Text editors do a lot more than just edit characters in a buffer. Whether you use vim, emacs, submile text, atom, or something else, you probably configured your editor to highlight syntax, provide auto-completions, jump to defintions, and maybe even evaluate code. These plugins often spawn processes that evaluate code alongside your editor, and sometimes they even make and receive network connections. What if you could hack them?
<br/><br/>
In my talk, I'll describe a vulnerability in the Vim plugin for the Elixir programming language and show an exploit I wrote that allows any website to execute code on your computer if you browse it while editing an Elixir file.
<br/><br/>
P.S. if you're reading this abstract and use Elixir and Vim, you should upgrade alchemist.vim as soon as possible!
</p>

### Protecting cryptography code from timing vulnerabilities

[Tim McLean](/speakers#tim-mclean)

<p class="abstract">
It's well-known that cryptography code is hard to get right.  Small mistakes often have disproportionately large consequences, like handing an attacker your encryption keys.
<br/><br/>
One key category of pitfalls that cryptography engineers face are timing leaks.  When a program runs on a computer, it subtly but measurably interferes with the performance of other processes.  Cryptography code must ensure that these interference patterns do not reveal sensitive information to attackers.
<br/><br/>
This talk is about the challenges of protecting code from timing leaks.  We will start with an example timing vulnerability and show how to exploit it, then proceed to look at how the obvious ways of fixing the problem are not good enough.  Finally, we will look at a particular style of coding that, as far as we know, prevents all timing leaks on x86 processors... except when your compiler "optimizes" your code by adding vulnerabilities.
</p>


### Undoing the Chatbot

[Erika Pierre](/speakers#erika-pierre)

<p class="abstract">
In this talk, we’ll be taking a look at the history and present of chatbots and digital personal assistants in English-speaking North America from a technological and social perspective. Whether we're looking at virtual assistant bots, Facebook Messenger bots, or Slackbots, what do we expect from our bots, and why? What else can we imagine for and with our bots?
<br/><br/>
One of the benefits of open web technologies is that rather than waiting for Siri and Alexa to come around, we can work through these issues ourselves!
<br/><br/>
First, we’ll learn a little bit about the Speech Recognition and Speech Synthesis Web APIs. Then, we’ll walk through a small project, relying only on front-end web technologies, that lets us explore the underutilized possibilities of chatbots. Whether they're talking back in unexpected ways or using the user’s expected emotional responses against them, we'll unravel understandings of what a chatbot is, who it's for, and the assumptions it relies on in order to function undetected.
</p>

### How giant human-powered calculators became the internet

[Andrew Louis](/speakers#andrew-louis)

<p class="abstract">
Once upon a time, a "computer" was literally a large room filled with hundreds of workers hunched over desks doing math. Almost a century later, we’ve arrived at the internet but what we have now was by no means inevitable.
<br/><br/>
Our story begins in a time in a time when newly-created digital computers were thought of as mere calculators, useful for analyzing missile trajectories or administrating payroll. Engineer Vannevar Bush, crushed by a deluge of memos and documents arriving on his desk each day, wondered if computers could help. He invented the Memex, most notably recognizing hyperlinks as a way to navigate through complex data.
<br/><br/>
Exactly zero of these devices were ever built but a magazine published his idea and this was picked up by a bored soldier stationed in a remote WW2 base. Douglas Engelbart took the ideas of the Memex and used it to guide his work, culminating in an incredible 1968 demo that showcased what computers could be made to do.
<br/><br/>
When it came time to get these computers to start talking to each other, he enlisted the help of Elizabeth Feinler. She came up with a lot of the Internet’s first processes, most notably the system which became DNS. She also ensured all discussions and decisions about protocols were carried out in the open.
<br/><br/>
These are just three stories in the complicated history of a complicated system but they illustrate how the values, ideas, priorities of individuals can shape the future.
</p>


### Introduction to Software Defined Radios

[Jordan Pryde](/speakers#jordan-pryde)

<p class="abstract">
Software Defined Radios (SDR) are devices that implement the components of a radio, that have been traditionally implemented in hardware, with more flexible software. These components include mixers, filters, modulators and demodulators. In my talk I will introduce the audience to the concept of SDRs and other basic radio concepts, describe some cool projects that are only made possible with SDRs (with possible demo videos; time permitting), and finally how easy it is to purchase and get started playing with SDRs. I will also introduce the audience to Amateur Radio which provides both some spectrum they would be licenced to play around with and access to a group of likeminded hobbyists. SDRs can be used to better understand the consumer devices that we use everyday and that sometimes can seem like magic. SDRs can also be used to inexpensively (for around $30) monitor and record the emergency response (i.e. fire, paramedics and police) and airplane traffic. Concluding my presentation, I will walk though today’s SDR market and make suggestions of what to buy for those both new and experienced with SDRs. I believe this technology is so cool because it both allows us to demystify the radio-controlled electronics we use everyday and can enable us to be better connected to our communities.
</p>
