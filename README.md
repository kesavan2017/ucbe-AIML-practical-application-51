# ucbe-AIML-practical-application-51
UC Berkeley Engineering - Practical Application 5.1 

## Summary of findings from analysis
**Findings**

##### Problem 1 (Data Cleaning / Analysis)
1. Data cleaning resulted in one feature with a high rate of poor / unusable data (~ 99% - Feature = Car - this feature had details of driver vehicle )
   1. Action was to drop the column from the data set
2. NaN values were low for features stating number of visits to various venues in the data set (all under 1.5%)
   1. Action taken to replace NaN with "unknown" string and keep all data as the rows will still contain acceptance rate data in the "Y" feature that is maintained.  Care taken to consider this as an added category in exercises (filtering datasets)

##### Problem 2 (Bar Coupon Analysis)
1. General observations about the Bar Coupon acceptance reate overall : 
    - 41% of the bar coupons were accepted per observations and 59% declined for the bar coupon based upon observations 
2. Characteristics of drivers that impact the acceptance rates of Bar Coupons tend to be the following:
    - Drivers under 25 tend to have a very high acceptance rate for Bar Coupons *100% Acceptance Rate* and Drivers under 30 also have fairly high *72% Acceptance Rate*
    - Drivers with income lower than 50K tend to frequenting cheap restaurants tend not to accept Bar Coupons (~ 45% acceptance rate)
    - Drivers with no child passangers tend to have a high acceptance rates when alone or with adult companion(s) (~ 71% acceptance rate)
    - As one would expect, drivers with kids don't accept bar coupons as well given the age restrictions for entrance into bars ()


## High level summary 
**Executive summary**

##### Based Upon the analysis conducted on Bar Coupons there are some observations to help develop a campaign targetted at the optimal auidence for any marketing / promotional coupons

1. General observations about the Bar Coupon acceptance reate overall : 
    - 41% of the bar coupons were accepted per observations and 59% declined for the bar coupon based upon observations 
2. Characteristics of drivers that impact the acceptance rates of Bar Coupons tend to be the following:
    - Drivers under 25 tend to have a very high acceptance rate for Bar Coupons *100% Acceptance Rate* and Drivers under 30 also have fairly high *72% Acceptance Rate*
    - Drivers with income lower than 50K tend to frequenting cheap restaurants tend not to accept Bar Coupons (~ 45% acceptance rate)
    - Drivers with no child passangers tend to have a high acceptance rates when alone or with adult companion(s) (~ 71% acceptance rate)
    - As one would expect, drivers with kids don't accept bar coupons as well given the age restrictions for entrance into bars ()

Based upon the analysis above, the ideal campaign for owners of Bars would be to target the following groups for maximum coupon acceptance rates of their coupons:
- Drivers that tend to visit the Bars and are familar with their respective Bar (multiple visits / month) show high correlation in acceptance of Bar Coupons received 
- Drivers that are under 30 with adult companions and no children in the vehicle tend to be a good target auidence for Bar Coupon promotions with a the highest acceptance rates for the Bar Coupons. 
- Drivers about 50k income would also be a good target group given frequening Bars tends to be an expensive outing and less likely for more conservatives in the 50k or below income range.