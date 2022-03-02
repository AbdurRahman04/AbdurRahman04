# Conents
## [1-Heading](#1-headings)
## [2-Block of words](#2--block-of-words)
## [3-Line Breaks](#3-line-brakes)
## [4-combination of two things](#4-combines-two-things)
## [5-Face of text](#5--face-of-text)
## [6-Bullet point list](#6--bullet-points--list)
## [7-Line Breaks and page breaks ](#7--line-breaks-or-page-brakes)
## [8-Link and hyper link ](#8--link-and-hyperlink)
## [9-Image and figure with the help of link ](#9--images-and-figurs-with-link)
## [10-Adding codes and code block ](#10--ading-codes-or-codes-block)
## [11-Adding Table ](#11--addings-table)

# 1-Headings 
How to give headings in markdown file?
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# 2- Block of words 
this is a normal text in mmarkdown

> this is a block of special text
>
> This is the scond block of special text 

## Note:- 

 
- for marking special text we use  >  sign 

# 3-Line breaks

This is the 40 day long course of  data science. 

 
This is the 40 day long course data science with python AKA as python ka chilla with baba ammar.\
This is the second line


## Note:-
**In markdown language for giving the kine break we use  \ or press the space two time**

# 4-Combines two things  

Block of words and heading 

>## Headding 2

# 5- Face of Text 

- **Bold**
- *Italic*
- **Bold and atalic** 
  
  or you can use these symbles 
- _ (underscore )

     __data fram__
- single underscore is used to ittalic the words \
_abdur rahman_

# 6- Bullet points / List

- DAY 1
- DAY 2
- DAY 3
- DAY 4
    - DAY 4 A
        - SUB LIST 
    - DAY 4 B

> **using * or +**

* one
+ two 

> Numbring of the list 

1.  day 1
1.  day 2
1.  day 3
1.  day 4
    1. day 4 a
    2. day 4 b
1.  day 5
1.  day 6
1.  day 7
1.  day 8

# 7- line breaks or page breaks 

ali is a good boy.

--- 
___
***
he goes to school

# 8- Link and Hyperlink 


## First Method 

[The google seach is ](https://www.google.com/search?q=pakistan&rlz=1C1GCEA_enPK985PK985&oq=pakistan&aqs=chrome..69i57j0i271l2j69i61j69i65l2.2239j0j15&sourceid=chrome&ie=UTF-8)

## 2 nd method Hyper link 
<https://www.google.com/search?q=pakistan&rlz=1C1GCEA_enPK985PK985&oq=pakistan&aqs=chrome..69i57j0i271l2j69i61j69i65l2.2239j0j15&sourceid=chrome&ie=UTF-8>


## 3 rd method 
click [here](https://www.google.com/search?q=pakistan&rlz=1C1GCEA_enPK985PK985&oq=pakistan&aqs=chrome..69i57j0i271l2j69i61j69i65l2.2239j0j15&sourceid=chrome&ie=UTF-8) 
to watch 


[codanics]:https://www.google.com/search?q=pakistan&rlz=1C1GCEA_enPK985PK985&oq=pakistan&aqs=chrome..69i57j0i271l2j69i61j69i65l2.2239j0j15&sourceid=chrome&ie=UTF-8


The whole search is [here][codanics]

# 9- images and figurs with link 

To see the log of islamia university click below:
![pic](a2.png)


> Task: how to comment out in markdown line\
>and its short cut 

<!--abd ur rahman-->
<!-- helo --> ctrl+k+u
<!-- hy --> shif+alt+a 

Online Piciute 

same as hyper link

# 10- Ading codes or codes block 

To print a string use `print("codanics")`

use to spreat command from the text use back comma `.

`helo('baba g ki hal chal nay')`


> for block of code 


> ##  This is the bar plot graph of ***Titanic*** data using python 

```python
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
boat=sns.load_dataset("titanic")
sns.barplot(x="sex",y="alone",hue="who",data=boat,order=["female","male"])
plt.show()
```
![](a3.png)


# 11- Addings table

| species | patel_lenght |sepal_lenght|
| ------- | :-----:        | :------:    |
| vergini  |    23.2             |18.85
| setosa |    21.2             |8
| versicolo  |    28.2             |17
| vergini  |    23.2             |18.85
| setosa |    21.2             |8
| versicolo  |    28.2             |17| 
| setosa |    21.2             |8
| versicolo  |    28.2             |17| 
| setosa |    21.2             |8
| versicolo  |    28.2             |17



