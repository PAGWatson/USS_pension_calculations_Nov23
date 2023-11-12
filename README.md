# USS pension calculations

(November 2023)

Analysis of benefits/returns from the proposed USS scheme from April 2024

## Introduction
The USS scheme has two main parts: a defined benefit (DB) part that promises a certain payment in retirement plus a cash lump sum, and a defined contribution (DC) part where payments in are invested and the amount available in retirement is the value of these investments at that time. There is no option about which to pay into - salary below a threshold is paid into the defined benefit part and salary above goes to the defined contribution part.

For comparison, I consider the expected return for someone paying their USS contribution into a self-invested personal pension (SIPP) instead (not getting the employer contribution or national insurance relief), and buying an inflation-linked annuity at retirement age (for comparability with getting a pension from USS).

For both the USS DC part and SIPP investor, I consider someone using a fairly "moderate" 60% stocks/40% government bond portfolio and someone invested "aggressively" in 100% equities. Note the actual return may differ substantially from the expected return and this isn't considered. (The DC fund options include 100% equities funds and other mixed asset or bond funds, and a 60% stocks/40% bond portfolio's expected return should sit somewhere in the range of expected returns from these funds, but doesn't correspond to any one in particular.) The USS DC part is assumed to grow at the same rate as investments into the SIPP and have the same charges (but benefit from having the added employer contribution and NI relief). Assuming constant asset allocation through to retirement age is a simplification and results are just meant to be illustrative.

For ease of comparison, the USS DB cash lump sum and USS DC parts are assumed to be used to purchase a single lifetime inflation-linked annuity for someone at retirement age. For simplicity it is assumed that all future USS DB payments increase following inflation, approximating that the inflation caps do not come into play.

Equations and calculations are included in the Jupyter notebook contained in this repo, in the form of python3 code. 
