# (Basic) Wealth Ineqiality Analytics
### A basic scope of an entry level data analysis and general practice regarding my technical computer/ program skills.

#### The data being used is fictional and out of my own creation about wealth inequality in a fictional city.

### Synopsis : 
The purpose of this basic/fictional wealth inequality data project is to utilize KPI's to determine which areas of the 
fictional city of "Avalon City" need to be addressed when reporting to governmental or buisness objectives. 

### Data Soruces:
The primary data source is the Avalon City Wealth Inequlaity Spreadsheet 2025 ( a Mac Numbers file) that has been 
converted to .xlsx for wider computer accessibility. 

### Tools
- Mac Numbers - Spreadsheet Development
- Microsoft Excel - Data Conversion & Data cleaning
- Microsoft Excel - Reporting
- Tableau - Data Visualization & Dashboard
- Mac Keynote - Presentation
- Microsoft Excel - Final Presentaion & Analysis

### Spreadsheet Data Development:

<img width="1099" height="414" alt="Avalon City Wealth Ineqality Mac Numbers Spreadsheet" src="https://github.com/user-attachments/assets/5b6a359c-d28e-4004-b94d-6d90cf2ead1d" />

I created fictional districts within "Avalon City" to demonstrate the economic and wealth diverity of the city. Some 
KPI's that are featured in the basic spreadsheet are generally used for reporting and determining real life statistical
information such as Gini Coefficent, Human Development Index & GDP. These districts can also be used to map geographic
visualuzations to better determine wealth gaps in areas of the city.

### Data Conversion & Data Cleaning:


After creating, filling-in and formatting the data, I then proceeded to convert the numbers file into xlsx. The results
are shown below:

<img width="1064" height="568" alt="ACWIS_v1_Xlsx" src="https://github.com/user-attachments/assets/c27c4179-a5e5-4a22-b838-05a3ac7d6abf" />


As you can see, there is a bit that was lost in translation and some editing/ cleaning needs to be done. futhermore, I've 
added some higher end detailing and formatting to futher enhance the spreadsheet. The following image feautres these
translation corrections, appropriate cell formatting as well as spreadsheet enchancements;


<img width="1137" height="568" alt="ACWIS_v2_Xlsx" src="https://github.com/user-attachments/assets/2599ece6-6f25-4129-8a7b-14b15384228c" />


#### Reporting:


Next,the cleaned spreadsheet can provide some reporting insights by filtering and applying basic formulas by using
the Microsoft Excel functions such as:

- featuring average counters for related metrics to measure analysis such as " Average GDP in ₳" , "Average Gini Coef."
  and Average HDI which is broken down by the following excel formulations:

  <img width="1106" height="559" alt="averages for Avalon City Wealth Inequlaity Spreadsheet" src="https://github.com/user-attachments/assets/cb694189-38b7-4267-9fb6-37ca9da6f49d" />


  
  `=AVERAGE(C3:C15)` to produce the Average in GDP result of ₳697,341 for the given data
  `=AVERAGE(H3:H15)` to produce the Average Gini Coef. result of 33.1 for the given data
  `=AVERAGE(F3:F15)` to produce the Average Human Development Index result of 0.890 for Avalon city.

Then we can also filter the data to figure out which districts are on either end of inequality by using the Gini Coef. metric.


- Highest district of inequality according to Gini Coef. :
  <img width="1137" height="429" alt="Highest Inequality" src="https://github.com/user-attachments/assets/4c90694e-734a-4dde-9391-25910ca3cf05" />
 

- Lowest district of inequality according to Gini Coef. :
  <img width="1137" height="429" alt="Lowest Inequality" src="https://github.com/user-attachments/assets/ccd259e1-72e4-4318-9deb-4e47cd64169d" />


Both of thoese results can also be calculated outby the following excel XLOOKUP formaulations:



  `=XLOOKUP(MAX(H3:H15),A3:H15,1,FALSE)` for which North Avalon is the district with the highest level of inequality.
  `=XLOOKUP(MIN(H3:H15),A3:H15,1,FALSE)` for which Ridge is the district with the lowest level of inequality.


Which results in the following XLOOKUP feauture in the spreasheet:

  <img width="1106" height="559" alt="XLOOKUP feautes" src="https://github.com/user-attachments/assets/6a8c657e-e4f0-4c2d-8b37-86f5a76cd3b1" />






### Spreadsheet Data Vizualization & Dashboard

