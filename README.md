## Web Scraping Amazon for Audiobooks

### Project Description
- Scraped data from Amazon to compile a dataset of audiobook details. </br>
- Navigated through Amazon's audiobook listings using Python and BeautifulSoup to extract specific product information such as title, author, narrator, release date, publisher, listening length, language, version, program type, copyright details, ratings, and number of reviews.

### Tools and Technologies
- **Python Libraries**: `requests`, `BeautifulSoup`, `pandas`
- **Data Handling**: `pandas` for organizing scraped data into a structured DataFrame

### Methodology
1. **Fetching Web Pages**: Utilized `requests` to retrieve HTML content from Amazon's audiobook search results and individual product pages.
2. **Parsing HTML**: Employed `BeautifulSoup` to parse and navigate the HTML structure, extracting relevant data points based on defined CSS selectors.
3. **Data Extraction**: Implemented functions to extract specific attributes such as title, author, narrator, etc., handling cases where data might be missing or structured differently.
4. **Data Storage**: Stored extracted data in a structured format (DataFrame) using `pandas`, facilitating easy manipulation and analysis.
5. **Output**: The final dataset, containing comprehensive details of audiobooks scraped from Amazon, was exported to a CSV file for further analysis or integration into other applications.
