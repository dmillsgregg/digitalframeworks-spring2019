# Mexico paid back more than $1 billion in US aid

From 2010 to 2019, Mexico paid back about $1.029 billion of the nearly $2.6 billion it's received in U.S. Aid, which begs the question of how much aid is the United States sending out as loans to countries in need of monetary support?

## Interview a dataset

I chose the U.S. A.I.D. [website](https://foreignassistance.gov/) and downloaded a csv file downloaded from the site's [page](https://foreignassistance.gov/explore/country/Mexico) on Mexico to see what kind of aid we are sending to our southern neighbors.
My first question about the dataset is for the staffer who grabs all this information. Is the department sending the amount or is the department taking any of these dollar amounts Congress passed in its budget? I know from past experience, what happens in reality isn't always what was laid out in law. I would also want to ask the staffer: What's the difference between a commitment and disbursement?
My third question is why some of the entries in column T, "Award_Transaction_Value" are negative. I would want to confirm if this is paying back previous aid that was dispensed as a loan.

For the excel document I created from downloading the csv file, I hid unrelevant comments columns, like ID numbers, and resized the columns so I could easily glance through the information. To address the negative amounts brought up in my last question, I sorted the T column from smallest to largest, and then added a few blank rows after the negative numbers to find their sum. I used the simiple equation of "=sum(T2:T10377)" and then skimmed the data to confirm the years included in that amount. I tallied the positive amounts the same way to get total the country's recieved over the years.

See USAID_Mexico upload for reference.
