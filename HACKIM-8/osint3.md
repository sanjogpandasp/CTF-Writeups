## OSINT Challenge - 3
The question was  
![](/HACKIM-8/images/osint3/1.png?raw=true)  

I was very sure that I will this challenge with minutes as the username=JaneStyle was given  
and also the date of compromise was given i.e 25th April 2015. BNever expected this to be difficult.  

###Steps to Solve  

-`Search for JaneStyle on Google. I got lots of links written in Japanese.  

![](/HACKIM-8/images/osint3/2.png?raw=true)  

-`After spending a lot of time and using various kind google dorks triks also, it did not yield juicy result.  
Apart from google you have various search engines. Tried there too, but failed.`  

-`Key to OSINT is keep searching different places like Github, google, twitter, facebook, pastes, Gist, stackoverflow, reddit, darknet.`  
-`Started searching for some pastes.`  

![](/HACKIM-8/images/osint3/3.png?raw=true)    

-`Got one occurrence on google with pastebin and janestyle`  

![](/HACKIM-8/images/osint3/4.png?raw=true)  

-`Close look on those gave me some juicy information. Got some AppKey and HMKey. Searched for Appkey on google and github got nothing.`  

![](/HACKIM-8/images/osint3/5.png?raw=true)  

-`No Worries. Then headed to gist. Search for the same Appkey. 1 hit.`  

![](/HACKIM-8/images/osint3/6.png?raw=true)  

-`Get into the user. Anonymous.  
Go to the stars which are given and check who all have given stars`  

![](/HACKIM-8/images/osint3/7.png?raw=true)  

-`Go to this guy’s github account and check the details`  

![](/HACKIM-8/images/osint3/8.png?raw=true)  
![](/HACKIM-8/images/osint3/9.png?raw=true)  

    Well, we got some pointers here. The profile says “Feel free to connect over social media”  
    
-`Now search this guy over google. We get nothing.`  
 ![](/HACKIM-8/images/osint3/10.png?raw=true)  

-`Seems like this is a username. Head to people finder website. A popular one “pipl.com”`  

 ![](/HACKIM-8/images/osint3/11.png?raw=true)  

- `We got some twitter handles. Goto twitter and get this guys searching.`  

 ![](/HACKIM-8/images/osint3/12.png?raw=true)  

-`There is a tweet where he tweeted.`  
    “ Finally home. Phew.”  
    
Open the tweet. Voila !
 ![](/HACKIM-8/images/osint3/13.png?raw=true)  
 
 
###Flag:  
    flag{Akishima-shi}  
    
    
    
###Credits  
- Sagar Popat
- Archita Aparachita
- Pratap Chandra
- Chandrakant Nial
- Swaroop Yermalkar

















