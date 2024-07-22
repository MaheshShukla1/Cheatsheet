# Cheat Sheet Repository for Tech Enthusiasts

Welcome to the **Cheat Sheet Repository**! Here, you'll find a comprehensive collection of cheat sheets covering a wide range of technology topics. Whether you’re a beginner or a seasoned pro, this repository is your go-to resource for quick and easy access to essential tech information
[google-cloud-security-cheat-sheet.pdf](https://github.com/user-attachments/files/16315573/google-cloud-security-cheat-sheet.pdf)

## [SSH Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/SSH-Cheatsheet)

## [Splunk Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/Splunk-Cheatsheet)

## [HTTP Status Code Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/HTTP-Status-Code-Cheatsheet)

## [Bash Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/_new)

## [IPv4 Subnetting cheat sheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/IPv4-Subnetting-cheat-sheet)

## [Powershell Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/Powershell-Cheatsheet)

## [Curl cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/Curl-CheatSheet)

## [SQL Map Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/SQL-Map-Cheatsheet)

## [Nmap Cheatsheet](https://github.com/MaheshShukla1/Cheatsheet/wiki/Nmap-Cheatsheet)

## 📚 Table of Contents

- [Introduction](#introduction)
- [Available Cheat Sheets](#available-cheat-sheets)
  - [Programming Languages](#programming-languages)
  - [Web Development](#web-development)
  - [Networking](#networking)
  - [Cybersecurity](#cybersecurity)
  - [Data Science](#data-science)
  - [DevOps](#devops)
  - [Database Management](#database-management)
  - [Tools & Utilities](#tools--utilities)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Contact](#contact)

## 📖 Introduction

This repository is designed to help you find quick references and cheat sheets for various technology-related topics. We cover everything from programming languages to cybersecurity tools, so you can find the information you need in just a few clicks.

## 📜 Available Cheat Sheets

Here’s a breakdown of the cheat sheets available in this repository:

### Programming Languages

- **Python**: [Python Cheat Sheet](path/to/python-cheat-sheet.md)
- **JavaScript**: [JavaScript Cheat Sheet](path/to/javascript-cheat-sheet.md)
- **Java**: [Java Cheat Sheet](path/to/java-cheat-sheet.md)
- **C++**: [C++ Cheat Sheet](path/to/cpp-cheat-sheet.md)

### Web Development

- **HTML/CSS**: [HTML/CSS Cheat Sheet](path/to/html-css-cheat-sheet.md)
- **React**: [React Cheat Sheet](path/to/react-cheat-sheet.md)
- **Node.js**: [Node.js Cheat Sheet](path/to/nodejs-cheat-sheet.md)

### Networking

- **TCP/IP**: [TCP/IP Cheat Sheet](path/to/tcp-ip-cheat-sheet.md)
- **OSI Model**: [OSI Model Cheat Sheet](path/to/osi-model-cheat-sheet.md)

### Cybersecurity

- **Snort Rules**: [Snort Rules Cheat Sheet](path/to/snort-rules-cheat-sheet.md)
- **Wireshark**: [Wireshark Cheat Sheet](path/to/wireshark-cheat-sheet.md)

### Data Science

- **Pandas**: [Pandas Cheat Sheet](path/to/pandas-cheat-sheet.md)
- **NumPy**: [NumPy Cheat Sheet](path/to/numpy-cheat-sheet.md)

### DevOps

- **Docker**: [Docker Cheat Sheet](path/to/docker-cheat-sheet.md)
- **Kubernetes**: [Kubernetes Cheat Sheet](path/to/kubernetes-cheat-sheet.md)

### Database Management

- **SQL**: [SQL Cheat Sheet](path/to/sql-cheat-sheet.md)
- **NoSQL**: [NoSQL Cheat Sheet](path/to/nosql-cheat-sheet.md)

### Tools & Utilities

- **Git**: [Git Cheat Sheet](path/to/git-cheat-sheet.md)
- **Vim**: [Vim Cheat Sheet](path/to/vim-cheat-sheet.md)

## 🤝 How to Contribute

We welcome contributions from the community! If you’d like to add a new cheat sheet or improve existing ones, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your modifications and add new cheat sheets.
4. Submit a pull request with a clear description of your changes.

## 📜 License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for more details.

## 📧 Contact

For any questions or suggestions, feel free to reach out:

- **Email**: [Email](shuklalogic@gmail.com)
- **GitHub**: [Github Profile](https://github.com/MaheshShukla1)

# Google Dork Cheatsheet

## What Is a Google Dork?

A “Google dork” is an advanced Google search technique. “Google dorking” (aka “Google hacking”) is the activity of performing advanced searches on Google. You can combine different Google dorks to comb data otherwise inaccessible to ordinary users of Google search.

On a browser, if you make too many Google searches in a short time, Google requires that you unscramble garbled letters in an image called a captcha before you can proceed. Captcha completion can frustrate end users like you, but Google servers must nip denial-of-service cyberattacks in the bud.

Unlike most cheat sheets, we cannot guarantee that the commands below will remain unchanged in perpetuity. Google updates its dorks continually, so deprecated techniques don’t appear here, even if you can find them elsewhere on the Internet.

### Before You Begin Google Dorking

Google dorking is not a playground where you can flood commands to your heart’s content:

- Google limits your Google search rate from a single device.
- It may ban your IP if you issue too many queries.
- Abuse of dorks may have legal repercussions.

No, you’re not immune even if you’re working from a virtual machine toying with [sqlmap](https://www.stationx.net/sqlmap-cheat-sheet/).

If you know you can’t resist having fun with it (and you will), you could work from [Pagodo](https://github.com/opsdisk/pagodo), which automates Google searching for potentially vulnerable web pages and applications on the Internet. It also lets you [automate the rate](https://github.com/opsdisk/pagodo#wait-time-between-google-dork-searchers) at which your device issues Google dorks.

Regardless of how you use Google dorks, respect Google’s [Terms of Service](https://policies.google.com/terms). Be careful.

### Examples of Creepy Dorks

These dorks reveal vulnerabilities in websites, and their contents may be newsworthy depending on the zeitgeist.

For details on how the following commands work, refer to [Text dorks](https://www.stationx.net/google-dorks-cheat-sheet/#text-dorks), [Google Dorks Operators](https://www.stationx.net/google-dorks-cheat-sheet/#google-dorks-operators), and [Scope-Restricting Dorks](https://www.stationx.net/google-dorks-cheat-sheet/#scope-restricting-dorks).

| EXAMPLES                                                                                                                                                                                                                                                                                                                                                                                                                                                                | DESCRIPTION                                                                                                                                                                                                                                                                                                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [inurl:"view.shtml" "Network Camera"](https://www.google.com/search?q=inurl%3A%22view.shtml%22+%22Network+Camera%22), ["Camera Live Image"](https://www.google.com/search?q=%22Camera+Live+Image%22), [inurl:"guestimage.html"](https://www.google.com/search?q=inurl%3A%22guestimage.html%22), [intitle:"webcamXP 5’"](https://www.google.com/search?q=intitle%3A%22webcamXP+5%E2%80%99%22)                                                                            | Get web applications showing live webcam (online camera) footage.                                                                                                                                                                                                                                                                                                                                                      |
| ["Not for Public Release" + "Confidential" ext:pdf \| ext:doc \| ext:xlsx](https://www.google.com/search?q=%22Not+for+Public+Release%22+%2B+%22Confidential%22+ext%3Apdf+%7C+ext%3Adoc+%7C+ext%3Axlsx)                                                                                                                                                                                                                                                                  | Get links to documents meant to be classified. Some come from governmental websites.                                                                                                                                                                                                                                                                                                                                   |
| [site:.hk & inurl:wp-login](https://www.google.com/search?q=site%3A.hk+%26+inurl%3Awp-login)                                                                                                                                                                                                                                                                                                                                                                            | Get login pages of WordPress sites ending in the notoriously [unsafe domain](https://circleid.com/posts/hk_the_most_unsafe_domains) “.hk”                                                                                                                                                                                                                                                                              |
| [”index of” inurl:ftp secret](https://www.google.com/search?q=%E2%80%9Dindex+of%E2%80%9D+inurl%3Aftp+secret)                                                                                                                                                                                                                                                                                                                                                            | Get FTP servers you want to access containing the keyword “secret”                                                                                                                                                                                                                                                                                                                                                     |
| Critical dorks performed on .env files yielding results such as:  <br>[![filetype:env [and a sensitive parameter] - Google Search - Google Search results on .env files containing a sensitive parameter.](https://www.stationx.net/wp-content/uploads/2022/11/Google-Search-results-on-.env-files-containing-a-sensitive-parameter.png)](https://www.stationx.net/wp-content/uploads/2022/11/Google-Search-results-on-.env-files-containing-a-sensitive-parameter.png) | Popular web development frameworks use .env files to declare general variables and configurations for local and online dev environments, often including passwords.  <br>The dork used to produce the screenshot exposes database passwords. Hence it’s vital to keep .env files from being publicly accessible.  <br>(If you’ve read this cheat sheet in its entirety, you will be able to guess the dork used here.) |

[This often-updated exploit database](https://www.exploit-db.com/google-hacking-database) contains other Google dorks that expose sensitive information. Proceed with caution.

## Google Dorks Search Parameters

A search parameter in a Google dork is the text string payload affixed to or used with the Google dorking command or operator. Without a suitable search parameter, Google treats the dork keyword as an ordinary query keyword at best and returns zero results at worst.

For example, in the search [site:www.stationx.net](https://www.google.com/search?q=site%3Awww.stationx.net), the domain “www.stationx.net” is the parameter. In [(psychology OR computer science) AND design](https://www.google.com/search?q=%28psychology+OR+computer+science%29+AND+design), the three subjects of psychology, computer science, and design are the parameters. In [16 F to C](https://www.google.com/search?q=16+F+to+C) (converting a temperature from degrees Fahrenheit to Celsius), 16 is the parameter.

Search parameters include web domains, file extensions, numbers, and character strings with or without quotes.

## Google Dorking Commands

As Google’s internal documentation on dorks frequently changes, the following is not an exhaustive list but a list of commands known to return meaningful results. Some of the given commands may be obsolete because they return similar results as a dork-free search. Deprecated commands don’t appear below.

### Scope-Restricting Dorks

These help specify your target range of websites or data types. For example, in hunting for e-books, the Google dork “filetype:pdf” is indispensable.

If a command listed below ends with a symbol, include no space between the command and the parameter. The correct way to use each command is in the “Example usage” column. Otherwise, Google will treat the command as an ordinary search keyword rather than a dork.

| COMMAND           | DESCRIPTION                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EXAMPLE USAGE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `site:`           | Restrict search to a particular website, top-level domain, or subdomain.  <br>Additional query items are optional.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | [site:google.com](https://www.google.com/search?q=site%3Agoogle.com),  <br>[site:maps.google.com](https://www.google.com/search?q=site%3Amaps.google.com),  <br>[site:.org tax return](https://www.google.com/search?q=site%3A.org+tax+return)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `filetype:, ext:` | Restrict the returned web addresses to the designated file type.  <br>  <br>Unlike most other dorks, this **requires additional keywords** in the search bar or will return no results.  <br>  <br>Here is Google’s [official list](https://developers.google.com/search/docs/crawling-indexing/indexable-file-types?hl=en&visit_id=638010780742925546-492926684&rd=1) of common file types it can search.  <br>  <br>Google also supports the file extensions [db](https://www.google.com/search?q=filetype%3Adb+webinar), [log](https://www.google.com/search?q=ext%3Alog), and [html](https://www.google.com/search?q=filetype%3Ahtml+site%3Arumble.com+james).  <br>  <br>Nonetheless, searches on mp3 and mp4 with and without additional search terms have yielded no results. | [filetype:pdf car design](https://www.google.com/search?q=filetype%3Apdf+car+design), [ext:log username](https://www.google.com/search?q=ext%3Alog+username)  <br>  <br>Compare with [filetype:pdf](https://www.google.com/search?q=filetype%3Apdf), [ext:txt](https://www.google.com/search?q=ext%3Atxt), etc.![filetype.pdf - Google Search - "Your search - filetype.pdf - did not match any results."](https://www.stationx.net/wp-content/uploads/2022/11/filetype.pdf-Google-Searc-Your-search-filetype.pdf-did-not-match-any-results..png)  <br>  <br>[![ext:txt - Google Search - About 5,420,000 results (0.21 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/exttxt-Google-Search-About-5420000-results0.21-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/exttxt-Google-Search-About-5420000-results0.21-seconds.png) |
| `@`               | Restrict search to a particular social platform.  <br>It supports popular platforms such as Facebook, Twitter, YouTube, and Reddit.  <br>A downside is it’s not as precise as the “site:” dork.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [@twitter pentest](https://www.google.com/search?q=%40twitter+pentest), [@youtube google dorking](https://www.google.com/search?q=%40youtube+google+dorking)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `define:`         | Return definitions of a word or phrase                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Compare [define:privacy](https://www.google.com/search?q=define%3Aprivacy) and a plain search on [privacy](https://www.google.com/search?q=privacy).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `stocks:`         | Check the financial activity of a particular stock                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | [stocks:META](https://www.google.com/search?q=stocks%3AMETA) (Meta),  <br>[stocks:gm](https://www.google.com/search?q=stocks%3Agm) (General Motors),  <br>[stocks:pfizer](https://www.google.com/search?q=stocks%3Apfizer)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `movie:`          | Return information about any movie with the given title                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Compare [movie:"phantom of the opera"](https://www.google.com/search?q=movie%3A%22phantom+of+the+opera%22) and ["phantom of the opera"](https://www.google.com/search?q=%22phantom+of+the+opera%22).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `source:`         | Find reports from a Google News source.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | [source:cnn](https://www.google.com/search?q=source%3Acnn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

### Informational Dorks

These dorks appear to work best if used as standalone commands, i.e., without additional query items.

|COMMAND|DESCRIPTION|EXAMPLE USAGE|
|---|---|---|
|`$`|Search for prices in USD ($). This also works for Euro (€), but not GBP (£) or Yen (¥).|[ipad $329](https://www.google.com/search?q=ipad+%24329), [iphone €239](https://www.google.com/search?q=iphone+%E2%82%AC239)|
|`cache:`|Get Google’s last saved version of a particular website. A website snapshot like this is called “cache”.|[cache:news.yahoo.com](https://www.google.com/search?q=cache:news.yahoo.com)|
|`link:`|Find pages linking to the given domain|[link:www.stationx.net](https://www.google.com/search?q=link%3Awww.stationx.net)|
|`related:`|Return websites related to the given website|[related:harvard.edu](https://www.google.com/search?q=related%3Aharvard.edu), [related:bbc.co.uk](https://www.google.com/search?q=related%3Abbc.co.uk)|
|`map:`|Get a map of the given location|[map:"new york"](https://www.google.com/search?q=map%3A%22new+york%22)|
|`weather:`|Get the weather of the given location|[weather:london](https://www.google.com/search?q=weather%3Alondon)|

|USABLE BUT POSSIBLY DEPRECATED COMMANDS|   |   |
|---|---|---|
|`location:`|Find information about a location.  <br>  <br>Results may be inconsistent.  <br>  <br>Google now treats “loc” (formerly an abbreviation of “location”) as a search term instead of a dork.|[loc](https://www.google.com/search?q=location%3ANY%20crime)[ation:NY crime](https://www.google.com/search?q=location%3ANY%20crime) compared with [NY crime](https://www.google.com/search?q=NY+crime).|
|`info:, id:`|Return pages that convey information about the given website.  <br>  <br>Finding queries that gave different results with and without the “info:” / “id:” command was difficult.  <br>  <br>This command could still help you find the canonical, indexed version of a URL.  <br>  <br>Google now treats “id” (possibly shorthand for “info”) as a search term instead of a dork.|["babylon bee"](https://www.google.com/search?q=babylon+bee) vs [info:"babylon bee"](https://www.google.com/search?q=info%3A%22babylon+bee%22): a politically conservative satire website in the US  <br>[!["babylon bee" - Google Search - About 545,000 results (0.43 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/babylon-be-Google-Search-About-545000-results-0.43-seconds-httpsbabylonbee.com_.png)](https://www.stationx.net/wp-content/uploads/2022/11/babylon-be-Google-Search-About-545000-results-0.43-seconds-httpsbabylonbee.com_.png)  <br>  <br>[![info:"babylon bee" - Google Search - About 236 results (0.41 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/infobabylon-bee-Google-Search-About-236-results-0.41-seconds-httpsbabylonbee.com_.png)](https://www.stationx.net/wp-content/uploads/2022/11/infobabylon-bee-Google-Search-About-236-results-0.41-seconds-httpsbabylonbee.com_.png)  <br>  <br>Here’s how [id:"babylon bee"](https://www.google.com/search?q=id%3A%22babylon+bee%22) treats “id” as a search parameter (bold text) in some results:  <br>[![An entry in [id:"babylon bee" - Google Search] - Example of Google Search treating "id" as another query keyword - Example of Google Search treating "id" as another query keyword](https://www.stationx.net/wp-content/uploads/2022/11/An-entry-in-idbabylon-bee-Google-Search-Example-of-Google-Search-treating-id-as-another-query-keyword-Example-of-Google-Search-treating-id-as-another-query-keyword.png)](https://www.stationx.net/wp-content/uploads/2022/11/An-entry-in-idbabylon-bee-Google-Search-Example-of-Google-Search-treating-id-as-another-query-keyword-Example-of-Google-Search-treating-id-as-another-query-keyword.png)  <br>  <br>![An entry in [id:"babylon bee" - Google Search] - Example of Google Search treating "id" as another query keyword](https://www.stationx.net/wp-content/uploads/2022/11/An-entry-in-idbabylon-bee-Google-Search-Example-of-Google-Search-treating-id-as-another-query-keyword.png)|

## Google Dork Generator

Say goodbye to the hassle of trying to remember the exact syntax for your Google Dorks! With our Google Dork Generator, you can simply say what you need to do, and we will generate the Google Dork for you.

Generate

### Text Dorks

These are helpful if you want to look for web pages containing certain text strings or follow particular patterns. For example, those familiar with the URLs of webcam apps, for example, use Google dorks similar to the first entry in [this table](https://www.stationx.net/google-dorks-cheat-sheet/#this-table) to find camera footage to watch.

|COMMAND|DESCRIPTION|EXAMPLE USAGE|
|---|---|---|
|`intitle:, allintitle:`|Look for pages with titles containing the search terms.  <br>  <br>The dork “intitle:” applies to its search parameter only, while “allintitle:” applies to the entire query string.|[intitle:toy story](https://www.google.com/search?q=intitle%3Atoy+story), [intitle:"toy story"](https://www.google.com/search?q=intitle%3A%22toy+story%22), [allintitle:"toy story"](https://www.google.com/search?q=allintitle%3A%22toy+story%22), [allintitle:toy story](https://www.google.com/search?q=allintitle%3Atoy+story)  <br>  <br>Compare the above with the number of search results of [toy story](https://www.google.com/search?q=toy+story) and ["toy story"](https://www.google.com/search?q=%22toy+story%22).|
|`inurl:`|Find links containing the character string.|[inurl:login.php](https://www.google.com/search?q=inurl%3Alogin.php)|
|`allinurl:`|Find links containing all words following the colon (:).  <br>  <br>Equivalent to applying “inurl:” to discrete search strings.|Compare [allinurl: healthy eating](https://www.google.com/search?q=allinurl%3A+healthy+eating) vs [inurl:healthy inurl:eating](https://www.google.com/search?q=inurl%3Ahealthy+inurl%3Aeating):  <br>[![allinurl: healthy eating - Google Search - About 972,000 results (0.53 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/allinurl-healthy-eating-Google-Search-About-972000-results-0.53-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/allinurl-healthy-eating-Google-Search-About-972000-results-0.53-seconds.png)  <br>  <br>[![inurl:healthy inurl:eating - Google Search - About 971,000 results (0.49 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/inurlhealthy-inurleating-Google-Search-About-971000-results-0.49-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/inurlhealthy-inurleating-Google-Search-About-971000-results-0.49-seconds.png)|

|USABLE BUT POSSIBLY DEPRECATED COMMANDS|   |   |
|---|---|---|
|`intext:, allintext:`|Find websites containing the payload.  <br>  <br>The dork “intext:” applies to its search parameter only, while “allintext:” applies to the entire query string.  <br>  <br>The websites displayed in the results appear similar to a search without either command.|Compare [intext:"Index of /" +.htaccess](https://www.google.com/search?q=intext%3A%22Index+of+%2F%22+%2B.htaccess), [allintext:"Index of /" +.htaccess](https://www.google.com/search?q=allintext%3A%22Index+of+%2F%22+%2B.htaccess), and ["Index of /" +.htaccess](https://www.google.com/search?q=%22Index+of+%2F%22+%2B.htaccess).  <br>  <br>Look at [intext:"Index of /" +.htaccess -intitle:"Index of /"](https://www.google.com/search?q=intext%3A%22Index+of+%2F%22+%2B.htaccess+-intitle%3A%22Index+of+%2F%22) (exclude titles containing the search query) too.|

## Google Dorks Operators

Unlike certain Google Dorking commands, you may include spaces between Google dorking operators and your query items. You may combine as many different operators and commands as are necessary.

### Search

These refine the search and constrain the results to follow the rules of logic. Most of the following are logical operators.

|COMMAND|DESCRIPTION|EXAMPLE USAGE|
|---|---|---|
|`" "`|Return exact matches of a query string enclosed in the double quotes.  <br>Note that these are straight and not curly “” quotation marks. The curly quotes may or may not return similar results as straight quotes.  <br>Single quotes don’t work.|["Google dorking commands"](https://www.google.com/search?q=%22Google+dorking+commands%22).  <br>Compare ['movie review'](https://www.google.com/search?q=%27movie+review%27) and ["movie review"](https://www.google.com/search?q=%22movie+review%22):  <br>[!['movie review' - Google Search. - Single quotes enclosing the phrase 'movie review'. About 5,700,000,000 results (0.78 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/movie-review-Google-Search-Single-quotes-enclosing-the-phrase-movie-review-About-5700000000-results-0.78-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/movie-review-Google-Search-Single-quotes-enclosing-the-phrase-movie-review-About-5700000000-results-0.78-seconds.png)  <br>  <br>[!["movie review" - Google Search - Double quotes enclosing the phrase "movie review". About 63,900,000 results (0.89 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/movie-review-Google-Search-Single-quotes-enclosing-the-phrase-movie-review-About-5700000000-results-0.89-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/movie-review-Google-Search-Single-quotes-enclosing-the-phrase-movie-review-About-5700000000-results-0.89-seconds.png)|
|`OR, \|`|Return sites containing either query item joined by OR or the pipe character \|.  <br>This is an inclusive OR.|[Amazon OR Google](https://www.google.com/search?q=Amazon+OR+Google) yields the same number of results as [Amazon \| Google](https://www.google.com/search?q=Amazon+%7C+Google).  <br>[![Amazon OR Google - Google Search - About 25,270,000,000 results (0.58 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-OR-Google-GoogleSearch-About-25270000000-results-0.58-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-OR-Google-GoogleSearch-About-25270000000-results-0.58-seconds.png)  <br>  <br>[![Amazon \| Google - Google Search - About 25,270,000,000 results (0.42 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-25270000000-results-0.42-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-25270000000-results-0.42-seconds.png)|
|`( )`|Group multiple Google dork operators as a logical statement|[(black OR white) hat hacker](https://www.google.com/search?q=%28black+OR+white%29+hat+hacker)|
|`-`|Hyphen; exclude search results containing the word or phrase after the hyphen.|[Amazon -reviews](https://www.google.com/search?q=amazon+-reviews), ["sql injection" -"penetration testing"](https://www.google.com/search?q=%22sql+injection%22+-%22penetration+testing%22)|
|`*`|Wildcard or glob pattern as a placeholder for query item|["type * error"](https://www.google.com/search?q=%22type+*+error%22) returns pages on Type I and II errors in statistics.  <br>Compare this with the search [“type i OR ii error”](https://www.google.com/search?q=type+i+OR+ii+error) which doesn’t use this wildcard:  <br>[!["type * error" - Google Search - About 4,130,000,000 results (0.70 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/type-error-Google-Search-About-4130000000-results-0.70-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/type-error-Google-Search-About-4130000000-results-0.70-seconds.png)  <br>  <br>[![type i OR ii error - Google Search - About 3,450,000,000 results (0.62 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/type-i-OR-ii-error-Google-Search-About-3450000000-results-0.62-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/type-i-OR-ii-error-Google-Search-About-3450000000-results-0.62-seconds.png)|
|`#..#`|Search a numerical range specified by the two endpoints # inclusive|[2006..2008](https://www.google.com/search?q=2006..2008) finds all pages that include 2006, 2007, or 2008 in them.|
|`AROUND(N)`|Match pages containing the search terms separated by at most N other words|[read AROUND(2) book](https://www.google.com/search?q=read+AROUND%282%29+book), [read AROUND(3) book](https://www.google.com/search?q=read+AROUND%283%29+book)|

|USABLE BUT POSSIBLY DEPRECATED COMMANDS|   |   |
|---|---|---|
|`AND, &, +`|Concatenation; return sites containing both query items joined by AND, the ampersand symbol & or the plus sign +.  <br>Google seems to assume you’re using this dork whenever you have multiple search items in one query.  <br>This is because the websites in the dorked search results are similar to queries without these dorks. Curiously, the estimated number of search results differs.|[Amazon AND Google](https://www.google.com/search?q=Amazon+AND+Google), [Amazon & Google](https://www.google.com/search?q=Amazon+%26+Google), [Amazon + Google](https://www.google.com/search?q=Amazon+%2B+Google).   <br>  <br>Compare with [Amazon Google](https://www.google.com/search?q=Amazon+Google) (no quotes):  <br>[![Amazon AND Google - Google Search - About 4,730,000,000 results (0.42 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-AND-Google-Google-Search-About-4730000000-results-0.42-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-AND-Google-Google-Search-About-4730000000-results-0.42-seconds.png)  <br>  <br>  <br>[![Amazon & Google - Google Search - About 4,040,000,000 results (0.44 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-4040000000-results-0.44-seconds-1.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-4040000000-results-0.44-seconds-1.png)  <br>  <br>[![Amazon + Google - Google Search - About 5,040,000,000 results (0.68 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-5040000000-results-0.68-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-5040000000-results-0.68-seconds.png)  <br>  <br>[![Amazon Google - Google Search - About 4,280,000,000 results (0.63 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-4280000000-results-0.63-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Amazon-Google-Google-Search-About-4280000000-results-0.63-seconds.png)|
|`_`|Wildcard symbol for Google Autocomplete.  <br>Google appears to treat this symbol literally if it’s inside double quotes.|Suppose you can’t recall the name of the late singer Michael Jackson:  <br>[Michael _ singer](https://www.google.com/search?q=Michael+_+singer), ["Michael _" singer](https://www.google.com/search?q=%22Michael+_%22+singer). [![Michael _ singer - Google Search - About 342,000,000 results (0.62 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-342000000-results-0.62-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-342000000-results-0.62-seconds.png)  <br>  <br>[!["Michael _" singer - Google Search - About 33,700 results (0.35 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-33700-results-0.35-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-33700-results-0.35-seconds.png)  <br>Compare with [Michael singer](https://www.google.com/search?q=Michael+singer), ["Michael *" singer](https://www.google.com/search?q=%22Michael+*%22+singer).  <br>[![Michael singer - Google Search - About 476,000,000 results (0.55 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-476000000-results-0.55-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-476000000-results-0.55-seconds.png)  <br>  <br>[!["Michael *" singer - Google Search - About 228,000,000 results (0.70 seconds)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-228000000-results-0.70-seconds.png)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-About-228000000-results-0.70-seconds.png)  <br>Only ["Michael *" singer](https://www.google.com/search?q=%22Michael+*%22+singer) has a direct entry about Michael Jackson on the first page of the search results:  <br>[!["Michael *" singer - Google Search - result: "Biography for Kids: Michael Jackson - Ducksters" Occupation: Singer; Born August 29, 1958 in Gary, Indiana; Died: June 25, 2009 in Los Angeles](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-result-Biography-for-Kids-Michael-Jackson-Ducksters-Occupation-Singer-Born-August-29-1958-in-Gary-Indiana-Died-June-25-2009-in-Los-Angel.png)](https://www.stationx.net/wp-content/uploads/2022/11/Michael-singer-Google-Search-result-Biography-for-Kids-Michael-Jackson-Ducksters-Occupation-Singer-Born-August-29-1958-in-Gary-Indiana-Died-June-25-2009-in-Los-Angel.png)|

### Math

The following are mathematical operations that you can perform on Google.

|OPERATORS|DESCRIPTION|EXAMPLE USAGE|RESULT|
|---|---|---|---|
|+|Addition|[3 + 20](https://www.google.com/search?q=3+%2B+20)|23|
|-|Subtraction|[3 - 20](https://www.google.com/search?q=3+-+20)|-17|
|*|Multiplication|[3 * 20](https://www.google.com/search?q=3+*+20)|60|
|/|Division|[3 / 20](https://www.google.com/search?q=3+%2F+20)|0.15|
|% of|Percentage|[33% of 400](https://www.google.com/search?q=33%25+of+400)|6.6|
|X^Y, X**Y|Raise X to the power of Y.  <br>Both operators ^ and ** perform the same operation.|[3^2](https://www.google.com/search?q=3%5E2), [3**2](https://www.google.com/search?q=3**2)|3^2 = 93**2 = 9|
|in, to|Convert a quantity from a given unit to another. Translate words into another language.|[6 ft 2 inches in cm](https://www.google.com/search?q=6+ft+2+inches+in+cm),[140 lbs in kg](https://www.google.com/search?q=140+lbs+in+kg),[100 USD to bitcoin](https://www.google.com/search?q=100+usd+to+bitcoin),[8 am London time to California time](https://www.google.com/search?q=8+am+london+time+to+california+time),[thank you in spanish](https://www.google.com/search?q=thank+you+in+spanish)|6 ft 2 inches = 187.96 cm,140 lbs = 63.5029 kg,100 USD =  <br>[![100 USD = 0.000052 bitcoin (BTC) on 11 Oct 2022, 1:05pm UTC - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/100-USD-0.000052-bitcoin-BTC-on-11-Oct-2022-105pm-UTC-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/100-USD-0.000052-bitcoin-BTC-on-11-Oct-2022-105pm-UTC-Google-Search.png)  <br>  <br>[![8:00am Tuesday in London, UK is 12:00am Tuesday in California, USA - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/800am-Tuesday-in-London-UK-is-1200am-Tuesday-in-California-USA-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/800am-Tuesday-in-London-UK-is-1200am-Tuesday-in-California-USA-Google-Search.png)  <br>  <br>[!["thank you" in English = "gracias" in Spanish - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/thank-you-in-English-gracias-in-Spanish-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/thank-you-in-English-gracias-in-Spanish-Google-Search.png)|
|sqrt|Square root|[sqrt(3)](https://www.google.com/search?q=sqrt(3))|1.73205080757|
|i|Imaginary number.  <br>Use it with other mathematical operations to see it in action.|[i^2](https://www.google.com/search?q=i%5E2)|-1|
|N choose R|Find how many combinations are possible from N items taken R at a time, where N and R are integers.  <br>(Combinatorics)|[6 choose 4](https://www.google.com/search?q=6+choose+4)|15|
|sin, cos, tan|Trigonometric functions. You may specify the formula using symbols and natural language.|[sin(pi/6)](https://www.google.com/search?q=sin%28pi%2F6%29), [sin 30 degrees](https://www.google.com/search?q=sin+30+degrees)|sin(pi/6) = 0.5, sin 30 degrees = 0.5|
|timer|[Timer](https://www.google.com/search?q=timer)|[timer for 20 minutes](https://www.google.com/search?q=timer+for+20+minutes)|[![Google Timer for 20 minutes: 20m00s. It counts down upon page load. - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/Google-Timer-for-20-minutes-20m00s-It-counts-down-upon-page-load-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Google-Timer-for-20-minutes-20m00s-It-counts-down-upon-page-load-Google-Search.png)|
|[This has no specific operator]|[Generate a random number](https://www.google.com/search?q=generate+a+random+number).  <br>Find more on the drop-down dialog box labeled “Tools” on the results page.|[flip a coin](https://www.google.com/search?q=flip+a+coin), [roll a dice](https://www.google.com/search?q=roll+a+dice), [show random number from 10 to 40](https://www.google.com/search?q=show+random+number+from+10+to+40)|[![Flip a coin - with drop-down dialog box labeled "Tools" on the results page - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/Flip-a-coin-with-drop-down-dialog-box-labeled-Tools-on-the-results-page-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Flip-a-coin-with-drop-down-dialog-box-labeled-Tools-on-the-results-page-Google-Search.png)  <br>  <br>[![Roll a dice - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/Roll-a-dice-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Roll-a-dice-Google-Search.png)  <br>[![Show random number from 10 to 40 (Google displays 28 here) - Google Search](https://www.stationx.net/wp-content/uploads/2022/11/Show-random-number-from-10-to-40-Google-displays-28-here-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Show-random-number-from-10-to-40-Google-displays-28-here-Google-Search.png)|
|[graph] EXPRESSION [from A to B]|Graph a mathematical EXPRESSION with variables x and y on an (optional) numerical range from A to B.  <br>The “graph” keyword is only necessary if Google doesn’t understand your query.|[sin(x)/x](https://www.google.com/search?q=sin(x)%2Fx), [graph log(x)](https://www.google.com/search?q=graph+log%28x%29),   <br>[sqrt(x^2+y^2) from -20 to 20](https://www.google.com/search?q=sqrt%28x%5E2%2By%5E2%29+from+-20+to+20)|[![Graph of y=sin(x)/x looks like a peak at x=0 and decreasing ripples towards both horizontal infinities. [sin(x)/x - Google Search]](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-y-sinx-x-looks-like-a-peak-at-x-0-and-decreasing-ripples-towards-both-horizontal-infinities-sinx-x-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-y-sinx-x-looks-like-a-peak-at-x-0-and-decreasing-ripples-towards-both-horizontal-infinities-sinx-x-Google-Search.png)  <br>  <br>[![Graph of y=log(x) looks like a curved arm reaching from bottom left to top right. [graph log(x) - Google Search]](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-y-logx-looks-like-a-curved-arm-reaching-from-bottom-left-to-top-right-graph-logx-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-y-logx-looks-like-a-curved-arm-reaching-from-bottom-left-to-top-right-graph-logx-Google-Search.png)  <br>  <br>[![Graph of z=sqrt(x^2+y^2) looks like a paper cone with the tip at (x,y)=(0,0). [sqrt(x^2+y^2) from -20 to 20 - Google Search]](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-z-sqrtx%5E2y%5E2-looks-like-a-paper-cone-with-the-tip-at-xy00-sqrtx%5E2y%5E2-from-20-to-20-Google-Search.png)](https://www.stationx.net/wp-content/uploads/2022/11/Graph-of-z-sqrtx%5E2y%5E2-looks-like-a-paper-cone-with-the-tip-at-xy00-sqrtx%5E2y%5E2-from-20-to-20-Google-Search.png)|

Google also supports other scientific calculator operations on its [calculator](https://www.google.com/search?q=calculator). This [website](https://mindyourdecisions.com/blog/2018/10/22/5-google-math-tricks-you-must-try/) features additional examples of mathematical operations you can perform on Google.

## Examples of Complex Google Dorks

You can combine Google dorking commands and operations for specific results.

|COMMAND|DESCRIPTION|
|---|---|
|[inurl:zoom.us/j intext:scheduled](https://www.google.com/search?q=inurl%3Azoom.us%2Fj+intext%3Ascheduled)|Get links to publicly shared Zoom meetings you may want to access.|
|["index of" "database.sql.zip"](https://www.google.com/search?q=%22index+of%22+%22database.sql.zip%22)|Get unsecured SQL dumps.  <br>Data from improperly configured SQL servers will show up on this page.|
|[filetype:yaml inurl:cassandra](https://www.google.com/search?q=filetype%3Ayaml+inurl%3Acassandra)|Get YAML configuration files specific to [Apache Cassandra databases](https://cassandra.apache.org/doc/latest/cassandra/operating/backups.html)|
|[@youtube trending shorts](https://www.google.com/search?q=%40youtube+trending+shorts)|Find short clips trending on YouTube|
|[@reddit memes -dark](https://www.google.com/search?q=%40reddit+memes+-dark)|Find memes on Reddit that are not dark|
|[site:cdn.cloudflare.net filetype:pdf](https://www.google.com/search?q=site%3Acdn.cloudflare.net+filetype%3Apdf)|Find PDFs on the *.cdn.cloudflare.net domain|
|[secret in spanish inurl:dict](https://www.google.com/search?q=secret+in+spanish+inurl%3Adict)|Translate the word “secret” to Spanish and limit results to URLs containing “dict”|
|[filetype:doc site:www.stationx.net nathan](https://www.google.com/search?q=filetype%3Adoc+site%3Awww.stationx.net+nathan)|StationX with the .doc extension. This looks for legacy Microsoft Word files containing the keyword “nathan” (founder’s name).  <br>[![Extension](https://www.stationx.net/wp-content/uploads/2023/08/extension.png)](https://www.stationx.net/wp-content/uploads/2023/08/extension.png)|

## How to Prevent Google Dorks

With great power comes great responsibility, and even if you use Google Dorks with the utmost care, other entities may not. Here are some suggestions to avoid becoming the next victim of unwanted Google Dorking.

- Implement IP-based restrictions and password authentication to protect private areas. Securing your login portals discourages unauthorized access.
- Encrypt all sensitive information, like usernames, passwords, email addresses, phone numbers, and physical addresses. This way, in the event of data leakage, the original data remains unexposed.
- Run vulnerability scans to find and disable Google dorks. Examples of vulnerability scanners are [nmap](https://www.stationx.net/nmap-cheat-sheet/), [Nessus](https://www.tenable.com/products/nessus/nessus-faq#:~:text=Nessus%C2%AE%20Essentials%20is%20free,16%20IP%20addresses%20per%20scanner.), and [Qualys](https://www.qualys.com/support/faq/general/#:~:text=Qualys%20Web%20Application%20Scanning%20(WAS,(XSS)%20and%20SQL%20injection.).
- Run regular dork queries on your website to discover loopholes and sensitive information before attacks occur. [Sqlmap](https://www.stationx.net/sqlmap-cheat-sheet/) is a helpful tool.
- If you find sensitive content exposed on your website and you’ve exhausted all other means of removing it (such as changing your passwords or renaming your login pages), request its removal through [Google Search Console](https://support.google.com/webmasters/answer/1663419?hl=en).
- Be judicious in the use of `robots.txt`. Read the [warning](https://www.stationx.net/google-dorks-cheat-sheet/#word-of-caution) below.

### A Word of Caution

Other websites mentioning Google Dorks typically recommend using robots.txt to conceal sensitive content or to stop Google from indexing specific parts of your website. On your website server, you can find `robots.txt` in the root-level directory, such as `/public_html`.

What seems like a simple, good-faith solution to eliminate complex reconnaissance via Google Dorks is, to an intelligent hacker, a treasure trove and a cash cow. Instead of backing off, they’ll attack your website by targeting the items listed in `robots.txt`.

Hence, it’s best to adopt this measure cautiously. The most prudent use of `robots.txt` is instructing Google to exclude one’s entire website, as follows:
