# Whymark_dot_net :globe_with_meridians:
Source code for the [whymark.net](https://whymark.net/) website (and mirrors) with links to various related services or resources.


## Features
Flat, minimalistic responsive design. The goals were maximum speed, minimum filesize and enhanced code-readability. There's no JS, only plain HTML and CSS. No frameworks of third-party requirements.

- Less than 15Kb total size for both html+css.
- Image fallback options to allow for smallest filesizes, using webp where supported.
- Responsive layout with adjustments triggered at 768px, 1024px, and 1200px.
- Automatic light & dark mode colour schemes.


## Config
### Third-Party Customisation
In addition to the template, the following is present:
- Top level 404 error page is present for use with Cloudflare Pages' [Not Found Behaviour](https://developers.cloudflare.com/pages/platform/serving-pages/) customisation, to retain the styled theme in case of backend issues. If you don't need these for your use case then you can safely remove/ignore it.
- The _redirects file is used for Cloudflare Pages' [redirects](https://developers.cloudflare.com/pages/platform/redirects/) function.
- The _headers file is used for Cloudflare Pages' [custom headers](https://developers.cloudflare.com/pages/platform/headers/) function.


### InfoSec
I would strongly recommened that you review the following files and linked documentation to ensure that the level of security is suitable for your site:
- robots.txt to control [Web Crawlers & Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard)
- crossdomain.xml & clientaccespolicy.xml to limit [Flash & Silverlight](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- .well-known/mta-sts.txt for [Mail Transfer Agent Strict Transport Security](https://www.ncsc.gov.uk/collection/email-security-and-anti-spoofing/using-mta-sts-to-protect-the-privacy-of-your-emails), the current version we implement is [here](https://github.com/daniel-whymark/whymark_dot_net_mta-sts).
- ads.txt for restricting [Authorized Digital Sellers](https://iabtechlab.com/ads-txt/)


## License
Distributed under [MIT License](https://opensource.org/licenses/MIT). Feel free to copy onwards but it's always good manners to give credit to the original authors!


## Credits
CSS template:  
- [Grid](https://github.com/uisual/freebies/tree/master/grid) by [Uisual](https://github.com/uisual/)

SVG Icons:
- [Bootstrap](https://icons.getbootstrap.com)

