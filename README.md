# Whymark_dot_net
### Source code for the whymark.net (and similar) websites
  
Minimal and fast landing page with links to various services or resources.
<br/>
  
- Original template is from [HTML UP](https://html5up.net/aerial), instructions are in the `TemplateDocs.txt` file.[^license]
- Use [this list](https://fontawesome.com/v6/icons/) to look up icon names/references from the font file used for the buttons.
- Background image is from the [Chrome Dinosaur Game](https://en.wikipedia.org/wiki/Dinosaur_Game) created by the Chrome UX team.
- Error pages are present for use with AWS Cloudfront, to retain the styled theme in case of backend issues. If you don't need these for your use case then you can safely remove the whole directory.
- Cloudflare images are present for use in Cloudflare Access / Zero Trust and can also be safely deleted if you have no need for them.
<br/>
  
I would strongly recommened that you review the following files and linked documentation to ensure that the level of security is suitable for your site.
- robots.txt [Web Crawlers & Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard)
- crossdomain.xml & clientaccespolicy.xml [Flash & Silverlight policies](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- .well-known/mta-sts.txt [Mail Transfer Agent Strict Transport Security](https://www.ncsc.gov.uk/collection/email-security-and-anti-spoofing/using-mta-sts-to-protect-the-privacy-of-your-emails)
<br/>
<br/>
  
[^license]:Distributed under [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/). Feel free to copy onwards, just give credit to the original authors!
