# I'm tired of all these datascrubbing Pandas in this datascrubbing Rideshare Service!
Module 5 Challenge

## Overview of Project
This project was initialized to provide V. Isualize and their team (henceforth referenced as 'Pyber') with a full breakdown of the 2019 rideshare data collected on their drivers operating in Rural, Suburban, and Urban service areas. The analysis covers the aggregation, sorting, and presentation of the data provided in single category and combined format; The charts contained herein show, respectively, the percent split of drivers by city type, the percent division of total fares by city type, variability of fares over a determined period of time, and more.

### Purpose

When running a business, it's prudent to know where the money comes from, and where it needs to go. That sounds like a loading screen, but really at the bottom of it all is a need to shore up weak areas and maintain those that are strong. The objective of this report and attached charts is intended to show exactly that: which operating areas bring in the most money, which areas may need to be looked at, and which are actively hindering company growth. While the grand majority of this report is an executive-level overview, also contained within the data is a breakdown of all cities individually, and could be separately analyzed for even more targeted campaigns by locale.

There are a couple areas specifically I would like to draw attention to, chiefly the combined DataFrame shown below:

<img width="648" alt="Screenshot 2022-12-04 at 10 49 27 AM" src="https://user-images.githubusercontent.com/116296092/205509446-491cf464-c727-4610-8f71-1fc026ce4652.png">


and the bubble scatter chart showing all of that combined data visually:

![all_rideshare_data_bubble](https://user-images.githubusercontent.com/116296092/205509461-ca98a635-0c76-45f1-a8e5-a310a0ecf22f.png)

In both of these we can see the same relationships in the service areas, but one is better for a planning presentation than the other. The combined data chart is very good at showing the direct, raw numbers, but isn't great at showing that value's impact on the entire company. Going off of just the DataFrame, one could infer that rural drivers are paid out disproportionately compared to the other types, and that their data should have a bigger impact than it does on the set as a whole. On the other hand, the bubble graph shows us that the Urban area has the most drivers and incoming money by far (regardless of it's much lower per-driver average), entirely dwarfing Rural's high per-driver and per-ride values. 

This is a perfect example of why having more than one way to present the data is critical: being able to show the base numbers and then something a little more visually digestible with those numbers in mind makes for a far easier time grasping of the data, and allows for faster and better informed business and strategy decisions on the part of the board.

## Analysis of City Types

Considering again the DataFrame above, we can break the data down as follows:

- Urban operating areas have the lowest per-ride fare, at $24.53, and the most drivers and rides by a significant margin.
- Urban Areas provide the backbone of Pyber's revenue stream.
- Suburban operations are underpinned by a solid contribution to the revenue stream, at 26.3% ($19,356.33). The driver count is modest, at roughly 20% of Urban counts.
- Suburban drivers's per-ride fares are double Urban's, with a much better ride:driver ratio. This is likely more attractive for these drivers that fall into the Suburban operating areas.
- Rural operating area fares are far higher than Suburban and Urban fares, which likely has to do with operation range and potential inavailability of drivers.
- Rural areas technically have the best ride:driver ratio, but the fact that per-driver rates are more than triple Urban's and average fares are close to Suburban's may mean a re-evaluation of the service area boundaries, as it only brings 6.8% of the total revenue in and would potentially be better served with a smaller focus, which could allow faster service times and higher overall revenue long-term.
## Recommendations

Based on the analysis, attached documents, and data above, I present a few recommendations:

- Suburban areas could be targeted with a dedicated temporary fare-reduction camapign to increase interest in Pyber, generating future contracts; the average ride fare is closer to Rural rates than to Urban and this may be a contributing factor in the section's future growth. This becomes especially potent if coupled with the second recommendation:

- Rural areas may need to be restructured to accomodate a wider sample of Suburban drivers, if not rolled into Suburban's category entirely. This not only increases the ride:driver ratio for that category, but paired with the similar ride fares, it would mean greater accessibilty to drivers for riders, and riders for drivers alike, with little increase in per-ride costs and a minor reduction in per-driver average numbers for annexed Rural drivers.

- Similarly, Urban ares may need a minor restructure to designate more drivers as Suburban, bringing up the overall per-driver Urban fares and normalizing average per-ride fares across the company, which in turn provides greater long-term stability and less volatile fares per area, increasing public interest in Pyber as an affordable and easily accessible service.