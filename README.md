This is the final Project for EECSE 6893 Big Data Analytics Fall 2016. Our group members are XiangbingJi(xj2178), Jingyi Yuan(jy2736), Xinzhe Yu(xy2282). Our topic is NYC Taxi data analysis. 

###Usage:

The front-end is all wrapped in the front-end folder. You can clone the repo and run localhost in the front-end folder's index.html to test the front-end. 

The src contains all the code for the back-end including EM for GMM, random forest, pickups validation. You will need to first run the data reorganization.ipynb before running the back-end code.

We also implemented our own version of EM algorithm in matlab, which is in the /src/GMM/EM for GMM.m.

The data folder has two files. One is the output for the GMM model and another is the overall statistics for the D3 visualization.

The dataset link:http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

###How to visit our APP:
The front-end is also deployed on the AWS cloud, you can check our front-end by the link: http://big-data-2016-1298.s3-website-us-east-1.amazonaws.com/#/  Click on the navgation bar to choose among different sections. You can find detailed explanation of our website in our Youtube video.

Copyright@XiangbingJi,JingyiYuan,XinzheYu 2016
