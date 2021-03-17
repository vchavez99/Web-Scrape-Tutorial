# Web-Scrape-Tutorial
This script will web-scrape Wes Anderson's Wikipedia page and extract the text from the table of contents. The script requires 3 libraries: beautiful soup (```bs4```), ```requests```, and ```lxml```. We will make a request for Wes Anderson's Wikipedia page (https://en.wikipedia.org/wiki/Wes_Anderson) and then identify the name of the class we are trying to extract (in this case "toc"). Finally, we define a "for loop" which allows us to select every item in the table of contents and then we print. Our output reads:

>Contents
>
>1 Early life
>2 Film career
>
>2.1 1990s<>
>4.2 2000s
>5.3 2010s
>6.4 2020s
>
>3 Directing techniques
>
>3.1 Themes and stories
>3.2 Visual style
>3.3 Soundtracks
>
>
>4 Personal life
>5 Filmography
>6 Awards and nominations
>7 In popular culture
>8 Recurring collaborators
>9 Further reading
>10 References
>11 External links
