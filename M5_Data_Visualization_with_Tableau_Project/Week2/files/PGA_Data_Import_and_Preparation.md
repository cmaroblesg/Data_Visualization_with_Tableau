# Peer-graded Assignment: Data Import and Preparation

## Instructions:
This milestone focuses on the nuts and bolts of preparing your data for analysis. You will make final decisions about which data to use to support your project, and you will acquire that data, import it into Tableau, and prep it for analysis.

The purpose of this step is to ensure the data you will be analyzing is free of problematic errors that would contaminate your analysis. As we have noted before, when it comes to the quality of your analytics and visualizations, it truly is “garbage in, garbage out.” Therefore, it is essential the data you choose for this project is of high quality and is free of any problematic cleanliness issues. The character of these issues will vary dramatically from project to project, and it will ultimately be up to you to determine if a perceived outlier in the data is evidence of a problem, or an interesting discovery, or neither.

The data sources we have curated for this project (and can be found in the resources section of this milestone) are known to be of high quality. This does not mean they are all completely free of cleanliness issues, but any issues that may arise in these data should be easy to address with skills learned in this program. However, if your data requires advanced cleaning and prepping techniques, we encourage you to watch this video from Tableau Public
Blog, which covers some very useful techniques: [Data prepping and data cleaning tableau examples](https://public.tableau.com/en-us/s/blog/2016/05/data-prepping-and-data-cleaning-tableau-explained.)

## Review criteria
You will submit a screenshot of the Data Source page in your Tableau Desktop instance that shows your data has been properly imported and is prepared for analysis. You will also submit an accompanying write-up on any data cleaning steps you took to prepare the data for analysis.

### Picture of Your Data Source
On your screenshot (picture), your peers will be looking for the following characteristics in your screenshot:
* No problematic outliers in the data
* No (or very few) missing data values
* Verify that the data types correspond to the actual values stored in the data, for example, if the data type is numeric, the values should be numeric
* No problematic patterns or trends

### Your Data Cleaning Process
Write a discussion entry that describes what data cleanliness issues you found in your chosen dataset(s), and what measures or steps were taken to correct those issues. Be sure to indicate why you took the steps you took.  For instance, did you remove outliers, change variables, normalize values? Why did you take these steps?  If you didn’t need to take any steps to clean the data, please indicate that in your write-up.

### Final Submission:
#### Executive summary
One of the most important task in the Data Analysis is to get a database to be used and analyzed. For this particular project, It is using the COVID-19 reported cases.\
This information can download free directly from the source: [Open Access Mexican Reported Cases](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico).\
Moreover, to understand and process the information it is also necessary to download the data dictionaries: [Open Access Mexican Data Dictionaries](http://datosabiertos.salud.gob.mx/gobmx/salud/datos_abiertos/diccionario_datos_covid19.zip).

The main goal of this project is to create a lockdown semaphore to stop non-essential activities in the country group by state.
The database contains all the reported cases in the region. The local government created a database in which the hospitals, clinics, laboratories and other health building report the cases daily.
Moreover, this dataset contains not only the positive cases, it contains also negative and false detections.
* Thus, the first part is related to the extraction of the positive-confirmed COVID-19 cases.
* Then, join the catalogues to the database to fully understand the content.
* The third part is to clean the database, this process includes the correction of typos, misspelling and grammar in the fields, convert date fields into date-stamps format, eliminate repetitions and blank spaces and convert some columns into numeric information.
* Finally, the information is stored into a *.csv file format and uploaded into Tableau.

[Data Import and Preparation Peer-Graded Activity](./PGA_Data_Import_and_Preparation.pdf)
