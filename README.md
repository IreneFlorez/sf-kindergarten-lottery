# sf-kindergarten-lottery
Data analysis reviewing KQED data and findings on the public school kindergarten lottery in San Francisco

4,611 children entered the 2017-2018 San Francisco Unified School District kindergarten lottery. Parents can select multiple schools, and they made more than 45,000 unique choices. 
This Jupyter Noteboook reviews data analyzed by KQED for this news article: https://www.kqed.org/news/11641019/s-f-s-kindergarten-lottery-do-parents-tricks-work, using this base workbook: https://github.com/pickoffwhite/San-Francisco-Kindergarten-Lottery

In addition the the baseline review, already set forth by the KQED team, this project looks at 
* those applications that listed three schools 
* the impact of zipcode and CTIP status on choices, assignments, and enrollments

Data limitations: Additional data would help ascertain how selections connect with language requirements for the bilitieracy and immersion programs. And, additional data can help assess how AA and sibling preference impact assignments and enrollment. 

Part 1: concat_schools ipynb notebook, this notebook puts together a list of schools along with their full address, district codes, and corresponding state codes. 
Part 2: KQED ipynb data analysis notebook, this notebook uses data from part 1 plus data wrangled by a KQED team of education reporters to review results from the 2017-2018 lottery. 
