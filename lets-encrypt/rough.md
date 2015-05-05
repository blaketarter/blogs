# Let's Encrypt is Going to Make the Switch to HTTPS Pain Free.
With Mozilla, Google, and the EFF leading the push for an HTTPS only web, there is no better time than now to make the leap to using HTTPS, and Let's Encrypt is making that easier (and cheaper) than ever.

### Enter Let's Encrypt

> Let’s Encrypt is a free, automated, and open certificate authority (CA), run for the public’s benefit. Let’s Encrypt is a service provided by the Internet Security Research Group (ISRG). -
[letsencrypt.org](https://letsencrypt.org/about/)

Let's Encrypt is trying to make the switch to HTTPS as fast and easy as possible, with the added benefit of being 100% free of charge. Instead of hours of error prone work to enable HTTPS on a site, now it's only a few minutes and a few commands away. Hopefully this tool will be available to everyone by summer 2015.

With this new tool, getting an SSL cert can now be done by less experienced site maintainers without the risk of bringing everything crashing down on accident. Easy cert revoking is even included in the off chance that a private key is compromised.

### Mozilla is Making 11.89% of Users Require Secure Connections

According to [recent market share estimates](https://www.netmarketshare.com/browser-market-share.aspx?qprid=0&qpcustomd=0), Mozilla's browser Firefox still holds on to around a 11.8% share of the browser market. They've made the [decision](https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/) to start a roll out of changes to browser features; phasing out access to certain features from websites that aren't secure, as well as making new features only available to websites utilizing HTTPS.

While usage of the http scheme will still be allowed for legacy content, they are sending a firm message to web developers to support HTTPS or start losing functionality and users.

### Google Will Warn Visitors of Non-Secure Sites

That same [market share report](https://www.netmarketshare.com/browser-market-share.aspx?qprid=0&qpcustomd=0) puts Google's Chrome browser around 25% market share, and they intend to make a [decision](https://www.chromium.org/Home/chromium-security/marking-http-as-non-secure) that affects Non-Secure websites as well. Hopefully starting in 2015 Chrome will begin to display a warning to visitors of unsecured http website informing them that they are accessing non-secure content.

This UX based approach is different than that of Mozilla's functionality based approach, but in the end they both achieve the same goal. Both parties have a vested interest to make the web more secure and free, secure access to information is beneficial to Google's business, as well as making both browsers more appealing to users and developers alike.

### Protecting Information and Preventing Malicious Attacks

In April 2015 [Github](github.com) came under a massive DDoS attack, nearly crippling the service for a period of time. While the attack has since subsided, it sent ripples through the tech community. Accusations of China's involvement aside, the attack [could have been prevented](http://www.pcworld.com/article/2905432/wider-use-of-https-could-have-prevented-attack-against-github.html) had affected websites been using HTTPS to access certain resources. The attack used un-suspecting visitors to Chinese based websites to attempt to overload Github's servers. This attack was one of many catalysts in the ever growing push towards HTTPS. Now, not only is HTTPS obviously good for securing communications, it can also protect a sites users from unwittingly partaking in a malicious attack.

### Now is the Time to Make the Switch to HTTPS

2015 is the year of secure web traffic, sites making the switch now are making both a necessary and smart move in doing so. Protecting their users information is an obligation, and having the best experience for users is a requirement for any self-respecting website.

### Further Reading
* [Let's Encrypt Documentation](https://letsencrypt.readthedocs.org/en/latest/intro.html#about-the-let-s-encrypt-client)
* [Preview Repository](https://github.com/letsencrypt/lets-encrypt-preview)
* [Let's Encrypt Announcement](https://letsencrypt.org/2014/11/18/announcing-lets-encrypt.html)
* [Let's Encrypt Website](https://letsencrypt.org/)
* [Mozilla Deprecating Non-Secure http](https://blog.mozilla.org/security/2015/04/30/deprecating-non-secure-http/)
* [Google Marking http Sites as Non-Secure](https://www.chromium.org/Home/chromium-security/marking-http-as-non-secure)
* [HTTPS Could Have Prevented the Github Attack](https://www.eff.org/mention/wider-use-https-could-have-protected-github)
