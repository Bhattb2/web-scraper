# scrape.py

A basic webscraper to determine if specific wikipedia pages require citation

It can handle 3 cases:

1. A wikipedia page that does not require any citation
2. A wikepedia pgae that does require citation, but does not have any specific section marked as such
3. A wikipedia page the does require citation(s) in specific sections

## Methods

<<<<<<< HEAD
`get_citations_needed_count(URL)` - returns a number of citations required for a given URL (a general citation requirement, without specific sections counts as 1, however when sections are also supplied, it does not count)

`get_citations_needed_report(URL)` - returns a report of the citations required for a given URL
=======
`get_citations_needed_count(URL)` - returns a number of citations required for a given URL (a general citation requirement, without specific sections counts as 1, however when sections are also supplied, it does not count) 

`get_citations_needed_report(URL)` - returns a report of the citations required for a given URL

## Credits
>>>>>>> 47c53ac89a21121a0a668fb04188c84d33abdea8

## Attributions/Credits

 Diving in stackoverflow quite a lot, Wikipedia pages source code, and the BeautifulSoup docs!