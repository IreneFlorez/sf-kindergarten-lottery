# sf-kindergarten-lottery
Data analysis reviewing various data sources and findings on the public school kindergarten lottery in San Francisco.


To get their child into a public kindergarten in San Francisco, parents enter a lottery that blends their choices with a mysterious algorithm designed to give every child the opportunity to attend the school of their choice. A kindergartner here could be assigned to any of the city's 72 elementary schools, and further to any of the total 120 elementary school programs (some schools have more than one program, such as a general education program and a seperate bilingual program).

For the 2017-2018 school year, 4,611 children entered the San Francisco Unified School District kindergarten lottery. 

Parents can select multiple schools, and they made more than 45,000 unique choices for the first round of the 2017-2018 lottery. In addition to the first round of the lottery, parents can continue for up to five rounds in the lottery. 

Here we look at various data sources and data sets. 

* Part 1: concat_schools analysis: this notebook puts together a list of schools along with their full address, district codes, and corresponding state codes. This part uses state data, city data, and sfusd data to compile a large master list of public elementary schools. This helps us use and reconcile the data sets reviewed in part 2 and part 3. 

* Part 2: This analysis uses data from part 1 plus data wrangled by a KQED team of education reporters to review results from the 2017-2018 lottery (https://www.kqed.org/news/11641019/s-f-s-kindergarten-lottery-do-parents-tricks-work and https://github.com/pickoffwhite/San-Francisco-Kindergarten-Lottery). In addition the the baseline review done by KQED this section also, already set forth by the KQED team, this section also looks at
** those applications that listed three schools 
** the impact of zipcode and CTIP status on choices, assignments, and enrollments

* Part 3: This analysis uses data made public by SFUSD on requests and waitpools for the public elementary schools in the district for 2016, 2017, and 2018. 


Data limitations: Additional data would help ascertain how selections connect with language requirements for the bilitieracy and immersion programs. And, additional data can help assess how attendance area designation (AA) and sibling preference  designations impact assignments and enrollment. Overall, this data should be considered preliminary as it is limited and contains errors. 

See the resulting data visualization here: https://public.tableau.com/profile/irene.f8341#!/vizhome/SFUSDLottery-DRAFT/Dashboard
