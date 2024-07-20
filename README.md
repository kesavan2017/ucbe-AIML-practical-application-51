# ucbe-AIML-practical-application-51
UC Berkeley Engineering - Practical Application 5.1 

## Summary of findings from analysis
**Findings**

#### Problem 1 (Data Cleaning / Analysis)
1. Data cleaning resulted in one feature with a high rate of poor / unusable data (~ 99% - Feature = Car - this feature had details of driver vehicle )
   -  Action was to drop the column from the data set
2. NaN value percentage for features stating number of visits to various venues in the data set (all under 1.5%)
   -  Action taken to replace NaN with "unknown" string and keep all data as the rows will still contain acceptance rate data in the "Y" feature that is maintained.  
   -  Care taken to consider this as an added category in exercises (filtering datasets)

#### Problem 2 (Bar Coupon Analysis)
1. General observations about the Bar Coupon acceptance rate overall : 
    - 41% of the bar coupons were accepted per observations and 59% declined for the bar coupon based upon observations 
2. Characteristics of drivers that impact the acceptance rates of Bar Coupons are the following:
    - Drivers under 25 have a high acceptance rate for Bar Coupons *100% Acceptance Rate* and Drivers under 30 also have a high *72% Acceptance Rate*
    - Drivers with income lower than 50K tend to frequenting cheap restaurants and have a low acceptance rate for Bar Coupons (~ 45% acceptance rate)
    - Drivers with no child passangers have a high acceptance rates when alone or with adult companion(s) (~ 71% acceptance rate)
    - Drivers with kids don't accept bar coupons given the age restrictions that exist for entrance into bars

#### Independent Analysis (Carry Out & Take Away Coupon Analysis)
1. Passengers that were driving alone tend to have a rate that is very high and equal to those that drive  with passangers.
2. Drivers going home or to a destination that is not urgent have a high combined acceptance rate compared to those that have a destination of work.
3. Direction does not seem to matter much when it comes to acceptance rates of this coupon - rates of acceptance are close irrespective of destination in the same direction as coupon venue (70% acceptance ) vs. destination in the opposite direction of the coupon venue (75% acceptance)
4. Drivers going to work have a greater acceptance rate when distance to coupon venue is 25m (74%) as compared to 15 min (60%) - more investigation of other features required to understand why 25m distance to coupon has a better acceptance rate than 15m distance to coupon.  

## High level summary 
**Executive summary**

#### Recommendations: Bar Coupon Acceptance 

##### Based Upon the analysis conducted on Bar Coupons there are some observations to help develop a campaign targetted at the optimal auidence for any marketing / promotional coupons
- Drivers that tend to visit Bars frequently (multiple visits / month) show a high acceptance of Bar Coupons received 
- Drivers that are under 30 with adult companions and no children in the vehicle show a high acceptance rate of Bar Coupons received. 
- Income range below 50k and behavior of attending cheaper restaurants frequently would tend to be a poor group to send bar coupons to. 

#### Recommendations : Carry Out & Take Away Coupon Acceptance  

##### Based Upon the analysis conducted on Carry Out & Take Away  Coupons there are some observations to help develop a campaign targetted at the optimal auidence for any marketing / promotional coupons
- Drivers that are heading home or have no urgent place to go have a high acceptance rate of 77% (this could be evenings upon returning from work or the weekends to sent coupons to drivers) - acceptance rate for this group was 12% greater than those going to work. 