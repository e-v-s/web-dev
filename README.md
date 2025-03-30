# web-dev

# Walking an application

Use page-source, inspector, network and debugger on dev-tools.

# Content Discovery

Manually, automated and OSINT.

## Robots.txt

website/robots.txt

## Favicon

Sometimes devs forget about it when developing a website, it can give clues to which frameworks they're using.
Transform it to md5 hash and look it up on  https://wiki.owasp.org/index.php/OWASP_favicon_database

<code> curl favicon-image-url | md5sum </code>

## Sitemap XML

## HTTP Headers

Can also be seen using devtools. It shows the versions used by HTTP and HTTPS, it status, what server etc.

<code> curl website.com -v </code>

First lines are the HTTP Header.
