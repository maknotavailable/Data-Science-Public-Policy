### This analysis was conducted as part of a discussion board forum for MPPA 403 - Fundamentals of Public Administration at the Northwestern University School of Profession Studies, Master's in Public Policy and Administration.

### The analysis was presented as part of a short form response essay to a peer. The full text is as follows:
To answer the question how heavy-handed government regulation should be, I decided to take it back to Herbert Storing's belief that "all interesting administrative questions are political questions" (Morgan, et al., 2010). From this perspective, the extent of government regulation is a question of party identity and politics. It is commonly understood that "Republicans want less government interference by regulation" and "Democrats want greater protection through regulation, " and I sought to examine this belief in the General Social Survey.
<br><br>First, I examined the distribution of opinions regarding government regulation. The most common response was "In favor" of less government regulation of business at just over 16 percent (“Get GSS Data | NORC,” n.d.).
![Alternate image text](https://github.com/rchardptrsn/Data-Science-Public-Policy/blob/master/Logistic%20Regression%20-%20Corruption%2C%20Regulation%2C%20and%20Political%20Party/GSS%20-%20Less%20Government%20Regulation.png)
<br><br>Next, I looked at the distribution of opinions about the corruption of government administrators. This is important to consider as whether or not you believe government administrators are corrupt should inform your belief in their ability to impartially enforce regulations. The logic on this statement has not been tested by me, but it feels like common sense, and in this space I will continue with it as a factor. The GSS shows that over 17.5 percent of respondents believe there are "some" corrupt government administrators (“Get GSS Data | NORC,” n.d.).
![Alternate image text](https://github.com/rchardptrsn/Data-Science-Public-Policy/blob/master/Logistic%20Regression%20-%20Corruption%2C%20Regulation%2C%20and%20Political%20Party/GSS%20-%20Less%20Government%20Regulation.png)
<br><br>To understand the role of political identification and beliefs about government corruption, I used the GSS variable for political party ID (PARTYID) and grouped responses to just Democrat or Republican. Support for less government regulation of business can be boiled down to a classification problem of "for" or "against," and a logistic regression model can be quite useful for analyzing different variables on the outcome of the classification. For this analysis, my independent variables were party ID (nominal) and beliefs about corruption (ordinal). The dependent variable being classified was for or against less government regulation of business.
<br><br>What I found was that political party affiliation was a greater predictor of support for less government regulation than beliefs about corrupt government administrators. Republicans were more than six times more likely than Democrats to support less government regulation. However, the belief that "Almost none" of government administrators were corrupt did result in a negative coefficient towards support for less regulation, and beliefs that "Almost all" government administrators were corrupt resulted in the second strongest coefficient. This shows that for Americans that participated in the 2016 GSS Survey, political party was the greatest indicator of support for less government regulation.

<br><br>
References
 
Get GSS Data | NORC. (n.d.). Retrieved November 17, 2019, from The General Social Survey website: https://gss.norc.org/Get-The-Data

Morgan, D. F., Kirwan, K. A., Rohr, J. A., Rosenbloom, D. H., & Schaefer, D. L. (2010). Recovering, Restoring, and Renewing the Foundations of American Public Administration: The Contributions of Herbert J. Storing. Public Administration Review, 70(4), 621–633.