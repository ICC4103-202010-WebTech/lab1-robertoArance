'Please write your report here.'

**Activity**

In the following document the questions in the part 3 of the lab assignement #1 will be answered, the questions are asked from the point 3 to the point 5:

_'1) How is the list of new articles listed in **HTML**?_

In the elements observed on the page, there is a Head and Body segment, in the Body segment we can observe that the element contained is Table which is centered, inside the body of the table ("< tbody >") there aretwo kind of table rows ("< tr >") one is for the title in orange and the second one contains the news for example:


<td align="right" valign="top" class="title"><span class="rank"></span></td>      <td valign="top" class="votelinks"><center><a id="up_22630665" href="vote?id=22630665&amp;how=up&amp;goto=news"><div class="votearrow" title="upvote"></div></a></center></td><td class="title"><a href="https://www.bbc.co.uk/news/technology-51968302" class="storylink">Netflix to cut streaming quality in Europe for 30 days</a><span class="sitebit comhead"> (<a href="from?site=bbc.co.uk"><span class="sitestr">bbc.co.uk</span></a>)</span></td></tr>



_'2)Briefly describe what you see in files with names starting with **hn.js** and **news.css.** How are these files different? What is their purpose?_

.js is javascript and . css is cascade style sheet. The Javascript code includes some functions and its definitions, engaging some actions on the page and defining them, and the cascade style sheet defines some of the style and letters shown over the page.

_'3)How many requests has it taken for the browser to download the Hacker News main page? What are the HTTP request methods in each case?_

The page took 7 requests to make the refresh, all of them where type get, two of them got code 200 (OK) and the other 5 also got OK but from the storaged cache (4 from memory cache and 1 from disc cache). From the 7 requests 4 where to get images, 2 where to obtain code (the .js and the .css from the previous question) and one last to get the raw information of the news (this request was made to https://news.ycombinator.com/)


Roberto Arance