After developing and applying light analysis/ reporting (Such as data filtering, excel formulations & conditional formatting)
I then proceed towards the next step of the data analysis which is visualization. This helps visualize the data and lets 
the data convey what the information is without bias. Therefore, the data from Avalon City Weath Inequality 2025 table
will be used to drive better business decisions to determine needs regarding wealth inequlaity in the city.




  
- 1st, we import the final Microsfot Excel Spredsheet into Tableau Public.

  <img width="1399" height="758" alt="Importing into Tableau Public" src="https://github.com/user-attachments/assets/ff2451e9-49e8-47b4-bfe8-f5b2409fe423" />

  We check to makure sure the data imported sucessfuly by reviewing the spreasheet in the preview pane making sure there
  are no anomalies that will disrupt the visualization later on when reproting the data. After clicking "Cleaned with
  Data Interpreter", the spreadsheet is automatically and correctly interpreted with the headings and columns appropreatly
  assigned.

  <img width="1545" height="762" alt="Automatic Import into Tableau" src="https://github.com/user-attachments/assets/379815bc-27e7-4961-9639-f086e74c57a1" />

- 2nd, we then proceed with Tableau Public's visualization tools by using KPI's to determine the data's story and relative
  information we need to conduct a basic analysis in the form of a dashboard.

  *In this instance, I created a tree map visualization that depicts the Gini coef. (how unequal the distribution of wealth is
  in a given economy) of each district within Avalon City. We want to highlight the areas that have the highest inequlaity
  first so we can easy determine which districts need the most attention. I have labled each Gini Coef to their corresponding
  Dtistrict and display them using colors that emphazise the disparity of wealth.*

  <img width="1331" height="679" alt="Gini Coef  Treemap" src="https://github.com/user-attachments/assets/82f6a442-51f1-4eb0-8484-0a3046de2a82" />


  *Next, I then created a bar chart to measure each district's level of human development index against each other. I ordered
  each "bar" (district) in ascending order with coloration to dstinctly highlight the differences of HDI between each district
  within the city.*

  <img width="1331" height="679" alt="HDI chart" src="https://github.com/user-attachments/assets/1cc9ff91-7c3c-4f5b-870e-b51528a15dd3" />

  *Then, I created a doughnut chart to visualize the direct proportion of people that live/ use governmental housing in each
  district. I also featured percentages under each district's label to futher enchance the proportion of the doughnut chart.*

  <img width="1331" height="679" alt="Gov Housing doughnut chart" src="https://github.com/user-attachments/assets/31f4cb3e-efcc-4281-ae32-6cb2f93897ac" />
  

  - 3rd. the dashboard development
  
    *Lastly, I developed an interactive dashboard to really bring the data into life while aslo allowing the data to be used to
  explore. This further drives more conclusions about the analyis from a easy to understand layout for stakeholders to interact,
  visualize and draw research findings.*

  <img width="1014" height="853" alt="Completed AC Wealth Dashboard" src="https://github.com/user-attachments/assets/dcb62d5c-9cc0-4afe-9a5c-73673f7cefaf" />



  *To futher enchance the dshboard, I've implemented a search filter within the dashbaord to focus on specific districts. This
  is a helpful feature that is built to provide specific data that a stakeholder has regarding specific districts within the
  city to help deal with ineqality.*

  <img width="1014" height="270" alt="Seach Filter in AC Inequality Dashboard" src="https://github.com/user-attachments/assets/d6ecb1f0-a524-49c1-bc77-77399b8d716b" />



### Presentation


This penultimate step will take everything we have done to finally present the data in a sample and effecive presentation.
Since I have orignally created the Avalon City Wealth Inequality data spreadsheet with Mac Numbers, I need to develop a
keynote presentation about the data findings. Becasue we need convey what the data is telling us in a simple and palletable
way for everyone (e.g. government entieties, stakeholders etc.) to interpret. 



<img width="1900" height="900" alt="ACWI_WIP" src="https://github.com/user-attachments/assets/3ffd91e7-de53-480b-92ff-c6b889422ed6" />


During the keynote development, I simply used the existing Tableau Public data visualizations I've aready used to tell the
data's story. I incorporated many aspects of the visulizations I've done along with taking it upon myself to deliver 
other valuable insights for complete analysis. After creating the Mac Keynote presenation I can already draw main conclusions 
and decifer what the data is reporting without bias. 


### Final Presentaion & Analysis

The last step is to convert the Mac Keynote file into a Microsoft PowerPoint presenation file. Like the Numbers to Excel
conversion, this final conversion is to make it easier for any stakeholder or vested person to access the Data Analysis
in an easy to understand medium. Which in turn, the stakeholder can draw their own conlcusions and develop a good strategy
to mitigate wealth inequality within Avalon city.



  
