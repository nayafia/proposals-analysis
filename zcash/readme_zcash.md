# Notes
2017Q4 data collected on 7/21/2018 from https://github.com/ZcashFoundation/GrantProposals-2017Q4/issues

2018Q2 data collected on 7/23/2018 from https://github.com/ZcashFoundation/GrantProposals-2018Q2/issues, except for *status* (I made a best guess on some of them, but they're not finalized) and *replies_count*, because the final awards weren't announced yet. I'll update this data when it's available. In the meantime, I wouldn't use these columns for Q018Q2 data.

For *USD_proposed*, if a range of funding was proposed, I recorded the highest end of the range (ex. "10K to 50K" would be recorded as 50K), and the most recent approval (ex. if original proposal said 10K but was later updated to 5K, I went with 5K). For amounts, total amount wasn't clear, so I had to guesstimate a bit. Finally, I had to convert currency to USD for a few applications, in which case I used the exchange rate at the time of the proposal.

# Key
* *title*: Title of GitHub issue
* *author*: GitHub username of applicant
* *cohort*: When they applied (Q017Q4 or 2018Q2)
* *status*: Approval status (funded = approved, not_funded = not approved, not_submitted = invited to submit a full proposal, but never heard back, withdrawn = applicant withdrew their application)
* *date*: Date that proposal (i.e. GitHub issue) was opened
* *type*: Type of proposal
* *type2*: Secondary type (if needed)
* *replies_count*: Number of comments on GitHub issue
* *USD_proposed*: The final amount of funding proposed by the applicant
