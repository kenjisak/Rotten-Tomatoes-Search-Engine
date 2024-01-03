# COMP4601
Group Members: 
Leo Xu: 101149896
Kenji Isak Laguan: 101160737
Minh Nguyen: 101154921


Link for video: 
https://youtu.be/ojB-zY3dfFw


Summary:

TLDR: We finished everything and completed all the requirements.

Crawl and search fruits and personal websites (10 points each) - Completed
    - fruits website and rotten tomatoes for the personal website
    - fruits
        - scraping and using the paragraphs and the title for searching in the index
    - personal
        - scraping movie info or actor info and their titles for searching in the index
        - uses cast and crew links to crawl for more if on a movie page, or movies in the actor's filmography if on an actor page
        - Only scrapes through 500 links
Search functionality supports query parameters (20 points) - Completed
    a) Supports 'q' for specifying the query
        - has a search textbox for users to input their query on the home page
    b) Supports 'boost' for boosting results using PageRank
        - has radio buttons on the page, true or false, to boost the page rank
    c) Supports 'limit' to specify the number of results
        - has a limit textbox for users to input number of pages theyd like.
        - theres a default 10 in the text box, which user can change
            - if any value under 1 or over 50 was given, the server will default to 10 results
Browser-based interface for searching and viewing results (5 points) - Completed
    - functionality explained above for the web page
    - when receiving the results, user can click on view details for each result to view the other information required below.
    - when receiving the results, user can click on the original url link for each result to view the pages data.
Search results include required information (5 points) - Completed
    a) Includes the URL of the original page
    b) Includes the title of the original page
    c) Provides the PageRank of the page within the crawled network
    d) Offers a link to view data for the page
    e) Displays the computed search score for the page
Viewing a page's data includes required information (5 points) - Completed
    a) Includes URL
    b) Includes Title
    c) Lists incoming links
    d) Lists outgoing links
    e) Provides word frequency data
Search service properly integrates with distributed search service (15 points) - Completed

Overall, the functional requirements have been successfully completed, meeting the specified criteria. The non-functional requirements will be evaluated based on the demonstration recording, where understanding and quality of implementation will be assessed.
