# News Exchange Whitepaper (Draft)

### Introduction

To be strictly accurate, the news business isn’t facing "a crisis" these days. It has <em>crises</em>, plural.

Start with sagging revenues and layoffs at major news organizations due to disruption of the industry's traditional advertising model by Google and Facebook. Then there’s waning public trust in the press, some of it driven by the easy spread of propaganda and misinformation online. And, of course, there’s always the parlor game of critiquing the quality of daily coverage in general. Are journalists flat-out missing certain stories? Could they cover some subjects more thoroughly? Are they biased regarding certain sources or topics? And so on.

This document focuses keenly on the economic piece of the puzzle in particular, under the assumption that part is the root of most of the rest. Just make journalism commercially viable again, and the whole ecosystem improves significantly in all sorts of ways. 

The proposed vehicle for doing this is a distributed news exchange built using the Dispatch blockchain protocol. This exchange should have the following features: 

- <strong>Manages user identity and payment transfer via the blockchain.</strong> Users create an identity that persists across multiple news sites and allows them to pay each publisher according to its particular business model. System will handle micropayments if necessary.
- <strong>Runs publishers' business logic off-blockchain.</strong> This well be accomplished via Dispatch's Distributed Artifact Network. System should also be flexible to support multiple approaches for publishers to make money. There may be off-the-shelf DAN modules for implementation of, say, a publisher paywall or an advertising model or to sell event tickets. 
- <strong>Works for a range of users and news providers.</strong> This system is designed to be useful on Day One for incumbent publishers or new entrants, for digital-only shops or legacy publications, for organizations or individual freelancers. Using open-source software from this project, any publisher should be able to set up sign in, payments, and business logic to support their journalism.

It's also important to note what <em>not</em> in scope here. , as that differentiates this exchange from other attempts to implement block: 

- Hosting news content.
- Managing user comments or feedback.
- Managing newsroom governance.

Dieter Rams: "Less, but better."









<img src="https://pmckay.com/img/illo1.jpg" alt="illo1" width="100%" height="auto">


### Links & factoids



- Halving of journalistic workforce: 

- NY Mag story on McNamee's worries about FB: http://nymag.com/selectall/2018/04/roger-mcnamee-early-facebook-investor-interview.html

- Pew State of the News Media report: http://www.pewresearch.org/topics/state-of-the-news-media/


- Dispatch Whitepaper, hosted on .io: https://dispatchlabs.io/wp-content/uploads/2018/03/DispatchWhitepaper_Mar_5_18_v1.55.pdf


- Other Dispatch technical docs: https://github.com/dispatchlabs/TechnicalDocs

- Civil whitepaper: https://github.com/joincivil/whitepaper

- Other Civil links...
  - How it Works summary: https://joincivil.com/how-it-works/
  - Homepage: https://joincivil.com/
  - Nieman coverage: http://www.niemanlab.org/2017/10/civil-the-blockchain-based-journalism-marketplace-is-building-its-first-batch-of-publications/
  - News: http://news.joincivil.com/
  - Poynter coverage: https://www.poynter.org/news/civil-wants-use-cryptoeconomics-and-blockchain-build-future-news-what
  - CJR coverage: https://www.cjr.org/business_of_news/civil-says-the-future-of-media-is-blockchains-and-cryptocurrencies.php


- 2016 CBC study on funding for public broadcast: A 2016 study of 18 western nations for Canadian public broadcasting showed that the state funding leader was Norway, at more than $134 per person. France spends less than half that, at $54 per capita. At less than a fourth of what Norway pays, Italy spends $28, while our neighbors to the north commit $21. How much does the U.S. spend? Around $2 per person per year – lowest of all countries studied. In fact, the U.S. spent less than 4 percent of the average of the 18 Western nations studied.

https://www.washingtonexaminer.com/what-do-other-countries-know-about-public-broadcasting-that-the-us-doesnt

http://www.cbc.radio-canada.ca/_files/cbcrc/documents/latest-studies/nordicity-public-broadcaster-comparison-2016.pdf





- Europe, which has better public funding for media, isn't immune to misninformation either. See https://foreignpolicy.com/2016/11/23/the-eu-moves-to-counter-russian-disinformation-campaign-populism/




- Nieman article on questionable nonprofit scaling: http://www.niemanlab.org/2013/11/what-does-sustainability-look-like-in-nonprofit-journalism/







### Why journalism must function commercially


Public funding levels...

$1.50...
$50 in Europe...

Even the higher spend doesn't get much in terms of...

- Journalism is in a multi-business model world to stay.

- Allow users to log in to their favorite news sites easily. The need to manage relationships with users is crucial, even if the content is free.




### Advantages

- Transaction times should be orders of magnitude faster on this proposed system than on Civil. While more testing will be necessary to specify, an implementation of the exchange as described herein should easily satisfy Larry Page's "10x Rule"... It could be hundreds of times faster, due two factors. First, we're limiting the scope of overall functionality of the system. Second, we're moving a signficant chunk of the remaining functionality to the off-chain DAN, versus Civil's implementation of a "purer" blockchain solution. 


- Works for a wider range of providers.


### Issues

- For some startup news organizations in particular, Civil's use of DAO structures may be valuable. As these organizations, by definition, need to build editorial credibility, the DAO over time may prove to be a useful feature for them. But for larger providers with recognized "brands" among consumers, the DAO structure will likely be just the opposite -- a needless incumberance to blockchain adoption. Similarly, new entrants may be interested and/or fully able to build credibility in other ways. Quartz, TK, and TK, for instance, have had no problem building credibility in recent years, for instance, even without taking votes of their users via the blockchain.





<em>By Peter A. McKay   
<a href="https://twitter.com/peteramckay">@peteramckay</a>    
<a href="mailto:peter@indizr.com">peter@indizr.com</a></em>   
