Webscraping is a method of data mining from web sites that uses software to extract all the information available from the targeted site by simulating human behavior. A script does this much more quickly and efficiently than a human, as it can generate multiple requests per minute.

<i>Step 1: Find the URL you want to scrape.</i>
In our case, its amazon.com.

Although before you try to start scraping a site, it’s a good idea to check the rules of the website first. The scraping rules can be found in the robots.txt file, which can be found by adding a /robots.txt path to the main domain of the site.

<i>Step 2: Identify the structure of the sites HTML</i>

With the inspect tool, quickly identify which elements you need to target.

<i>Step 3: Install Beautiful Soup and Requests</i>

There are other packages and frameworks, like Scrapy. But Beautiful Soup allows you to parse the HTML in beautifully, so that’s what I’m going to use. With Beautiful Soup, you’ll also need to install a Request library, which will fetch the url content.
If you aren’t familiar with it, the Beautiful Soup documentation has a lot of great examples to help get you started as well.

To install these two packages, you can simply use the pip installer.

<b>$ pip install requests</b>

and then…

<b>$ pip install beautifulsoup4</b>

<i>Step 4: Web Scraping Code:</i>

You'll find it in the 'price_scrapper.py' file.

<i>Step 5: Isolating the results:</i>

Beautiful Soup also has a host of other ways to search, filter and isolate the results you want from the HTML. You can also be more specific, finding an element with a specific class or attribute:

I know this really just scratches the surface of web scraping. And my intention isn’t to go into a ton of detail here. Web scraping is actually pretty easy to get started. But doing it the right way takes a little more time and effort. Also, I’m still fairly new at this, and am by no means an expert on anything, and appreciate any feedback or tips!



