Day 1 --Jan 4, 2021
    What I have learnt today:
        1. Django has a very powerful command, where you can create a projectwith everything organized for you to use, though the number of files might be a little intimidating.
        2. When the the server received a request, the request will first go to the project urls.py, then select where to pass the request depending on the url (usually send to the app url.py). Then url.py in app will also pass the request to views.py. (Don't know what the third parameter 'name' stand for?) At views.py, our server will only render all the html templates we have. 
    
    Question for today:
        1. What does the 'name' parameter in url.py in app, this parameter can be the same as other parameters, and can be removed. May be it is a tag like we use in css?
        2. What can I do I that admin page?