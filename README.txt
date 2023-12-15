This repo contains analysis for a dataset from the UCI Machine Learning repository.

The dataset contains data related to coupons for various business types presented to drivers when driving. Demographic information is available for the scenarios presented as well as whether the drier accepted the coupon in each scenario presented.

In our analysis of the data, we analyzed the Restaurant20To50 coupon category in more detail. We found that to have the best chance of success when offering this coupon type, as many as possible of the following conditions should be true:

    * passenger = "Partner"
    * time = "10AM"
    * education = "Some High School" OR "High School Graduate"
    * occupation = "Construction & Extraction" OR "Healthcare Support" OR "Office & Administrative Support" OR "Production Occupations"
    * Restaurant20To50 = as high as possible
    * maritalStatus = "Single" OR "Unmarried partner"
    * weather = "Sunny"
    * temperature = warmer weather
    * expiration = "1d"

Additional analysis is located in the Jupyter notebook which is part of this repo.
