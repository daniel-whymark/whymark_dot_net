# Whymark_dot_net :globe_with_meridians:
Source code for the [whymark.net](https://whymark.net/) websites (and mirrors) with links to various related services or resources.

Flat, minimalistic responsive design. There's no JS, only plain HTML and CSS. No frameworks of third-party requirements.

The goals were speed and code-readability.

## Config
### Third-Party Customisation
In addition to the template, the following is present:
- Top level 404 error page is present for use with Cloudflare Pages, to retain the styled theme in case of backend issues. If you don't need these for your use case then you can safely remove them.
- The _redirects file is used for Cloudflare Pages [redirects](https://developers.cloudflare.com/pages/platform/redirects/).
- The _headers file is used for Cloudflare Pages [custom headers](https://developers.cloudflare.com/pages/platform/headers/).


### InfoSec
I would strongly recommened that you review the following files and linked documentation to ensure that the level of security is suitable for your site:
- robots.txt to control [Web Crawlers & Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard)
- crossdomain.xml & clientaccespolicy.xml to limit [Flash & Silverlight](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
- .well-known/mta-sts.txt for [Mail Transfer Agent Strict Transport Security](https://www.ncsc.gov.uk/collection/email-security-and-anti-spoofing/using-mta-sts-to-protect-the-privacy-of-your-emails)
- ads.txt for restricting [Authorized Digital Sellers](https://iabtechlab.com/ads-txt/)

## License
Distributed under [MIT License](https://opensource.org/licenses/MIT). Feel free to copy onwards but it's always good manners to give credit to the original authors!

## Credits
Original Template:  
- [Uisual](https://github.com/uisual/freebies).

SVG Icons:
- [Bootstrap](https://icons.getbootstrap.com)

