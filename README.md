# Credit-Risk-Analysis
This project dove deep into the loan data of a financial company to understand why some loans were defaulting and how to improve the lending process.  I started by exploring the data, getting a sense of the different loan statuses (paid, unpaid, partly paid) and calculating the overall default rate.  It turned out that a significant portion of loans were not being fully repaid, highlighting the need for better risk management.

One key area I investigated was the timing of defaults.  I looked at the First Payment Default (FPD) rates at different intervals (0 days, 3 days, 7 days, etc.) and discovered that most defaults happened very early on, often within the first week. This suggested that there might be early warning signs in the loan applications or initial payment behavior that could help predict future defaults.

Then, I wanted to understand the loan portfolio better. I grouped the loans by their status (paid, unpaid, etc.) and analyzed the loan amounts, disbursement amounts, and total amounts to repay for each group. This helped see the financial impact of defaults and understand the characteristics of different loan categories.

Since internal scores were available I wanted to see if they could be used to predict defaults.  I looked at the distribution of these scores and tested different cutoff points to see if a minimum score could help reduce the default rate.  The goal was to find a balance between approving enough loans and minimizing the risk of defaults.

Another important factor I considered was whether a client was new or returning.  I found that returning clients had a significantly lower default rate and often took larger loans.  This made sense – if someone has successfully repaid loans in the past, they are likely to do so again.

Based on these insights, I proposed a few key lending rules.  First, for new clients, I suggested implementing a minimum internal score cutoff to reduce the risk of defaults.  Second, for returning clients with a good repayment history (for example, 3 or more successfully repaid loans), I recommended offering higher credit limits as they are less risky. Third, I suggested avoiding loans to clients with multiple users sharing the same Android ID, as this could be a sign of fraudulent activity.

Finally, I created visualizations to clearly communicate my findings.  I made a chart showing the distribution of loan statuses and another chart comparing the default rates of new and returning clients.  These visuals helped to tell the story of the data and make the insights more accessible to everyone.  The overall goal of this project was to provide data-driven recommendations to improve the lending process, reduce defaults, and ultimately make the business more profitable.
