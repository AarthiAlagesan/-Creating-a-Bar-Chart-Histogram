Here's a simplified README for **Task 01**:

---

# Population Distribution Visualization

This project visualizes the distribution of population data using a histogram.

## Overview

We create a histogram to show the population distribution across various countries or regions, using data from the World Bank. This visualization helps identify how populations are spread across different regions.

## Dataset

- **Source**: 
-
[indian population new.csv](https://github.com/user-attachments/files/17634737/indian.population.new.csv)Year,Population,% Increase in Population,Population Density,% Increase in Population Density,Urban Population,Urban Population % of Total Population,% Increase in Urban Population,Rural Population,Rural Population % of Total Population,% Increase in Rural Population,Life Expectancy,% Increase in Life Expectancy,Birth Rate,% Change in Birth Rate,Death Rate,% Change in Death Rate,Infant Mortality Rate,% Change in Infant Mortality Rate,Fertility Rate,% Change in Fertility Rate,Net Migration Rate,% Change in Net Migration Rate
1950,"35,70,21,100",0.00%,108.61,0.00%,Null,Null,Null,Null,Null,Null,35.21,0.00%,44.175,0.00%,28.161,0.00%,189.629,0.00%,5.907,0.00%,-0.043,0.00%
1951,"36,49,22,360",2.21%,111.01,2.21%,Null,Null,Null,Null,Null,Null,35.8,1.68%,43.97,-0.46%,27.584,-2.05%,186.737,-1.53%,5.906,-0.02%,-0.047,9.30%
1952,"37,29,97,188",2.21%,113.47,2.21%,Null,Null,Null,Null,Null,Null,36.39,1.65%,43.764,-0.47%,27.008,-2.09%,183.846,-1.55%,5.904,-0.03%,-0.05,6.38%
1953,"38,12,27,705",2.21%,115.97,2.21%,Null,Null,Null,Null,Null,Null,36.98,1.62%,43.558,-0.47%,26.432,-2.13%,180.954,-1.57%,5.903,-0.02%,-0.054,8.00%
1954,"38,97,31,406",2.23%,118.56,2.23%,Null,Null,Null,Null,Null,Null,37.57,1.60%,43.352,-0.47%,25.856,-2.18%,178.062,-1.60%,5.902,-0.02%,-0.058,7.41%
1955,"39,85,77,992",2.27%,121.25,2.27%,Null,Null,Null,Null,Null,Null,38.16,1.57%,43.146,-0.48%,25.28,-2.23%,175.171,-1.62%,5.9,-0.03%,-0.061,5.17%
1956,"40,76,56,597",2.28%,124.01,2.28%,Null,Null,Null,Null,Null,Null,38.75,1.55%,42.941,-0.48%,24.703,-2.28%,172.279,-1.65%,5.899,-0.02%,-0.065,6.56%
1957,"41,69,35,399",2.28%,126.83,2.28%,Null,Null,Null,Null,Null,Null,39.34,1.52%,42.735,-0.48%,24.127,-2.33%,169.388,-1.68%,5.897,-0.03%,-0.068,4.62%
1958,"42,62,95,763",2.25%,129.68,2.25%,Null,Null,Null,Null,Null,Null,39.93,1.50%,42.529,-0.48%,23.551,-2.39%,166.496,-1.71%,5.896,-0.02%,-0.072,5.88%
1959,"43,59,00,352",2.25%,132.6,2.25%,Null,Null,Null,Null,Null,Null,40.53,1.51%,42.298,-0.54%,23.016,-2.27%,164.119,-1.43%,5.895,-0.02%,-0.065,-9.72%
1960,"44,59,54,579",2.31%,135.66,2.31%,"8,07,56,165",17.92,0.00%,"36,97,91,510",82.08,0.00%,41.13,1.49%,42.066,-0.55%,22.481,-2.32%,161.742,-1.45%,5.894,-0.02%,-0.058,-10.77%
1961,"45,63,51,876",2.33%,138.82,2.33%,"8,28,82,675",18.03,2.60%,"37,67,59,491",81.97,1.87%,41.74,1.46%,41.835,-0.55%,21.946,-2.38%,159.366,-1.47%,5.892,-0.03%,-0.05,-13.79%
1962,"46,70,24,193",2.34%,142.07,2.34%,"8,54,56,483",18.22,3.06%,"38,36,20,708",81.78,1.80%,42.34,1.44%,41.603,-0.55%,21.411,-2.44%,156.989,-1.49%,5.891,-0.02%,-0.043,-14.00%
1963,"47,79,33,619",2.34%,145.39,2.34%,"8,81,27,852",18.41,3.08%,"39,06,97,750",81.6,1.83%,42.94,1.42%,41.372,-0.56%,20.876,-2.50%,154.612,-1.51%,5.89,-0.02%,-0.036,-16.28%
1964,"48,90,59,309",2.33%,148.77,2.33%,"9,09,01,311",18.6,3.10%,"39,79,46,828",81.41,1.84%,43.57,1.47%,41.051,-0.78%,20.374,-2.40%,152.851,-1.14%,5.857,-0.56%,-0.055,52.78%
1965,"50,01,14,346",2.26%,152.14,2.26%,"9,37,60,317",18.79,3.10%,"40,53,63,011",81.22,1.85%,44.2,1.45%,40.731,-0.78%,19.873,-2.46%,151.091,-1.15%,5.823,-0.58%,-0.074,34.55%
1966,"51,09,92,617",2.18%,155.45,2.18%,"9,67,12,771",18.98,3.10%,"41,29,18,738",81.02,1.85%,44.84,1.43%,40.41,-0.79%,19.371,-2.53%,149.33,-1.17%,5.79,-0.57%,-0.092,24.32%
1967,"52,19,87,069",2.15%,158.79,2.15%,"9,97,65,995",19.17,3.11%,"42,06,34,582",80.83,1.85%,45.47,1.41%,40.09,-0.79%,18.87,-2.59%,147.57,-1.18%,5.756,-0.59%,-0.111,20.65%
1968,"53,34,31,909",2.19%,162.27,2.19%,"10,29,32,969",19.37,3.13%,"42,85,80,865",80.63,1.87%,46.1,1.39%,39.769,-0.80%,18.368,-2.66%,145.809,-1.19%,5.723,-0.57%,-0.13,17.12%
1969,"54,53,14,670",2.23%,165.89,2.23%,"10,62,38,157",19.56,3.16%,"43,68,46,176",80.44,1.91%,46.75,1.42%,39.5,-0.68%,17.911,-2.49%,143.815,-1.37%,5.66,-1.10%,0.039,-130.00%
1970,"55,75,01,301",2.23%,169.59,2.23%,"10,97,05,504",19.76,3.21%,"44,54,84,293",80.24,1.96%,47.41,1.40%,39.231,-0.68%,17.454,-2.55%,141.822,-1.39%,5.598,-1.10%,0.208,433.33%
1971,"56,99,99,178",2.24%,173.4,2.24%,"11,35,22,496",19.99,3.42%,"45,43,45,525",80.01,1.97%,48.06,1.38%,38.961,-0.69%,16.997,-2.62%,139.828,-1.41%,5.535,-1.13%,0.377,81.25%
1972,"58,28,37,973",2.25%,177.3,2.25%,"11,80,82,741",20.32,3.94%,"46,30,04,514",79.68,1.89%,48.72,1.36%,38.692,-0.69%,16.54,-2.69%,137.835,-1.43%,5.473,-1.12%,0.546,44.83%
1973,"59,61,07,483",2.28%,181.34,2.28%,"12,28,37,876",20.65,3.95%,"47,19,32,260",79.35,1.91%,49.37,1.34%,38.423,-0.70%,16.083,-2.76%,135.841,-1.45%,5.41,-1.15%,0.715,30.95%
1974,"60,97,21,951",2.28%,185.48,2.28%,"12,77,93,753",20.99,3.96%,"48,10,08,842",79.01,1.91%,50,1.27%,38.071,-0.92%,15.676,-2.53%,132.832,-2.22%,5.323,-1.61%,0.639,-10.63%
1975,"62,35,24,219",2.26%,189.68,2.26%,"13,29,20,311",21.33,3.93%,"49,01,82,589",78.67,1.89%,50.63,1.26%,37.718,-0.93%,15.269,-2.60%,129.824,-2.26%,5.236,-1.63%,0.563,-11.89%
1976,"63,74,51,448",2.23%,193.92,2.23%,"13,82,19,074",21.68,3.91%,"49,94,11,011",78.32,1.87%,51.25,1.24%,37.366,-0.93%,14.862,-2.67%,126.815,-2.32%,5.148,-1.68%,0.488,-13.32%
1977,"65,16,85,628",2.23%,198.25,2.23%,"14,36,99,555",22.03,3.89%,"50,87,09,211",77.97,1.84%,51.88,1.23%,37.013,-0.94%,14.455,-2.74%,123.807,-2.37%,5.061,-1.69%,0.412,-15.57%
1978,"66,62,67,760",2.24%,202.68,2.24%,"14,93,79,784",22.38,3.88%,"51,81,20,031",77.62,1.83%,52.51,1.21%,36.661,-0.95%,14.048,-2.82%,120.798,-2.43%,4.974,-1.72%,0.336,-18.45%
1979,"68,12,48,383",2.25%,207.24,2.25%,"15,52,85,822",22.74,3.88%,"52,77,09,526",77.26,1.83%,52.99,0.91%,36.438,-0.61%,13.773,-1.96%,117.771,-2.51%,4.916,-1.17%,0.3,-10.71%
1980,"69,68,28,385",2.29%,211.98,2.29%,"16,14,44,126",23.1,3.89%,"53,75,08,711",76.9,1.84%,53.47,0.91%,36.216,-0.61%,13.498,-2.00%,114.743,-2.57%,4.857,-1.20%,0.264,-12.00%
1981,"71,28,69,298",2.30%,216.86,2.30%,"16,75,21,705",23.42,3.70%,"54,78,63,292",76.58,1.91%,53.95,0.90%,35.993,-0.62%,13.223,-2.04%,111.716,-2.64%,4.799,-1.19%,0.228,-13.64%
1982,"72,91,69,466",2.29%,221.82,2.29%,"17,31,52,674",23.65,3.31%,"55,90,86,824",76.35,2.03%,54.43,0.89%,35.771,-0.62%,12.948,-2.08%,108.688,-2.71%,4.74,-1.23%,0.192,-15.79%
1983,"74,58,26,546",2.28%,226.88,2.28%,"17,89,56,141",23.88,3.30%,"57,04,72,817",76.12,2.02%,54.91,0.88%,35.548,-0.62%,12.673,-2.12%,105.661,-2.79%,4.682,-1.22%,0.156,-18.75%
1984,"76,28,95,156",2.29%,232.08,2.29%,"18,49,06,540",24.11,3.27%,"58,19,26,871",75.89,1.99%,55.27,0.65%,35.04,-1.43%,12.451,-1.75%,103.178,-2.35%,4.599,-1.77%,0.127,-18.59%
1985,"78,02,42,084",2.27%,237.35,2.27%,"19,09,75,976",24.35,3.23%,"59,33,84,036",75.65,1.95%,55.62,0.64%,34.532,-1.45%,12.229,-1.78%,100.695,-2.41%,4.516,-1.80%,0.098,-22.83%
1986,"79,78,78,993",2.26%,242.72,2.26%,"19,71,65,615",24.59,3.19%,"60,48,09,635",75.42,1.91%,55.98,0.64%,34.025,-1.47%,12.008,-1.81%,98.213,-2.46%,4.432,-1.86%,0.069,-29.59%
1987,"81,57,16,125",2.24%,248.14,2.24%,"20,34,69,686",24.82,3.15%,"61,62,12,409",75.18,1.87%,56.33,0.64%,33.517,-1.49%,11.786,-1.85%,95.73,-2.53%,4.349,-1.87%,0.04,-42.03%
1988,"83,37,29,681",2.21%,253.62,2.21%,"20,98,94,840",25.06,3.11%,"62,75,74,098",74.94,1.83%,56.69,0.63%,33.009,-1.52%,11.564,-1.88%,93.247,-2.59%,4.266,-1.91%,0.011,-72.50%
1989,"85,20,12,673",2.19%,259.19,2.19%,"21,64,42,440",25.31,3.07%,"63,88,92,235",74.7,1.79%,57.18,0.86%,32.413,-1.81%,11.286,-2.40%,91.019,-2.39%,4.179,-2.04%,-0.015,-236.36%
1990,"87,04,52,165",2.16%,264.8,2.16%,"22,30,96,279",25.55,3.03%,"65,01,81,520",74.45,1.75%,57.66,0.85%,31.817,-1.84%,11.007,-2.47%,88.791,-2.45%,4.093,-2.06%,-0.041,173.33%
1991,"88,89,41,756",2.12%,270.42,2.12%,"22,97,52,406",25.78,2.94%,"66,15,20,796",74.22,1.73%,58.15,0.84%,31.22,-1.88%,10.729,-2.53%,86.564,-2.51%,4.006,-2.13%,-0.068,65.85%
1992,"90,75,74,049",2.10%,276.09,2.10%,"23,62,74,336",25.98,2.80%,"67,30,32,682",74.02,1.73%,58.63,0.84%,30.624,-1.91%,10.45,-2.60%,84.336,-2.57%,3.92,-2.15%,-0.094,38.24%
1993,"92,63,51,297",2.07%,281.8,2.07%,"24,28,96,347",26.19,2.76%,"68,45,07,519",73.81,1.69%,59.12,0.83%,30.028,-1.95%,10.172,-2.66%,82.108,-2.64%,3.833,-2.22%,-0.12,27.66%
1994,"94,52,61,958",2.04%,287.55,2.04%,"24,96,29,427",26.4,2.73%,"69,59,72,401",73.6,1.66%,59.59,0.79%,29.536,-1.64%,9.956,-2.12%,79.936,-2.65%,3.763,-1.83%,-0.123,2.50%
1995,"96,42,79,129",2.01%,293.34,2.01%,"25,64,70,882",26.61,2.70%,"70,74,51,704",73.39,1.64%,60.06,0.79%,29.044,-1.67%,9.739,-2.18%,77.764,-2.72%,3.693,-1.86%,-0.126,2.44%
1996,"98,32,81,218",1.97%,299.12,1.97%,"26,34,40,889",26.82,2.68%,"71,89,24,359",73.18,1.61%,60.53,0.78%,28.551,-1.70%,9.523,-2.22%,75.591,-2.79%,3.623,-1.90%,-0.129,2.38%
1997,"1,00,23,35,230",1.94%,304.92,1.94%,"27,05,23,260",27.03,2.65%,"73,03,76,768",72.97,1.58%,61,0.78%,28.059,-1.72%,9.306,-2.28%,73.419,-2.87%,3.553,-1.93%,-0.132,2.33%
1998,"1,02,14,34,576",1.91%,310.73,1.91%,"27,77,07,329",27.24,2.62%,"74,17,76,257",72.76,1.55%,61.47,0.77%,27.567,-1.75%,9.09,-2.32%,71.247,-2.96%,3.483,-1.97%,-0.135,2.27%
1999,"1,04,05,00,054",1.87%,316.53,1.87%,"28,49,78,105",27.45,2.58%,"75,30,80,049",72.55,1.51%,61.88,0.66%,27.101,-1.69%,8.947,-1.57%,68.988,-3.17%,3.414,-1.98%,-0.177,31.11%
2000,"1,05,96,33,675",1.84%,322.35,1.84%,"29,23,22,757",27.67,2.54%,"76,42,52,791",72.33,1.47%,62.28,0.66%,26.635,-1.72%,8.804,-1.60%,66.729,-3.27%,3.346,-1.99%,-0.218,23.16%
2001,"1,07,89,70,907",1.82%,328.23,1.82%,"30,01,18,526",27.92,2.63%,"77,48,81,568",72.08,1.38%,62.69,0.65%,26.17,-1.75%,8.661,-1.62%,64.471,-3.38%,3.277,-2.06%,-0.26,19.27%
2002,"1,09,83,13,039",1.79%,334.11,1.79%,"30,87,96,506",28.24,2.85%,"78,45,20,681",71.76,1.24%,63.09,0.65%,25.704,-1.78%,8.518,-1.65%,62.212,-3.50%,3.209,-2.08%,-0.301,15.77%
2003,"1,11,74,15,123",1.74%,339.92,1.74%,"31,75,84,393",28.57,2.81%,"79,39,38,753",71.43,1.19%,63.5,0.64%,25.238,-1.81%,8.375,-1.68%,59.953,-3.63%,3.14,-2.15%,-0.343,13.95%
2004,"1,13,62,64,583",1.69%,345.66,1.69%,"32,64,95,070",28.9,2.77%,"80,31,28,396",71.1,1.15%,63.91,0.64%,24.752,-1.93%,8.261,-1.36%,57.854,-3.50%,3.071,-2.20%,-0.364,6.12%
2005,"1,15,46,38,713",1.62%,351.25,1.62%,"33,55,03,761",29.24,2.72%,"81,21,06,163",70.77,1.11%,64.31,0.64%,24.266,-1.96%,8.147,-1.38%,55.755,-3.63%,3.002,-2.25%,-0.384,5.49%
2006,"1,17,23,73,788",1.54%,356.64,1.54%,"34,46,22,641",29.57,2.68%,"82,08,63,650",70.43,1.07%,64.72,0.63%,23.779,-2.01%,8.034,-1.39%,53.655,-3.77%,2.934,-2.27%,-0.405,5.47%
2007,"1,18,96,91,809",1.48%,361.91,1.48%,"35,38,50,624",29.91,2.64%,"82,93,58,847",70.09,1.03%,65.12,0.63%,23.293,-2.04%,7.92,-1.42%,51.556,-3.91%,2.865,-2.35%,-0.425,4.94%
2008,"1,20,67,34,806",1.43%,367.09,1.43%,"36,31,54,576",30.25,2.60%,"83,75,15,186",69.75,0.98%,65.53,0.62%,22.807,-2.09%,7.806,-1.44%,49.457,-4.07%,2.796,-2.41%,-0.446,4.94%
2009,"1,22,36,40,160",1.40%,372.24,1.40%,"37,24,65,918",30.59,2.53%,"84,52,60,299",69.41,0.92%,65.98,0.68%,22.158,-2.85%,7.697,-1.40%,47.382,-4.20%,2.716,-2.86%,-0.431,-3.36%
2010,"1,24,06,13,620",1.39%,377.4,1.39%,"38,17,63,164",30.93,2.47%,"85,25,17,999",69.07,0.86%,66.43,0.68%,21.508,-2.93%,7.589,-1.40%,45.307,-4.38%,2.636,-2.95%,-0.415,-3.71%
2011,"1,25,76,21,191",1.37%,382.57,1.37%,"39,10,40,056",31.28,2.40%,"85,92,47,883",68.72,0.79%,66.87,0.67%,20.859,-3.02%,7.48,-1.44%,43.232,-4.58%,2.556,-3.03%,-0.4,-3.61%
2012,"1,27,44,87,215",1.34%,387.71,1.34%,"40,04,16,922",31.63,2.37%,"86,53,63,321",68.37,0.71%,67.32,0.67%,20.209,-3.12%,7.372,-1.44%,41.157,-4.80%,2.476,-3.13%,-0.384,-4.00%
2013,"1,29,11,32,063",1.31%,392.77,1.31%,"40,99,07,903",32,2.34%,"87,09,34,216",68,0.64%,67.77,0.67%,19.56,-3.21%,7.263,-1.48%,39.082,-5.04%,2.396,-3.23%,-0.369,-3.91%
2014,"1,30,72,46,509",1.25%,397.67,1.25%,"41,95,67,353",32.38,2.33%,"87,60,33,415",67.62,0.58%,68.07,0.44%,19.252,-1.57%,7.258,-0.07%,37.666,-3.62%,2.365,-1.29%,-0.374,1.36%
2015,"1,32,28,66,505",1.19%,402.42,1.19%,"42,94,28,650",32.78,2.32%,"88,07,23,742",67.22,0.53%,68.37,0.44%,18.944,-1.60%,7.253,-0.07%,36.249,-3.76%,2.334,-1.31%,-0.38,1.60%
2016,"1,33,86,36,340",1.19%,407.22,1.19%,"43,95,01,314",33.18,2.32%,"88,50,15,936",66.82,0.49%,68.67,0.44%,18.636,-1.63%,7.247,-0.08%,34.833,-3.91%,2.302,-1.37%,-0.385,1.32%
2017,"1,35,41,95,680",1.16%,411.95,1.16%,"44,97,95,398",33.6,2.32%,"88,88,81,381",66.4,0.44%,68.97,0.44%,18.328,-1.65%,7.242,-0.07%,33.416,-4.07%,2.271,-1.35%,-0.391,1.56%
2018,"1,36,90,03,306",1.09%,416.46,1.09%,"46,03,04,169",34.03,2.31%,"89,23,38,114",65.97,0.39%,69.27,0.43%,18.02,-1.68%,7.237,-0.07%,32,-4.24%,2.24,-1.37%,-0.396,1.28%
2019,"1,38,31,12,050",1.03%,420.75,1.03%,"47,10,31,529",34.47,2.30%,"89,53,86,227",65.53,0.34%,69.5,0.33%,17.806,-1.19%,7.273,0.50%,30.924,-3.36%,2.22,-0.89%,-0.383,-3.28%
2020,"1,39,63,87,127",0.96%,424.79,0.96%,"48,19,80,332",34.93,2.30%,"89,80,24,053",65.07,0.29%,69.73,0.33%,17.592,-1.20%,7.309,0.49%,29.848,-3.48%,2.2,-0.90%,-0.369,-3.66%
2021,"1,40,75,63,842",0.80%,428.19,0.80%,"49,31,69,259",35.39,2.29%,"90,02,39,774",64.61,0.25%,69.96,0.33%,17.377,-1.22%,7.344,0.48%,28.771,-3.61%,2.179,-0.95%,-0.356,-3.52%
2022,"1,41,71,73,173",0.68%,431.11,0.68%,Null,Null,Null,Null,Null,Null,70.19,0.33%,17.163,-1.23%,7.38,0.49%,27.695,-3.74%,2.159,-0.92%,-0.342,-3.93%



