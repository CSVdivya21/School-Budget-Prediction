# Predicting School Budgets

Budgets for schools and school districts are huge, complex, and unwieldy. It's no easy task to digest where and how schools are using their resources. Education Resource Strategies is a non-profit that tackles just this task with the goal of letting districts be smarter, more strategic, and more effective in their spending. The dataset used here has 25 variables out of which 16 variables are feature variables and 9 variables are label classes.

## Feature Variables

The values in these 16 feature columns describe the properties of budget data as shown :-
  * FTE (float) - If an employee, the percentage of full-time that the employee works. 
  * Facility_or_Department – name of the department/facility the expenditure is tied to.
  * Function_Description - A description of the function the expenditure was serving.
  * Fund_Description - A description of the source of the funds.
  * Job_Title_Description - If this is an employee, a description of that employee's job title.
  * Location_Description - A description of where the funds were spent.
  * Object_Description - A description of what the funds were used for.
  * Position_Extra - Any extra information about the position that we have.
  * Program_Description - A description of the program that the funds were used for.
  * SubFund_Description - More detail on Fund_Description
  * Sub_Object_Description - More detail on Object_Description 
  * Text_1 - Any additional text supplied by the district.
  * Text_2 - Any additional text supplied by the district.
  * Text_3 - Any additional text supplied by the district.
  * Text_4 - Any additional text supplied by the district.
  * Total (float) - The total cost of the expenditure. 

## Label Variables

The labe; columns correspond to the budget item labels i will be trying to predict with the model. 
  * Function
  * Object_type
  * Operating_Status
  * Position_Type
  * Pre_K
  * Reporting
  * Sharing
  * Student_Type
  * Use
This is a a multi-class-multi-label classification problem because there are 9 broad categories that each take on many possible sub-label instances.