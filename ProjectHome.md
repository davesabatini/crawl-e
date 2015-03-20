CRAWL-E is a web crawling framework that seamlessly supports distributed crawling across multiple threads as well as multiple machines.

CRAWL-E was designed to crawl fast with as little development time as possible. It is only a framework, and requires the development of a Handler module in order to function properly.

The CRAWL-E developers are very familiar with how TCP and HTTP works and using that knowledge have written a web crawler intended to maximize TCP throughput. This benefit is realized when crawling web servers that utilize persistent HTTP connections as numerous requests will be made over a single TCP connection thus increasing the throughput.

Other features of CRAWL-E are multiple HTTP request method support, the most
basic being GET, POST, PUT, DELETE, HEAD.


CRAWL-E has been utilized in the data collection of:
  * Can Social Networks Improve e-Commerce: a Study on Social Marketplaces, [Gayatri Swamynathan](http://www.cs.ucsb.edu/~gayatri/), [Christo Wilson](http://www.cs.ucsb.edu/~bowlin), [Bryce Boe](http://www.cs.ucsb.edu/~bboe), [Kevin C. Almeroth](http://www.cs.ucsb.edu/~almeroth/) and [Ben Y. Zhao](http://www.cs.ucsb.edu/~ravenben), WOSN'08
  * User Interactions in Social Networks and their Implications, [Christo Wilson](http://www.cs.ucsb.edu/~bowlin), [Bryce Boe](http://www.cs.ucsb.edu/~bboe), [Alessandra Sala](http://www.dia.unisa.it/~sala/), [Krishna P. N. Puttaswamy](http://www.cs.ucsb.edu/~krishnap/) and [Ben Y. Zhao](http://www.cs.ucsb.edu/~ravenben), EuroSys'09