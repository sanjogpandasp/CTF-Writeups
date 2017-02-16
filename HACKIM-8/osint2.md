## OSINT Challenge - 2  

The question was  
    ![](/HACKIM-8/images/osint2/1.png?raw=true)  
    
##Steps to Solve  

-`Hit the url. But it will give you the same challenge which was hosted for Web - 3. But there is a link to an image file which was this`

![](/HACKIM-8/images/osint2/2.png?raw=true)  

-`Start searching for 7033 on Google and you get these links`  


![](/HACKIM-8/images/osint2/3.png?raw=true)  

-`Got few results. Go and read the RFC. Spent around 1 hour, just reading the WebFinger RFC.`  
![](/HACKIM-8/images/osint2/4.png?raw=true)  

Figured out that Webfinger is a protocol where it can be used to get information about the people or other entities by using standard HTTP methods.
Then got to know how to make a webfinger query on HTTP. 
    "/.well-known/webfinger"  
    
 Went ahead and hit the given server with this query on it  
 
    http://54.89.146.217/.well-known/webfinger

which lead to  


![](/HACKIM-8/images/osint2/5.png?raw=true)  

-`Google about ssdeep , read about it. Got to know that ssdeep is a hashing algorithm.`   
![](/HACKIM-8/images/osint2/6.png?raw=true)  

Downloaded a few pre-written snippets to crack and fiddled around ssdeep but nothing worked out. Then I started googling the entire query i.e  
    SSDEEP(523bd1e47b08cfd4d92cddcbff8e541d)  
    
 ![](/HACKIM-8/images/osint2/7.png?raw=true)  
 
 and landed onto this website but then there was no luck. There was nothing related to the MD5 which I was searching for.
 
  ![](/HACKIM-8/images/osint2/8.png?raw=true)  
  
  -`Then headed to the tools section of this website and passed the MD5 hash`  
  ![](/HACKIM-8/images/osint2/9.png?raw=true)  
    
    and finally got the flag 
  ![](/HACKIM-8/images/osint2/10.png?raw=true)  
  
  ###Flag :
      flag{3072:uFvAPdnvdoz91j/q2p4N1m1QmKoEe2TE4lvrNh:uFvAPdnvdoz91rq2p4rm1QdoEe2TE4l/}  


###Credits  
- Archita Aparachita
- Shubham Mittal
- Pratap Chandra
- Chandrakant Nial
- Swaroop Yermalkar



