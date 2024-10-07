This Python script extracts and cleans news articles from a list of URLs stored in a CSV file. It scrapes the main heading and optimized news content while removing unwanted elements such as advertisements, footers, headers, navigation bars, scripts, and social media links. The cleaned content is saved as individual text files in a specified output folder. The code also handles failed URL requests and logs them for troubleshooting.


Features:
Scrapes main news headings and content from web pages.
Removes unnecessary sections like ads, footers, scripts, and style tags.
Optimizes content extraction by filtering through <div> and <p> tags.
Logs failed URL retrievals for further inspection.
Excludes content from domains like LinkedIn, Facebook, YouTube, etc.


Technologies:
Python
BeautifulSoup for web scraping
pandas for CSV file processing
requests for making HTTP requests
