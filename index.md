# Developing Data Product Wee4 Project - BMI
Nsi J.  
22 juillet 2017  
## Project and goal   

**The project has two parts**             
- First, create a Shiny application and deploy it on Rstudio's servers and associated it with a supporting documentation.             
- Second,use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about the application.          

*How to for peer review on RPubs: Please mouse over until you see a hand to click to the next slide or press on descending arrow n times*

## Documentation 

**Description**

The application is a web site that enable you to compute your Body Mass Indice BMC.
The Body mass index (BMI) is a measure of body fat based on height and weight that applies to adult men and women.
The presentation is done with R Markdown presentation which is made interactive using Shiny.

**Format**   
variables      
- Height : a numerical type in centimeters   
- Weight : a numerical type in kilograms   
- Date : a date format formatted as yyyy-mm-dd   
- Firstname : a character type 

## HOW TO USE BMI APPLICATION
**Step by step example**     
*On the top of your screen : enter the values required*        
- First Enter your height by moving the slider labelled Your Height (in centimeters) e.g 160
- And Enter your weight by moving the slider labelled Your Weight (in kilograms) e.g 58
- Then  Type your firsname in the textbox named Your Firstname, e.g James
- And  Enter the date by selecting in the open calandar or type it in the field labbeled Date input: yyyy-mm-dd, e.g 2017-22-07
- Finally See the results immediately

*Under the values entered, you can then observe the results typed and computed*        
- In the table, you have the values you are selecting(height, weight, date) or typing(firstname, date)   
- Below the table,the data computed : 
Your BMC is calculated when you finished to select your height and weight. It is displayed in the field named data.   
Also, in the plot these 2 values of height and weight are displayed   
Furthermore, the most you move the values with the 2 sliders, the most the results change both on data field. 
The BMI is recalculated. 
In the plot included, you can observe the changes on values for weight and height and their linked point, the red circle that corresponding. 

## THE DISPLAY OF THE BMI APPLICATION     
*YOU CAN TEST THE APP AND ENJOY*  
<!--html_preserve--><div style="width: 100% ; height: 400px ; text-align: center; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box;" class="muted well">Shiny applications not supported in static R Markdown documents</div><!--/html_preserve-->
