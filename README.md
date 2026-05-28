# Will the Customer Accept the Coupon?

## Objective

This project is focused on analysing chances of drivers accepting coupons delivered to them. It uses data from UCI Machine Learning Repo. 

## Dataset

The dataset contains 12,684 survey responses describing driving scenarios (destination, time, weather, passengers) and whether the driver accepted the coupon. There are five coupon types: bars, coffee houses, carry out & take away, cheap restaurants, and expensive restaurants ($20-$50).

## Key Findings

### Overall
- **56.93%** of all coupons were accepted
- Coffee House has most number of coupon distribution

### Bar Coupons (41% acceptance rate)
- Drivers who accepted bar coupons tend to be 1) frequent bar visitors 2) Over 25 years old 3) Not travelling with children 4) not widowed. 
- ~77% of the drivers who goes to bar more than once a month are likely to accept the coupon.  
- The strongest predictor of bar coupon acceptance is existing bar visit behavior

### Coffee House Coupons (50% acceptance rate)
- Key Findings for Coffee House coupons are 1) Nuber of visits to the coffee shop is god indicator.
- Driver with 1 to 3 times a month visit are willing to accpet te couon by close to 60% time
- Same goes for time of day. 64% drivers are liekly to accept the coupon at 10AM. 
- interesting to see people with age less than 21 are likely to accepts che coupon - ~65% chance
- If coupon expiration is out by a day, chances are higher compared to 2 hr coupon expiration

## Recommendations

1. Target existing customers — frequent visitors are 3x more likely to accept
2. Time delivery strategically — morning for coffee, evening for bars
4. Use longer expiration windows — reduces pressure, increases acceptance
5. Consider age demographics — younger drivers are more responsive to coupons

## Files

- `prompt.ipynb` — Complete Jupyter notebook with analysis and visualizations
- `data/coupons.csv` — Source dataset from UCI ML Repository

## Tools Used

- Python (pandas, numpy)
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook
