# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on [ ... date you accessed the file ... ]

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

The top segment says that any bot is allowed to access any page on the site. However the "Crawl-delay" indicates that the bot must wait 10 seconds in between requests to prevent overloading the server.
The bottom segment says that the SemrushBot specifically is not allowed to access any page on the site.
