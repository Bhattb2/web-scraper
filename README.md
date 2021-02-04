scrape.py

A simple webscraper to determine if specific wikipedia pages require citation

This can handle 3 cases:

A wikipedia page that does not require any citation
A wikepedia pgae that does require citation, but does not have any specific section marked as such
A wikipedia page the does require citation(s) in specific sections

Methods

get_citations_needed_count(URL) - returns a number of citations required for a given URL (a general citation requirement, without specific sections counts as 1, however when sections are also supplied, it does not count) get_citations_needed_report(URL) - returns a report of the citations required for a given URL

Credits

 in stackoverflow, Wikipedia pages source code, and the BeautifulSoup docs!