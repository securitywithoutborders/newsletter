# Newsletter #2

Welcome to the second newsletter from Security Without Borders. This is a somewhat regular newsletter covering recent cyber security issues, tools and events relevant for activists, dissidents, journalists and civil society at large.

> **Security Tip**: No matter how secure your password is, it takes one convincing phishing email for an attacker to steal it. It is therefore vital that you protect all your important online accounts with two-factor authentication. The Electronic Frontier Foundation (EFF) has published [a series of blog posts](https://www.eff.org/deeplinks/2016/12/12-days-2fa-how-enable-two-factor-authentication-your-online-accounts) about how to do that for various popular services, including Facebook, Twitter and Gmail.

This newsletter is an experiment. Please let us know if you enjoy it and suggest us any content you would like to see here either via [Twitter](https://twitter.com/swborders) or via [email](mailto:info@securitywithoutborders.org).


## Editorial

This issue of the Security Without Borders newsletter comes a bit later than when originally expected, with no critical security alerts, but rich with informative reading as numerous reports were published in the last weeks that are relevant to security threats to civil society.

This second issue has a somewhat unintended focus on phishing attacks, mainly due to the coincidental high number of reports related to such attacks published in the last few weeks. Phishing is a type of attack designed to steal credentials of online accounts (most commonly Gmail, but at times also Facebook, Twitter, Apple and more) by luring victims into typing their password in a illegitimate clone of the original service. The reports published recently demonstrate that the attention to details and effort invested by attackers using phishing is increasingly remarkable. Phishing is a very present and concerning issue, especially widely used against journalists and activist communities.

This edition's Tools section is also rich of new (and old) releases, with a continued focus on solutions to minimize the risk of phishing. We're also announcing the _beta_ release of a little utility of our own production, [Hardentools](https://github.com/securitywithoutborders/hardentools), which we invite you to check out. Among the other highlights you'll find anti-phishing browser extensions and a censorship detection mobile app!

Thanks to all those who helped compile this newsletter, Martijn in particular.

Enjoy the reading and stay safe.

    Claudio "nex" Guarnieri
    Security Without Borders

## Informative Reading

- **Phishing against Egyptian NGOs**. Citizen Lab writes about an ongoing [phishing campaign against various Egyptian NGOs](https://citizenlab.org/2017/02/nilephish-report/). Phishing is a technique where users are lured into entering their credentials of for example email, banking or social media accounts. It affects any internet user, but is of particular concern to those targeted by powerful adversaries such as governments. In this case, as was seen in Egypt, the senders already know quite a lot about their target and use this to make the emails that contained the phishing link look very credible. Those who are likely targets of such attacks should be very wary of clicking links in emails they receive; in case of the slightest doubt, they should consult a trusted security expert. To seriously increase the bar for the adversary, two factor authentication should be used for all accounts that give access to important information.

- **Phishing against activists in Qatar and Nepal**. Researchers at Amnesty International - including Claudio and Collin from SWB - discovered a [campaign of phishing attacks against a group of people most of whom are involved in the issue of migrants’ rights in Qatar and Nepal](https://medium.com/amnesty-insights/operation-kingphish-uncovering-a-campaign-of-cyber-attacks-against-civil-society-in-qatar-and-aa40c9e08852). The attack was well planned and involved carefully crafted fake social media profiles that infiltrated thematic groups, befriended targets, and ultimately delivered the phishing attacks. Social media can be really great to meet people who care about the same cause as you do, but if you handle sensitive information you should be wary of fake profiles trying to connect. As the article puts it: if you wouldn’t share it on Twitter, don’t share information with someone you don’t know, even if it is someone who appears to have friends on social media in common with you.

- **Mac malware found used in Iran**. Claudio and Collin also wrote about [new malware that targets Apple's Mac OS X](https://iranthreats.github.io/resources/macdownloader-macos-malware/) operating system and that is written by an Iranian group. For everyone, even those not particularly concerned about Iranian actors, this serves as an important reminder that malware on OS X is a reality. Though malware targeting Windows is far more prevalent, Mac users should not consider themselves invincible and apply the same security hygiene as users of other operating systems. This especially applies to those with powerful adversaries. Another example of this was seen when [security researchers found a piece of malware, of unknown origin, that was hidden inside a Word for Mac file](https://motherboard.vice.com/en_us/article/these-hackers-cleverly-disguised-their-malware-as-a-document-about-trumps-victory). The malware would be activated when the user enabled macros. It is thus important, in Mac as much as in Windows, to never enable macros in Office files, no matter how much the document says it is needed to view hidden content.

- **NSO exploits used against Mexican activists**. CitizenLab wrote about the use of [NSO Group exploits to target the mobile devices of a number of Mexican individuals](https://citizenlab.org/2017/02/bittersweet-nso-mexico-spyware/) all of whom have campaigned for a tax on sugary drinks ("soda tax"). NSO Group malware had previously been used to target UAE-based human rights defender Ahmed Mansoor. This malware, which is exclusively sold to governments, is known to be both very powerful and very stealthy; in practice this means that the usual advice about keeping your devices and software up to date, while still important, is not always good enough. Those who suspect they could be the target of these kinds of attacks are adviced to take extreme caution and look for help locking down their devices. Advanced though the malware was, the infection techniques weren't. The targets recevied a number of SMS messages, each of which contained a link clicking on which would have infected their phone with the malware. Given the targeted nature of the campain, the messages appeared very relevant to the targets. The same technique has been used in many less sophisticated malware and phishing campaigns. It is important to err on the side of caution before opening links sent in messages. In case of doubt, contact the apparent sender of the messages through a different channel. Matters of life and death are rarely, if ever, solved by clicking on a link.

- **How to give a Security Training**. There are many great sources on the internet about improving your (digital) security, but for many people, especially the less tech-savvy among us, face to face trainings are the best way to learn about digital safety and security. Four experienced trainers have written a brief document on [how to give such security trainings](https://medium.com/@geminiimatt/how-to-give-a-digital-security-training-4c83af667d40).

- **Pseudonymous Signal**. The Signal messaging app is widely praised for its security and privacy properties. Using it should be sufficient for almost everyone who needs to care about their online security. However, a very small group of users could have reasons to be worried about the (small amount of) Metadata stored on Signal's servers. For those users, security researcher 'x0rz' published [a simple guide on how to use Tor to use Signal pseudonymously](https://blog.0day.rocks/operational-signal-d41d2c457d8d).

- **Running an anonymous Twitter account**. Micah Lee from The Intercept published an interesting guide, mainly targeted at American readers though, on [how to create and operate a Twitter account anonymously using Tor and a burner phone](https://theintercept.com/2017/02/20/how-to-run-a-rogue-government-twitter-account-with-an-anonymous-email-address-and-a-burner-phone/). Operating anonymously online can be quite difficult, especially when done in a way that attracts attention. In the past we have seen numerous cases of [attacks designed to deanonymize anonymous or pseudonymous activists on Twitter](https://bahrainwatch.org/ipspy/). Check out again the grugq's guide on [how to run a dissident Twitter account](https://medium.com/@thegrugq/twitter-activist-security-7c806bae9cb0).


## Tools

- [Hardentools](https://github.com/securitywithoutborders/hardentools) is a little Windows utility developed by Security Without Borders designed to make some simple modifications to the configuration of your Windows computer to reduce some of the attack surface that is commonly used by attackers, particularly targeting activists and dissidents. A lot of the attacks we observe use very simple tricks leveraging dangerous features of Windows and other mainstream applications (for example Office documents with Macros) to manage to execute malicious code. Claudio explained this in his blog post [On the Banality of Attacks and on Mindful Engineering](https://medium.com/@botherder/on-the-banality-of-attacks-and-on-mindful-engineering-fc0a50e5cff5). Most of these features are generally unused by most people and especially for individuals at risk they represent a liability rather than a functionality. Hardentools disables a lot of these features. Bear in mind, after running Hardentools you won't be able to do complex calculations with Microsoft Office Excel or use the Command-line terminal, but those are pretty much the only considerable "downsides" of having a safer Windows environment. Before deciding to use it, make sure you read the [README](https://github.com/securitywithoutborders/hardentools/blob/master/README.md) and understand that this is an **experimental beta** release.

- [Blockade](https://blockade.io) is an interesting Chrome extension designed to block malicious or suspicious sites blacklisted by data feeds that are configurable. We are happy to announce that Security Without Borders is now running a data feed for Blockade, meaning that your browser will receive both the public and private block lists we compile from the research and investigations we continuously conduct. While this does by no means block any attempt of phishing or compromise, it might very well at least block _some_. In order to use our data feed with Blockade, after having read the instructions and installed the extension, you need to configure it to use the cloud node at **https://blockade.securitywithoutborders.org** (notice, this is not a working webpage but an API server, so opening it in a browser won't work). We made a [short video showing how to do it](https://vimeo.com/205097462).

- [Password Alert](https://chrome.google.com/webstore/detail/password-alert/noondiphcddnnabmjcihcjfbhfklnnep?hl=en) is yet another interesting Chrome extension developed by Google, which should alert you whenever you might have fallen victim of a phishing attack attempting to steal your Google Account credentials. We have not thoroughly tested this yet, but it might be something worth looking into.

- [Ooniprobe](https://ooni.torproject.org/post/ooni-mobile-app/) is a mobile app developed by the Open Observatory for Network Interference and is a simple utility that allows you to run network measurements through your phone to identify whether your current Internet connection implements any level of censorship. If you are interested in contributing useful data to the ongoing struggle against pervasive censorship, this might be something for you to do. Please notice, running Ooniprobe has [some risks involved](https://ooni.torproject.org/about/risks/); make sure you understand them before proceeding.

- [Security Umbrella](https://secfirst.org/) is a mobile app developed by Security First that combines a lot of useful security and safety advice, dealing with both digital as well physical threats. It's a very useful resource to have at hand, and you should definitely check it out.


## Upcoming Events

- 6-10 March: [Internet Freedom Festival](https://internetfreedomfestival.org/), Valencia, Spain
- 29-31 March: [RightsCon](https://www.rightscon.org/), Brussels, Belgium
- 5-6 May: [CryptoRave](https://cryptorave.org), São Paulo, Brazil
- 8-10 May: [re:publica](https://re-publica.de), Berlin, Germany

## People who contributed to this newsletter

This newsletter is edited collaboratively by the larger Security Without Borders community. These are some of the people who helped with this issue: [Martijn Grooten](https://twitter.com/martijn_grooten), adonis28850 and [others](https://github.com/securitywithoutborders/newsletter/issues/8). Curated by [Claudio "nex" Guarnieri](https://twitter.com/botherder).

---
Preferences: [LINK_PREFERENCES]  
Unsubscribe: [LINK_UNSUBSCRIBE]  
View this email in your browser: [LINK_BROWSER]
