# stock-analysis
Toni Hewin

## Overview
	The purpose of the analysis was to create a refactored code for stock data for 2017, and 2018 which allows multiple years of data to be output with the click of a button. In this report, the original codes for 2017-18 run time will be provided to compare it to the refactored code. 
  
  ## Results
  ### Original Code
    In the original stock analysis, nested loops were used to locate the data for each year respectively. Running the code without refactoring returned a run time for 2017 at 0.5703125, and a run time for 2018 at 0.5546875. Using this method poses a concern when multiple years of data are needed due to the time frame. I have attached a copy of the code and run times below for the original code.
    
    ![image](https://user-images.githubusercontent.com/101079743/161198862-f0c9c81b-cb58-4272-86bf-80f41429a730.png)

![2017 Original Script](https://user-images.githubusercontent.com/101079743/161199083-adf46904-3d79-4893-ab7f-5cd5e91c300a.png)

![2018 Original Script](https://user-images.githubusercontent.com/101079743/161199105-1bf5a2a2-bfa4-4597-9f55-0c54af509ed6.PNG)

### Refactored Code
  	In the refactored code instead of using multiple nesting loops, Arrays, and conditionals were created which looped through the data one time making the code more efficient time wise. The returned run time for the refactored code for 2017 ran at 0.078125, and 2018 had run time of 0.09375. The refactored findings are below:
    
    ![image](https://user-images.githubusercontent.com/101079743/161199239-0c4ead19-6478-4681-8232-e1af2ee81afd.png)

![VBA Challenge-2017](https://user-images.githubusercontent.com/101079743/161199325-51fbf1e8-ec39-44a0-b916-0da40e784051.png)

![VBA Challeng-2018](https://user-images.githubusercontent.com/101079743/161199357-5223217e-0fd6-43d7-8c66-360876213697.png)

## Conclusion
    	In conclusion, the advantage of running a refactored code saved about 70% in time. This would be idea for Corporations that have large sums of data under review. The disadvantages found with refactoring code is the proper placement of code, and letters in code. Using this form of coding although time wise would be more business idea, it can also be challenging for a beginner Data Analyst. The pros in this particular analysis of VBA script is the time saved in refactoring. It also allows you the advantage of having information with the click of a button. The cons found were in the detail of inputting the code for it to run successfully.
