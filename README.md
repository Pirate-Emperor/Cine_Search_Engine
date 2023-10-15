# C++ Search Engine Project

This project is a basic text search engine written in C++. It allows users to search for words or phrases in a collection of documents and retrieves the relevant documents based on the query.

## Features

- **Text Searching**: Users can enter search queries and receive a list of documents that contain the search terms.
- **Indexing**: The search engine uses an inverted index to quickly find documents containing a particular word or phrase.
- **Relevance Ranking**: Search results are ranked based on their relevance to the search query.

## Prerequisites

To compile and run this project, you will need:

- A C++ compiler (such as g++, clang++, etc.)
- A Makefile or build script (if not using an IDE)

## Importance
A [search engine](https://www.text-mining.ro/) is a software system that is designed to carry out web searches. They search the World Wide Web in a systematic way for particular information specified in a textual web search query. The search results are generally presented in a line of results, often referred to as search engine results pages (SERPs) The information may be a mix of links to web pages, images, videos, infographics, articles, research papers, and other types of files. Some search engines also mine data available in databases or open directories. Unlike web directories, which are maintained only by human editors, search engines also maintain real-time information by running an algorithm on a web crawler. Internet content that is not capable of being searched by a web search engine is generally described as the deep web.

A search engine maintains the following processes in near real time:
1. Web crawling
2. Indexing
3. Searching

## Web Crawling
Web search engines get their information by web crawling from site to site. The "spider" checks for the standard filename robots.txt, addressed to it. The robots.txt file contains directives for search spiders, telling it which pages to crawl and which pages not to crawl. After checking for robots.txt and either finding it or not, the spider sends certain information back to be indexed depending on many factors, such as the titles, page content, JavaScript, Cascading Style Sheets (CSS), headings, or its metadata in HTML meta tags. After a certain number of pages crawled, amount of data indexed, or time spent on the website, the spider stops crawling and moves on. "[N]o web crawler may actually crawl the entire reachable web. Due to infinite websites, spider traps, spam, and other exigencies of the real web, crawlers instead apply a crawl policy to determine when the crawling of a site should be deemed sufficient. Some websites are crawled exhaustively, while others are crawled only partially".

## Indexing
Indexing means associating words and other definable tokens found on web pages to their domain names and HTML-based fields. The associations are made in a public database, made available for web search queries. A query from a user can be a single word, multiple words or a sentence. The index helps find information relating to the query as quickly as possible. Some of the techniques for indexing, and caching are trade secrets, whereas web crawling is a straightforward process of visiting all sites on a systematic basis.

Between visits by the spider, the cached version of the page (some or all the content needed to render it) stored in the search engine working memory is quickly sent to an inquirer. If a visit is overdue, the search engine can just act as a web proxy instead. In this case, the page may differ from the search terms indexed. The cached page holds the appearance of the version whose words were previously indexed, so a cached version of a page can be useful to the website when the actual page has been lost, but this problem is also considered a mild form of linkrot.

## Searching 
Typically when a user enters a query into a search engine it is a few keywords. The index already has the names of the sites containing the keywords, and these are instantly obtained from the index. The real processing load is in generating the web pages that are the search results list: Every page in the entire list must be weighted according to information in the indexes. Then the top search result item requires the lookup, reconstruction, and markup of the snippets showing the context of the keywords matched. These are only part of the processing each search results web page requires, and further pages (next to the top) require more of this post-processing.

Beyond simple keyword lookups, search engines offer their own GUI- or command-driven operators and search parameters to refine the search results. These provide the necessary controls for the user engaged in the feedback loop users create by filtering and weighting while refining the search results, given the initial pages of the first search results. For example, from 2007 the Google.com search engine has allowed one to filter by date by clicking "Show search tools" in the leftmost column of the initial search results page, and then selecting the desired date range. It's also possible to weight by date because each page has a modification time. Most search engines support the use of the boolean operators AND, OR and NOT to help end users refine the search query. Boolean operators are for literal searches that allow the user to refine and extend the terms of the search. The engine looks for the words or phrases exactly as entered. Some search engines provide an advanced feature called proximity search, which allows users to define the distance between keywords. There is also concept-based searching where the research involves using statistical analysis on pages containing the words or phrases you search for.

The usefulness of a search engine depends on the relevance of the result set it gives back. While there may be millions of web pages that include a particular word or phrase, some pages may be more relevant, popular, or authoritative than others. Most search engines employ methods to rank the results to provide the "best" results first. How a search engine decides which pages are the best matches, and what order the results should be shown in, varies widely from one engine to another. The methods also change over time as Internet usage changes and new techniques evolve. There are two main types of search engine that have evolved: one is a system of predefined and hierarchically ordered keywords that humans have programmed extensively. The other is a system that generates an "inverted index" by analyzing texts it locates. This first form relies much more heavily on the computer itself to do the bulk of the work.
## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/my-search-engine-cpp.git
cd my-search-engine-cpp
```

Compile the project using your C++ compiler. For example, with g++:

```bash
g++ -o search-engine main.cpp
```

## Usage

Run the compiled executable:

```bash
./search-engine
```

You will be prompted to enter your search query. Enter the query and press Enter. The search engine will then display a list of documents that contain the search terms.

## Data Source

The search engine uses a sample dataset of documents for searching. The dataset can be found in the `data` directory. You can replace this dataset with your own data source if needed.

## Development

To add more features or modify existing ones, you can edit the C++ files in the `src` directory. Some potential areas for improvement include:

- Implementing a more sophisticated ranking algorithm
- Improving the efficiency of the indexing and searching processes
- Adding support for more complex queries (e.g., phrase queries, boolean queries)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.




Most Web search engines are commercial ventures supported by advertising revenue and thus some of them allow advertisers to have their listings ranked higher in search results for a fee. Search engines that do not accept money for their search results make money by running search related ads alongside the regular search engine results. The search engines make money every time someone clicks on one of these ads.
