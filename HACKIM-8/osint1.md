## OSINT Challenge - 1
The question was  
![](/HACKIM-8/images/osint1/1.png?raw=true)  

The idea behind solving this challenge was to read and understand the question as closely as possible.  
-`Hint :- A city between Palm Harbor and Belleair.`
###Steps to solve  

-`Search google for rocky`  
-`Search google for clear water`  
-`Search maps and locate palm harbor and Belleair`  

This is what I got after spending few minutes on google maps.

![](/HACKIM-8/images/osint1/2.png?raw=true)  

I got to know that there is a city called Clearwater. But what next ? I tried searching for the below mwntioned queries  
but no luck.  

-`Now search rocky + Clearwater + server = Nothing (no luck)`  
-`Initial thought was the latitude and longitude of this :-`  

![](/HACKIM-8/images/osint1/3.png?raw=true)  

-`Obviously did not work. But had no clue where to head next.`  
-`When in doubt read the question again.“I am not human”. I SERVE`  
-`Could be a server, no? Let’s head to shodan.`  

![](/HACKIM-8/images/osint1/4.png?raw=true)  

-`Let’s apply some filters. “US” , Clearwater`  

![](/HACKIM-8/images/osint1/5.png?raw=true)  

-`Phew! There is only result. Let’s go check it.`  

![](/HACKIM-8/images/osint1/6.png?raw=true)  

### Flag :  
    flag{ee:06:bb:c1:48:bc:64:bf:69:d3:ff:6f:b0:89:6a:84}


###Credits  
- Sagar Popat
- Archita Aparachita
- Pratap Chandra
- Chandrakant Nial
- Swaroop Yermalkar





