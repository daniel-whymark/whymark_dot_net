# Whymark_dot_net :globe_with_meridians:
Source code for the [whymark.net](https://whymark.net/) websites (and mirrors) with links to various related services or resources.

Flat, minimalistic design, a fully animated interface (with noscript fallbacks), and styling for all basic page elements (including blockquotes, tables and lists).

## Config
### Third-Party Customisation
In addition to the template, the following is present:
- Error pages are present at the top level for use with Cloudflare, to retain the styled theme in case of backend issues. If you don't need these for your use case then you can safely remove the whole directory.
- Cloudflare images are present for use in Cloudflare Access / Zero Trust and can also be safely deleted if you have no need for them.
- The _redirects file is used for Cloudflare Pages redirects.

### InfoSec
I would strongly recommened that you review the following files and linked documentation to ensure that the level of security is suitable for your site:
- robots.txt to control [Web Crawlers & Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard)
- crossdomain.xml & clientaccespolicy.xml to limit [Flash & Silverlight](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- .well-known/mta-sts.txt for [Mail Transfer Agent Strict Transport Security](https://www.ncsc.gov.uk/collection/email-security-and-anti-spoofing/using-mta-sts-to-protect-the-privacy-of-your-emails)
- ads.txt for restricting [Authorized Digital Sellers](https://iabtechlab.com/ads-txt/)

## License
Distributed under [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/). Feel free to copy onwards, just give credit to the original authors!

## Credits
Original Theme:  
- [HTML UP](https://html5up.net/astral).

Background Images:  
- [Unsplash](https://unsplash.com/photos/gPnHi8AmO5k) credited to [@sincerelymedia](https://unsplash.com/@sincerelymedia).

Fonts:
- Source Sans Pro font is from [Adobe Systems](https://www.adobe.com/) under [SIL Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL).
- [Font Awesome](https://github.com/FortAwesome/Font-Awesome)

Other:  
- [jQuery](jquery.com)
- html5shiv.js (@afarkas @jdalton @jon_neal @remv)
- [background-size polyfill](https://github.com/louisremi/background-size-polyfill)
- [Repond.js](https://github.com/scottjehl/Respond)
