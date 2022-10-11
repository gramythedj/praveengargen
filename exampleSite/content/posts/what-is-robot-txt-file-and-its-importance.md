---
title: What is robots.txt? and its importance in SEO
thumbnail: default/gpking.jpg
thumbnailAlt: my thoughts
description: one of the most important thing to do before lauching a site is to setup sitemap and robots.txt for google bots to crawl your website
date: 2022-08-21T05:57:00.000Z
tags:
  - blog
---

# What is robots.txt?
![robots.txt](https://miro.medium.com/max/966/1*InlE5EBbjkCQanIMAIcVDA.png)



# Just what is robots.txt?


Robots.txt is a text file with instructions for internet search engine crawlers. It defines which areas of the crawlers which can be website permitted to search. However, these are not explicitly called by the robots.txt file. Instead, certain areas are not allowed to be searched. 

Using this text that is simple, you can effortlessly exclude entire domains, complete directories, one or more subdirectories or individual files from s.e. crawling. But, this file does maybe not drive back unauthorized access.

Robots.txt is stored into the root directory of a domain. Therefore it is the document that is very first crawlers open when visiting your site. Nevertheless, the file does not only control crawling. You can even integrate a link to your sitemap, gives google crawlers a summary of all existing URLs of the domain.



## How robots.txt works

In 1994, a protocol called REP (Robots Exclusion Protocol that is standard published. This protocol stipulates that most s.e. crawlers(user-agents) must search for the first robots.txt file in the main directory of your site and read the instructions it contains. Only then, robots can start indexing your internet web page. 

The file must directly be based in the root directory of your domain and must be written in reduced case because robots read the robots.txt file and its directions case-sensitive. Unfortuitously, not absolutely all search engine robots follow these rules. At least the file works most abundant in search that is important like Bing, Yahoo, and Google. Their search robots strictly follow the REP and robots.txt instructions.

In training, robots.txt are used for various kinds of files. For image files, it prevents these files from showing up in the Google serp's if you utilize it. Unimportant resource files, such as script, style, and image files, can be blocked effortlessly also with robots.txt. In addition, you are able to exclude dynamically created webpages from crawling using commands that are appropriate.

 For example, outcome pages of an search that is internal, pages with session IDs or user actions such as shopping carts can be obstructed. You can also get a grip on access that is crawler other non-image files (web pages) using the text file. Thereby, you are able to avoid the scenarios which can be after

In this context, however, keep in mind that robots.txt does not guarantee that your internet site or sub-pages that are individual not indexed. It only controls the crawling of your site, but not the indexation. If web pages are not to be indexed by search machines, you have to set the meta that is after into the header of your web page:

<meta name="robots" content="noindex">
Nevertheless, you ought not to block files that are of high relevance for search robots. Note that CSS and JavaScript files should be unblocked, additionally as these are used for crawling specially by mobile robots.

## Which guidelines are utilized in robots.txt?

Your robots.txt needs to be conserved as a UTF-8 or text that is ASCII in the root directory of the web page. There must be just one file using this name. It has more than one rule sets structured in a format that is clearly readable. The principles (instructions) are processed all the way through whereby upper and lower case letters are distinguished.
![enter image description here](https://cf-assets.www.cloudflare.com/slt3lc6tev37/3Ywvq2PWJh61tcLdjerzsf/e9285f6cb42c1ece060d2e4aa29bf6b2/robots-txt-example.png)
The terms that are following utilized in a robots.txt file:

User-agent: denotes the real name of this crawler (the names are present in the Robots Database)
disallow: prevents crawling of certain files, directories or website pages
allow: overwrites disallow and permits crawling of files, webpages, and directories
sitemap (optional): shows the place for the sitemap
*: stands for any number of character
$: is short for the last end of this line

The instructions (entries) in robots.txt always contain two parts. In the part that is first you define which robots (user-agents) the following instruction apply for. 

The part that is 2nd the instruction (disallow or enable). "user-agent: Google-Bot" and also the instruction "disallow: /clients/" mean that Google bot isn't permitted to search the directory /clients/. 

The entry is: "user-agent: *" with all the instruction "disallow: /" if the whole website is not to ever be crawled by a search bot. You can use the buck indication "$" to block web pages that have a extension that is specific. The statement "disallow: /* .doc$" blocks all URLs with a .doc extension. In the way that is same you can block particular file formats n robots.txt: "disallow: /*.jpg$".

For example, the robots.txt file for the https being internet site.com/ could look like this:

User-agent: *
Disallow: /login/
Disallow: /card/
Disallow: /fotos/
Disallow: /temp/
Disallow: /search/
Disallow: /*.pdf$

Sitemap: https://www.example.com/sitemap.xml

# What part does robots.txt play in search engine optimization?

The directions in a robots.txt file have influence that is strong SEO (Search Engine Optimization) as the file enables you to control search robots. Nonetheless, if user agents are restricted too much by disallow instructions, this has a effect that is negative the ranking of one's website. 

You additionally have to start thinking about you have excluded by disallow in robots.txt you won’t rank with web pages. If, on the other hand, there are no or hardly any disallow restrictions, it can happen that pages with duplicate content are indexed, which also offers a impact that is negative the ranking of the pages.

You should check the syntax before you save the file in the root directory of your website. Also errors that are small lead to search bots disregarding the disallow rules and crawling websites that will never be indexed. Such errors can also lead to pages not any longer being accessible for search bots and URLs which can be entire being indexed because of disallow. 

The correctness could be checked by you of one's robots.txt making use of Google Search Console. Under "Current Status" and "Crawl Errors", you may find all pages blocked by the disallow instructions.

Making use of robots.txt precisely you can make certain that all important components of your website are crawled by search bots. Consequently, your page that is entire content indexed by Google along with other search engines.