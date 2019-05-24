# Python Assignment


## Part 0: Fork and clone the repo

You should make your own copy of the repository so that you can edit it and at the end submit a pull request.

1. Create a fork of this repo by clicking on the **Fork** link in the upper right.
2. Checkout your personal copy of the repo: `git clone https://github.com/<username>/python-intro1`

### How to submit?
1. `git add filename` (or `git add .`) for all the files you want to add.
2. `git commit -m "Message describing what you did"`
3. `git push origin master`
4. Now if you go to your personal copy on github, your changes should be there: `https://github.com/<username>/python-intro1`
5. From there, click on **Pull Requests** and then **New pull request**.

Ideally, you should regularly run steps 1-3. This will save your work as you go. And if you ever goof things up, you will have all the history, you can revert any file to how it was at any previous commit!

## Exercise 
<b>1.Exploring the HyperText Transport Protocol</b>

You are to retrieve the following document using the HTTP protocol in a way that you can examine the HTTP Response headers.
~~~
http://data.pr4e.org/intro-short.txt
~~~

There are three ways that you might retrieve this web page and look at the response headers:

* Preferred: Modify the socket1.py program to retrieve the above URL and print out the headers and data. Make sure to change the code to retrieve the above URL - the values are different for each URL.
* Open the URL in a web browser with a developer console or FireBug and manually examine the headers that are returned.
* Use the telnet program as shown in lecture to retrieve the headers and content.
<br>

Enter the header values in each of the fields below 

~~~
Last-Modified: 


ETag:

Content_Length:

Cache-Control:

Content-Type:


~~~
