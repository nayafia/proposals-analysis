# Notes
Data collected 7/24-7/25/2018 from https://dashvotetracker.com/past.php only ("current proposals" not included)

There were more items than I was willing to hand code, so I took a sample instead (see below).

There were a few proposals that are about governance, not funding. These are labeled with *type* = "governance".

I didn't include blue proposals at the bottom of the page, where final voting deadline hadn't yet passed.

USD conversions calculated with historical data from https://www.investing.com/crypto/dash/dash-usd-historical-data

## Sample methodology
Include every 3rd item in the proposal tracker, which yields CI +/- 5.51 @ 95% confidence. (CI will be higher for subsets of this data.)

Some proposals said "please vote no/downvote this" bc they had an updated version of the proposal. In that case, I swapped the "incorrect" for the correct proposal.

If both the incorrect and correct proposals fell into my every-third count, or if the third proposal was "please downvote" because it was withdrawn, I replaced the incorrect proposal with the next proposal immediately after (but resumed counting from the original post).

If the third proposal was spam, I replaced it with the next proposal immediately after (but resumed counting from the original post).

# Key
* *title*: Title of forum thread
* *replies_count*: Number of comments on forum thread
* *date*: Date that proposal was opened
* *author*: Username of applicant
* *status*: Proposal status (approved, not_approved, active)
* *upvotes*: Number of "Yes" votes
* *downvotes*: Number of "No" votes
* *abstain*: Number of "Abstain" votes
* *aggregate_votes*: "Yes" votes minus "No" votes
* *payments_made*: Total number of payments that have been made
* *payments_total*: Total number of payments requested
* *DASH_monthly*: Monthly amount requested, in DASH
* *DASH_total*: Total amount received, in DASH
* *USD_rate*: DASH-USD conversion rate, based on value of "date" column
* *USD_monthly*: DASH_monthly_amount, converted to USD
* *USD_total*: DASH_total, converted to USD
* *type*: Type of proposal
* *type2*: Secondary type (if needed)
