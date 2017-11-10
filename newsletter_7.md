Welcome to the seventh newsletter from **Security Without Borders**. This is a somewhat regular newsletter covering recent cyber security issues, tools and events relevant for activists, dissidents, journalists and civil society at large.

It has been some time since we sent a newsletter, but many things have been happening at SWB, even if most of them happened behind the scenes. We do intend to send these newsletters regularly again from now on.

> **Security Tip** Uninstall Adobe's **Flash Player** from your computer (see this [HowTo](https://helpx.adobe.com/flash-player/kb/uninstall-flash-player-windows.html) from Adobe), or at least remove the corresponding plugin from your browser.
Though the security of Flash Player may have improved over the years, vulnerabilities in it are regularly found and subsequently abused to target users with malware. Moreover, fake Flash Player updates are often used as a lure in malware campaigns; if you don't run Flash Player, you can be certain such updates are fake, no matter how convincing they may seem. If you absolutely need to use Flash Player for a particular site or service, use a special device for it, or if that is not possible at least a decidated browser.

## Security alerts

- An important [security update](https://blog.torproject.org/tor-browser-709-released) has been released for the **Tor Browser** for the macOS and Linux operating systems. The update fixes a vulnerability in which an attacker who is able to get you to visit a specially crafted URL can find out your real IP address, which in turn could lead to your identity being revealed. If you use the Tor Browser on either operating system, make sure you run at least version 7.0.9. Note that the Tails operating system is not affected by this vulnerability; users for whom the secrecy of their identity is extremely critical are advised to use [Tails](https://tails.boum.org/)].

- The **WordPress** content management system also released an important [security update](https://wordpress.org/news/2017/10/wordpress-4-8-3-security-release/). If your website runs WordPress you are advised to update immediately. This may also be a good moment to check whether your installation supports automatic updates.
This is not the first time this newsletter has warned of vulnerabilities in WordPress. Though the WordPress team works hard to quickly fix all security issues reported to them, for very critical sites a simple WordPress installation may not be good enough.

- Last month, a vulnerability was found in the protocol used for **encrypted WiFi connections**. The vulnerability, named [KRACK](https://www.krackattacks.com/), could allow someone who finds themselves close to the network to read the communication between a device and the WiFi router. The exploitability depends on the operating system, and many vulnerable instances have been patched.
Though this is fairly serious as vulnerabilities go, it cannot be exploited remotely. Moreover, relying on the encryption of your WiFi connection is a bad idea anyway, as this doesn't protect you from a hack into your router, or a rogue employee at an ISP. Therefore, regardless of whether your connection is vulnerable to KRACK, you should make sure that any connection for content that is even mildly important is already encrypted, for example, by using HTTPS.

- This summer a new attack vector was discovered that makes use of the **Bluetooth protocol**. While the attack would require an adversary to be near the targeted device, it is not to be ignored. Those with a [vulnerable device](https://www.armis.com/blueborne/#/devices) are urged to always make sure the latest security patches are installed, and it is also good practice to have Bluetooth turned off and only turn it on temporarily when necessary, for example, when you use an authentication device.

## Informative reading

- The 2nd of November was the United Nations' [International Day to End Impunity for Crimes Against Journalists](https://en.unesco.org/endimpunity-2017). **Journalists** increasingly face digital threats, and Citizen Lab, which has written various reports on such threats, [listed](https://citizenlab.ca/2017/11/international-end-impunity-crimes-journalists/) three separated cases of attacks against journalists and news organisations.

- The political situation in Catalonia has led to various kinds of **censorship by the Spanish government**, who have seized the domain used by the Catalan regional government and raided the offices of the .cat registrar. In a [blog post](https://www.securitywithoutborders.org/blog/2017/09/27/catalonia.html), SWB strongly condemed this censorship.

- Moderately good news from Turkey, where the **Istanbul Ten**, whom we [wrote about](https://www.securitywithoutborders.org/blog/2017/07/25/istanbul10.html) previously, have been [released on bail](http://www.dw.com/en/german-activist-peter-steudtner-returns-from-turkey-on-bail/a-41113789). They are still awaiting trial though, while the Chair of Amnesty International Turkey, Taner Kılıç, [remains in prison](https://www.amnesty.org/en/latest/news/2017/10/amnesty-turkey-chair-kept-in-jail/).

- Bad news for **civil society in Afghanistan**, as well as anyone in the country who values their privacy: the government has told ISPs to [block](https://thewire.in/194329/afghanistan-block-whatsapp-telegram/) the use of WhatsApp and Telegram. It is unclear whether and to what extent ISPs have complied.

- Security company Volexity has published a [report](https://www.volexity.com/blog/2017/11/06/oceanlotus-blossoms-mass-digital-surveillance-and-exploitation-of-asean-nations-the-media-human-rights-and-civil-society/) about new attacks by the OceanLotus group that have targeted various organisations in Southeast Asia, as well as **civil society in Vietnam**; for this reason it is believed the group is linked to the Vietnamese government. The attacks carried out by the group involved many compromised websites, fake tools that mimic legitimate ones, spearphishing and very detailed digital profiling, and they are yet again a reminder that activists around the world have to take their online security very seriously. 

## Tools

- Many high-risk users use various Google services, for example Gmail. Such users can now sign up for the company's free **[Advanced Protection Program](https://landing.google.com/advancedprotection/)**, to seriously decrease the risks of a rogue account takeover, for example through phishing. One of the ways in which accounts are hardened is the use of a physical security key, which needs to be present before one can login. It is important to note that with added security comes added inconvenience, and certain ways of using Google (such as the use of external apps) will not be possible anymore. For high-risk users, however, this is a compromise worth making, although it does require purchasing physical devices.
If you are interested in the Program, you may want to read the [write-up](https://www.randhome.io/blog/2017/11/05/google-advanced-protection/) by Tek, one of the people behind SWB.

- We have previously written about our **[Blockade node](https://securitywithoutborders.org/missions.html)** that adds anti-virus like capabilities to your web browsing in Chrome or Firefox. We have now added detection for the aforementioned OceanLotus operation to this node.

Preferences: [LINK_PREFERENCES]  
Unsubscribe: [LINK_UNSUBSCRIBE]  
View this email in your browser: [LINK_BROWSER]
