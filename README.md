<a id="top"></a>
##[![ANL](https://pbs.twimg.com/profile_images/116507411/Delta_normal.jpg "ANL")](https://www.anl.gov) Samir J Yuja 
----

[![Plus](http://4.bp.blogspot.com/-LUvaFlG26y8/VLPIPu3K-RI/AAAAAAAAATM/wW2u6bkMxa4/s1600/google_button.png)](https://plus.google.com/u/0/)[^footnote1]


####Table of Contents
 1. [Pros of Markdown](#pros)
 2. [Cons of Markdown](#cons)
 3. [Sample Code](#sample)
 4. [Contact Info](#contact)
 
<a id="pros"></a>

####Pros of Markdown
+	Readability in plain text 
+	Format as you type (as opposed to pressing buttons)
	 1. Fast to learn
+	Supports inline HTML
	* HTML Embedded easily
<a id="cons"></a>

####Cons of Markdown 
1.	Abandonware (some editors support more than others)
2.	Little table support

<a id = "sample"></a>
###Sample Code 
Python code returning a list of primes less than n:
		
	def primes(n):
  	  sieve = [True] * n
   	  for i in xrange(3,int(n**0.5)+1,2):
    	    if sieve[i]:
            	sieve[i*i::2*i]=[False]*((n-i*i-1)/(2*i)+1)
  	  return [2] + [i for i in xrange(3,n,2) if sieve[i]]

<a id="contact"></a>
###`Contact Information:`

|Email:                 |Addresses:              |Phone Numbers: |
| --------------------- | :--------------------: | ------------: |
|<samiryuja@hotmail.com> |11631 NE 109th Place    |352 871 2546   |
|<samiryuja@gmail.com>   |306 Stadium Drive Apt 15|850 555 5555   |
|<sjy14b@my.fsu.edu>    |1017 Academic Way       |352 666 6666   | 



>"when you don't create things, you become defined by your tastes rather than ability. your tastes only narrow & exclude people. so create." **_why**  
>>This quote was borrowed from a [Sam Kiswani][id], TA.  
>
"Leave you your power to draw, And I shall have no power to follow..." [^footnote]

###[Top](#top) 

[id]: https://sskiswani.github.io/ "Sam Kiswani"
[^footnote]: Billy Shakes, A Midsummer Night's Dream, Act 2, Scene 1
[^footnote1]: Practice footnote