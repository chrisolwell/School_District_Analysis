# School_District_Analysis
## Overview of Analysis
After running our analysis, we were contact by district officials concerned fraudulent results among the scores of ninth graders at Thomas High School might result in erroneous conclusions. In the interest of accuracy, we nullified the data in question and conducted the analysis again.
## Results of Analysis
The data quality issues caused minimal distortion of the overall results of the analysis. Only the Thomas High Academic results seemed to be significantly different in any way from the results of the analysis before we eliminated our corrupt data. Here's a look at the district summary when the corrupt data was included in our analysis:

<img width="613" alt="district_summary_bad" src="https://user-images.githubusercontent.com/4724180/150822940-76bef4a9-8adc-405e-928d-c2321f52c95a.png">

Here's the district summary after we cleaned up the bad data:

<img width="613" alt="district_summary_good" src="https://user-images.githubusercontent.com/4724180/150823216-f24161fc-b607-422f-a9b9-cb5bbdc2978a.png">

As you can see, the academic scores either decreased by one-tenth of a percentage point or not at all, and that makes sense as about one percent of the data was potentially corrupted. Let's get into the weeds:
  - The number of schools and students were not impacted, nor was the district budget
  - The districtwide average math score decreased from 79 percent to 78.9 percent
  - The districtwide average reading score remained 81.9 percent
  - The districtwide percentage of students with a passing math score decreased from 75 percent to 74.9 percent
  - The districtwide percentage of students with a passing reading score decreased from 86 percent to 85.7 percent
  - The districtwide percentage of students with an overall passing score decreased from 65 percent to 64.9 percent

Here are is the school summary with the corrupt data:

<img width="971" alt="schools_bad_final" src="https://user-images.githubusercontent.com/4724180/150823896-4e75795d-24d7-4300-a812-5cdaaa076c08.png">

And here's the same summary with the bad data removed:

<img width="971" alt="schools_good_final" src="https://user-images.githubusercontent.com/4724180/150824010-9fa29680-8ad0-4b74-b62c-e5fc8b694f6c.png">

Note that only the Thomas High result are affected, which again makes sense, as that's where the cheating was alleged to have occurred.
