TECHNICAL QUESTIONS:

1.What is an API ?

API is a tool set used by the programmers to create a software. An API is consisdered as good when it has clear and brief command which make the programmer to use and reuse it .
It often serves as a middleman to communicate with one another.
for eg:
Google utilizes API to display relevant data from user search queries.
Youtube's API allows to integrate the video.
API's in instagram allows developers to pull tags ,incorporate photos and view the trending photos on their application.

2.What is REST and which methods are there in REST ?

REST stands for Representational State Transfer.
It is an architecture style for designing networked applications.
The World Wide Web (WWW) is an example of a distributed system that uses REST protocol architecture to provide a hypermedia driven interface for websites.
Methods of REST
 Post - Create
 GET – Read
 PUT -Update/Replace
 PATCH –Update/Modify
 DELETE -Delete

3.Which REST method will be cached in browser unless otherwise explicitly mentioned by
server ?

GET system will be catched in program aside from if regardless unequivocally referenced by server. 
The GET system is used to examine or retrival.Get method returns XML or JSON portrayal. 
In goof case it returns 400(bad requesting) or 404 error(not found).

4.Which REST method is idempotent and which method is not idempotent ? Explain with a
small example.
POST is an idempotent strategy… .Example:A customer needs to refresh assets through POST.Since it is an idempotent calling results in incorrect.It is known as sheltered techniques.

HTTP is non-idempotent..Example:To get to a database or picture from HTML page JSP page tales,we use GET method,it will return same object.If we need to get to database like client data we need to utilize POST technique.
Idempotent :
int f=8;
Not idempotent  :
f++;

5.Which REST method should be used to deal with user sensitive data like credit card
information etc. ?
The strategy used to manage the client senstive information like charge card and data is PATCH technique in REST method.It is additionally called as a solicitation technique wherein it gives a substance containing a 
rundown of changes applied to a specific asset mentioned utilizing a HTTP url.


6.What is the difference between http and https ? Explain shortly how https works.
HTTP:

HTTP stands for hyper text transfer protocol which is mainly used for transfering the client request to the browser and information from browser to the client system
for example , all the computers can understand only 0s and 1s which is a binary language. we will give input to the computer in the form of text and numerics but the computer 
coverts into a binary language .
when we are gining these inputs to the browser as text , these browsers translates it as hypertext and the protocol which is used to transfer the text as HyperText Transfer Protocol.
we can transfer images,files but it cannot  transfer videos

HTTPS:

HTTPS stands for Hypertext Transfer Protocol Secure. the main difference between these two protocols is https is more secure than http but both are crptyographic(hidden graphy which use codes)
protocols
HTTP uses TLS(Transport Layer Security) and HTTPS uses SSL(Secure Socket Layer). Both TLS and SSL are secure in their prespectives .Gmail uses TLS and TLS is more secure than SSL.
 Banking information are example of HTTPS.

7.What is caching ? How does it help an application ?

Caching:

          The name itself suggests that it is the process of storing the recently accessed files and when we search the same file another time it takes from the cache area not from the main server
 and it is storage of time ,speed and reduces the additional traffic to the server.

i)It uses gigabyte of your memory and we can delete the cache memory also.It is also called as RAM cache.
ii)Storing is a procedure for improving application execution.
iii)Since memory get to is a significant degree quicker than magnetic media, information is perused from a reserve a lot quicker and the application can proceed on sooner. In the event that the 
normal information isn't in the reserve (a store miss), the information can at present be gotten to from capacity

8.What is the main difference between traditional relational databases and nosql databases ?

TRADITIONAL DATABASE:

     Traditional data systems, for example social databases and information distribution centers, have been the essential way organizations and associations have put away and broke down their 
information for as long as 30 to 40 years. Traditional frameworks are planned from the beginning to work with information that has essentially been organized information.Its speed is slow 
compared to NoSql database.

NOSQL DATABASE:

     NoSQL databases give high operational speed and expanded adaptability for programming designers and different clients when contrasted with customary plain (or SQL) databases.
The information structures utilized by NoSQL databases—key-esteem, wide section, diagram, or record—vary from those utilized by social databases
NoSQL databases: MongoDB: The most famous open-source NoSQL framework. MongoDB is a record arranged database that stores JSON-like archives in powerful patterns.
Craigslist, eBay, and Foursquare use MongoDB. CouchDB: An open source, web-arranged database created by Apache.

9.Explain shortly MVC pattern in developing backend applications.
      Model View Controller is mainly used for developing modern user interfaces and developing a program for desktop or mobile as well as web applications.
i)It is one of the most frequently used industry-standard web development framework to create scalable and extensible projects.
ii)It consist of three main logical components: the model, the view, and the controller.
iii)We can easily maintain our application because of separation of their concern.

10.What is event loop in javascript ? Explain with an example

     The event loop in javascript is to look after the call stack and the call back queue.The event loop continously check the call stack to identify whether there any function to be runned.During this
 process it adds any function call it finds to the call stack and executes in an order.Each event is called a function call back.
For example. During event loop,a message will be enqueued when the user clicks on elements and event fires.When the message is dequeued its call back function is called.Incase,if the function returns 
again or throw an error,the event loop continues.

11.What is the difference between git pull and git fetch ?

Git pull:

Git Pull it will do basically fetch  and merge any new changes to your master branch and move the pointer to HEAD.
This means that pull not only downloads new data; it also directly integrates it into your current working copy files
git pull=git fetch + merge.

Git Fetch:

Git Fetch is the command that tells your local git to retrieve the latest meta-data info from the original. it will just fetch all the changes in the remote repository (Github) and 
move the origin/master pointer to HEAD.Meanwhile your local branch master will keep pointing to where it has.








