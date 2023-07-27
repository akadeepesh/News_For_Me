# News_For_Me
## Daily Current Affairs
### This Python script uses the `requests`, `datetime`, `docx`, and `bs4` libraries to fetch current affairs from the News API, extract article content from webpages, and generate a Microsoft Word document containing the current affairs information. The script defines several functions to perform these tasks:

- `fetch_current_affairs`: This function uses the `requests` library to fetch top headlines from the News API for a specified source (`the-hindu`) and returns a list of articles.
- `extract_article_content`: This function takes a URL as input, uses the `requests` library to fetch the webpage content, and uses the `BeautifulSoup` class from the `bs4` library to extract the text of the article from the webpage.
- `generate_current_affairs_doc`: This function takes a list of articles as input and uses the `docx` library to generate a Microsoft Word document containing the current affairs information. The document includes a heading with the current date, headings for each article title, paragraphs for each article description and content, and paragraphs for each article source and URL.

The `main` function calls these functions to fetch current affairs, generate a current affairs document, and save it to a file named `current_affairs.docx`.
