# Webcrawler

Webcrawler to find all the links in a domain
#
npm run start (website)

The webcrawler takes in an a url as input and then lists all the links relative to the website's domain. The shortcoming of the crawler is the time it would take to go through a large website with many subdomains. For example, in the case that https://github.com is entered as an input, the crawler will attempt to list every link associated with github including every user and their repositories.
The project can be improved by having a frontend for a more convienient user interface and by having way to sort and search for specific urls. It can also be improved to look for additional content instead of only URLS.
