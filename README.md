# USS pension calculations

(December 2023)

Analysis of benefits/returns from the proposed USS scheme from April 2024

## Introduction
The USS scheme has two main parts: a defined benefit (DB) part that promises a certain payment in retirement plus a cash lump sum, and a defined contribution (DC) part where payments in are invested and the amount available in retirement is the value of these investments at that time. There is no option about which to pay into - a proportion of salary below a threshold is paid into the defined benefit part and a proportion of salary above goes to the defined contribution part.

For comparison, I consider the expected pension for someone paying their USS contribution into a self-invested personal pension (SIPP) instead (not getting the employer contribution or national insurance relief), and buying an inflation-linked annuity at retirement age (for comparability with getting a pension from USS). The cost of private income protection insurance comparable to what the USS provides is subtracted from the SIPP contributions.

For both the USS DC part and SIPP investor, I consider someone using a fairly "moderate" 60% stocks/40% government bond portfolio and someone investedfor "high growth" in 100% equities. Note the actual return may differ substantially from the expected return and this isn't considered. (The DC fund options include 100% equities funds and other mixed asset or bond funds, and a 60% stocks/40% bond portfolio's expected return should sit somewhere in the range of expected returns from these funds, but doesn't correspond to any one in particular.) The USS DC part is assumed to grow at the same rate as investments into the SIPP and have the same charges (but benefit from having the added employer contribution and NI relief). Results for the expected pension payments are considered for the case assuming constant asset allocation through to retirement ageand with derisking in the final 10 years.

For ease of comparison, the USS DB cash lump sum and USS DC parts are assumed to be used to purchase a single lifetime inflation-linked annuity for someone at retirement age (with 5.5% yield, the best available on a comparison site). For simplicity it is assumed that all future USS DB payments increase following inflation, approximating that the inflation caps do not come into play (which will overestimate the expected USS pension). Expected investment returns in the DC scheme and personal pension are set to USS projections (4.1% for stocks, 0.6% for government bonds and 0.7% for cash, minus 0.1% for assumed investment costs for stocks and bonds).

I have also added calculations of the expected bequest that would be left to inheritors if the USS pension were reinvested for growth and SIPP investments were left invested.

Equations and calculations are included in the Jupyter notebook contained in this repo, in the form of python3 code. The calculations contained therein are simplified and are not meant to be precise – they’re just to illustrate some main qualitative points.

