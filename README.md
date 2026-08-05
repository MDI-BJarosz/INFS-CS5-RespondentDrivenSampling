# INFS-CS5-RespondentDrivenSampling
Code to analyze survey responses to illustrate that respondent-driven sampling may be a way to efficiently collect data for otherwise hard-to-reach subpopulations
Data Availability Statement: Data used in the analyses are partially available through ICPSR as follows. Note that due to potential identifiability and privacy issues, some variables (e.g., the link between the recruiters and recruits) are either available through a restricted file or unavailable. 

- PATH 2017: Lee, S., & Roddy, J. (2021). Project Positive Attitudes Towards Health, Michigan, 2017. ICPSR37957-v1. Ann Arbor, MI: Inter-university Consortium for Political and Social Research [distributor], 2021-3-30. http://dx.doi.org/10.3886/ICPSR37957.v1
- PATH 2022: Lee, S., Bonar, E., Stoddard, S., & Elliott, M. (2026). Project Positive Attitudes Toward Health. Ann Arbor, MI: Inter-university Consortium for Political and Social Research [distributor], 2026-01-07. https://doi.org/10.3886/E241211V1
- HAWK: Lee, S. (2025). Health and Well-being of Koreans. Ann Arbor, MI: Inter-university Consortium for Political and Social Research [distributor], 2025-11-17. https://doi.org/10.3886/E232822V2

The original code can be found in
1. ...\RDS effectiveness

PCA (PATH 2017)-FINAL.Rmd
    Overview: Generates 
        - output for Table A.5.3
        - Figure A.5.1 (path2017_cv_FINAL.png)

PCA (PATH 2022)-FINAL.Rmd
    Overview: Generates 
        - output for Table A.5.4
        - Figure A.5.2 (path2022_cv_FINAL.png)

PCA (HAWK)-FINAL.Rmd
    Overview: Generates 
        - output for Table A.5.5
        - Figure A.5.3 (HAWK_cv_FINAL.png)

make_charts_FINAL.Rmd
    Overview: Generates 
        - Figure A.5.7 (path2017_lpca_FINAL.png), A.5.8 (path2022_lpca_FINAL.png), A.5.9 (hawk_lpca_FINAL.png)

2. ...\Korean Health\Analysis\SL\NCSES
ACS and HAWK Benchmarking.Rmd 
	- Figure A.5.4 (Figure_Seeds_NCSES.jpg)
HAWK Contact.Rmd
	- Figure A.5.5 (Figure_AgeContact_NCSES.jpg)
	- Figure A.5.6 (Figure_Coupon_NCSES.jpg)
