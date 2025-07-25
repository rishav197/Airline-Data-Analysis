# Airline-Data-Analysis

## Business Problem 

Airline companies operate a diverse fleet of airplanes from small jets to medium sized 
ones and have been offering good quality air travel services for a long time. Their 
primary goal is to make sure passengers have safe and comfortable, and convenient 
flights. But now they are facing challenges due to various factors like  

- New environmental rules are stricter 
- Taxes on flights have gone up 
- Increase Interest rates (so borrowing money is more expensive) 
- Fuel prices have increased 
- It’s harder to find workers in a tight labour market as wages rising  

As a result, it is harder for airlines to earn good revenue. To solve this, they want to look 
at their data and figure out how to fill more seats on each flight (increase the 
“occupancy rate”). If more seats are sold per flight, they can make more profits from 
each trip and improve their overall profits.  


FIGURE0_IMAGE


## Main Challenges 

- **Stricter Environmental Regulations :** The airline industry is under growing 
pressure to reduce its carbon emission. As a result, stricter environmental 
regulations have been introduced, leading to higher compliance costs, 
operational restrictions and limited room for fleet expansion.  
- **Rising Flight Taxes :** To address climate concerns and boost government 
revenue, many countries are imposing heavier taxes on air travel. These 
increased taxes raise the overall cost of operations, which may reduce customer 
demand and hurt profitability.  
- **Tight Labor Market and Rising Labor Costs :** The aviation industry is facing a 
shortage of skilled professionals, such as pilots, engineers, and maintenance 
staff. This talent gap has driven up wages and turnover rates, making it harder to 
maintain consistent staffing levels while managing personnel expenses. 


## Objectives

- **Increase Occupancy rate :** Fill more seats on each flight to boost average profits 
per seat and reduce the impact of rising costs. 
- **Optimize Pricing Strategy :** Create a smart pricing plan that reflects market trends 
and customer needs to attract and retain customers.  
- **Enhance Customer Experience :** we need to focus on the entire experience from 
booking to arrival as smooth and enjoyable as possible to stand out from competitors 
and build customer loyalty.  
The ultimate goal of this task would be to identify opportunities to increase occupancy 
rate on low-performing flights, which can ultimately lead to increased profitability for the 
airline.


## Basic Analysis  

The initial data analysis offers key insights into our fleet and revenue trends. It highlights 
the number of aircraft with over 100 seats, tracks how ticket bookings and total revenue 
have changed over time, and reveals the average fare per aircraft under different fare 
conditions. 
These insights are valuable for identifying opportunities to increase occupancy rates 
and optimize pricing strategies for each aircraft type. 
Table 1 provides a breakdown of aircraft with more than 100 seats, along with their 
exact seat capacities. 


<!-- TABLE1_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/table1.jpg" alt="Table1" width="400"/>


To better understand trends in ticket bookings and the resulting revenue, we used a line 
chart visualization. The analysis revealed a steady increase in ticket bookings from 
June 22 to July 7, followed by a relatively stable period from July 8 through August. A 
clear peak is observed during this period(maybe due to a nearby festival), marking the 
highest number of tickets booked on a single day. Since revenue is closely linked to 
ticket sales, the revenue trend closely mirrors the booking trend over this time period.  
These findings indicate that analyzing the factors behind the booking peak could uncover 
valuable insights to help boost overall revenue and improve operational planning. 

<!-- FIGURE1_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure1.png" alt="figure1_img" width="1000"/>

<!-- FIGURE2_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure2.png" alt="figure2_img" width="1000"/>

After calculating the average fare for each aircraft under different fare conditions, we 
created a bar chart to visually compare the results. Figure 3 illustrates the average fares 
for three classes: business, economy, and comfort. Notably, comfort class is only 
offered on the 773 aircraft, while CN1 and CR2 provide only economy class fares. 
Across all aircraft, business class consistently shows higher average fares than 
economy class, highlighting a clear pricing hierarchy regardless of the aircraft type. 
These insights can guide fare optimization by understanding which aircraft and fare 
combinations offer the greatest pricing leverage.

<!-- FIGURE3_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure3.png" alt="figure3_img" width="1000"/>


## Revenue and Occupancy Analysis 
 
To improve profitability, airlines need to closely examine their revenue streams. Two key 
metrics to consider are: 
1. Total yearly revenue 
2. Average revenue per ticket per aircraft 
By analyzing these, airlines can identify which aircraft types and routes bring in the most 
income. This helps in making informed decisions about pricing, scheduling, and 
resource allocation. 

Figure 4 shows total revenue, number of tickets sold, and average revenue per ticket for 
each aircraft. 

The SU9 aircraft generated the highest revenue. From earlier analysis (Figure 3), we 
know that SU9 has the lowest prices for both business and economy class, which may 
have attracted more passengers. On the other hand, CN1 earned the least revenue, 
likely because it only offers low-cost economy class and may have limited features or 
comfort.

<!-- FIGURE4_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure3.png" alt="figure3_img" width="1000"/>

**Occupancy Rate Insights :** 
Another crucial metric is the occupancy rate, which tells us how well the seats on an 
aircraft are being filled. It's calculated as: 
Occupancy Rate = (Booked Seats / Total Seats)*100 
Higher occupancy means fewer empty seats, leading to better revenue and lower cost 
per seat. 

Figure 5 shows the average occupancy for each aircraft. This metric helps airlines 
identify opportunities to boost load factors through better scheduling, pricing, or service 
improvements.  

<!-- FIGURE5_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure3.png" alt="figure3_img" width="1000"/>

**Impact of Increasing Occupancy :**
To explore the potential upside, we simulated a 10% increase in occupancy across all 
aircraft. The result, shown in the next figure, demonstrates a clear increase in total 
revenue. 
This suggests that even a small improvement in occupancy can significantly boost 
profitability. Therefore, airlines should focus on optimizing pricing strategies and 
operations to drive higher seat utilization.


<!-- FIGURE6_IMAGE -->
<img src="https://github.com/rishav197/Airline-Data-Analysis/blob/main/plots-and-images/figure6.jpg" alt="figure6_img" width="600"/>


## Conclusion 

In summary, analyzing key revenue metrics such as total yearly revenue, average 
revenue per ticket, and average occupancy per aircraft is essential for improving airline 
profitability. These insights help identify areas for improvement and guide better pricing 
and route decisions. 
One of the most effective ways to increase profit is by improving occupancy rates, as 
filling more seats boosts revenue and reduces losses from empty ones. However, 
pricing needs to be carefully adjusted, too high or too low fares can both reduce 
demand. Prices should reflect the condition and service level of each aircraft, offering a 
fair value to passengers. 
Importantly, efforts to increase occupancy must not compromise customer satisfaction 
or safety. Airlines should aim for a balance between profitability and service quality. 
By using a data-driven approach to optimize pricing and operations, airlines can stay 
competitive and achieve sustainable growth in the long run.
