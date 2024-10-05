# Introduction
goal of the project is to acquire an overview of the functioning of data science , basic concepts and techniques of data analysis, understand how they work and gain intuition for their appropriate application for the purpose of discovering data knowledge . Also get an idea of what questions we can answer and apply using data analysis _ _ _ basic approaches of machine learning . Emphasis is placed on the analysis and preprocessing of data, the use of machine learning methods , methods of their evaluation and comparison.
 
The project is developed in pairs . The solution uses the Python programming language and available data science libraries such as pandas, numpy, scipy, scikit-learn , etc. . An executable is handed over at each stage Jupyter Notebook to AIS, which contains all performed transformations on data with appropriate documentation. The submitted notebook must contain not only the code , but also its results (calculated values , statements , visualizations , etc. ) together with a comment on the scanned result and the following decisions for further steps of the data process . The ability to communicate well and present relevant results is an important component of the evaluation .
 
For each phase, in the submitted notebook, also indicate the percentage of the work of the members of the pair .

# Data
https://drive.google.com/drive/folders/1wZaVpr0VedXeS1TgjGOg6eHkhwvWA2BM?usp=sharing 
 
Air pollution causes serious respiratory and heart diseases , which can be fatal . _ _ _ _ _ _ _ _ _ Children are most often affected , which leads to pneumonia and breathing problems , including asthma . _ _ _ _ _ _ _ Acid rain , destruction of the ozone layer and global warming are some of the adverse consequences . The data set for you (World's Air Pollution: Real-time Air Quality Index https://waqi.info/ ) represents records of individual air quality measurements as a combination of many factors without time sequence . In the records , there is a dependent variable with the name " warning " indicating an alarming state of air quality. In big cities such as _ _ Beijing (English: Beijing, the capital of China with more than 21 million people ) when a warning is issued , a measure such as limiting the movement of cars and people in the city or artificial rain is triggered if the air quality does not return to normal.
    
*A dictionary of domain-specific abbreviations that occur in the data*
	PM2.5         Particulate Matter (µg/m 3 )
	PM10         Particulate Matter (µg/m 3 )
	NOx         Nitrogen Oxides (µg/m 3 )
	NO2         Nitrogen Dioxide (µg/m 3 )
	SO2         Sulfur Dioxide (µg/m 3 )
	CO         Carbon Monoxide emissions (µg/m 3 )
	CO2         Carbon Dioxide (µg/m 3 )
	PAHs         Polycyclic Aromatic Hydrocarbons (µg/m 3 )
	NH3         Ammonia trace (µg/m 3 )
	Pb         Lead (µg/m 3 )
	TEMP         Temperature (degrees Celsius)
	DEWP         Dew point temperature (degree Celsius)
	PRES         Pressure (hPa, <100, 1050>)
	RAIN         Rain (mm)
	WSPM         Wind Speed (m/s)
	WD         Wind Direction
	VOC         Volatile Organic Compounds
	CFCs         Chlorofluorocarbons
	C2H3NO5     Peroxyacetyl nitrate
	H2CO         Plywood emits formaldehyde
	GSTM1         Glutathione-S transferase M1
	1-OHP         1-hydroxypyrene
	2-OHF         2-hydroxyfluorene
	2-OHNa     2-hydroxynaphthalene
	N2         Nitrogen
	O2         Oxygen
	O3         Ozone
	Ar         Argon
	No         Neon
	CH4         Methane
	Hey         Helium
	Kr         Krypton
	I2         Iodine
	H2         Hydrogen
	Xe         Xenon
 
Selected columns contain ú scaled or _ _ _ _ averaged values of different time intervals . _ _ The reason is the application of different standards valid in different countries of the world.

# Assignment
Each pair will work with the assigned data set from the 3rd week .
	· Your task is to predict the dependent values of the " warning " variable using machine learning methods
At the same time , you will have to deal with several problems found in the data , such as data formats , missing , skewed values , etc.

## Phase 1 - exploratory analysis (in the 6th week): 15% = 15 points
Basic description of the data together with their characteristics (5b)
At this stage , state :
	· Number of records , number of attributes , their types ,
	· For selected significant attributes of their distribution, basic descriptive statistics, etc.
	· Pairwise data analysis: examine the relationships between selected pairs of attributes . 
	· Pairwise data analysis: Identify dependencies between pairs of attributes (e.g. correlations)
	· Paired data analysis: Identify dependencies between the predicted variable and other variables (potential predictors).
Identification of problems in the data with an initial solution (5b)
	· Identify problems in the data eg: inappropriate data structure, duplicate records, inconsistent formats, missing values, skewed values. There may be other problems not mentioned here in the data . 
	· First implement the proposed solution to data problems on the data. You can solve data problems iteratively in each phase and in all phases according to your needs . _
Formulation and statistical verification of data hypotheses (5b)
	· Formulate two hypotheses about the data in the context of the given prediction task . 
		An example of formulating a hypothesis: air quality measurements in a critical state have, on average, a different (higher/lower) value of a certain chemical ( or concentration flow ) than air quality measurements in a normal state .
	· Verify the formulated hypotheses with an appropriately chosen statistical test.
 
In the submitted report (Jupyter notebook), you should be able to answer the following questions :
	1. Does the data have a suitable format for further processing ? If not, what problems do they have ?
	2. Are some attributes dependent on each other? Which attributes does the predicted variable depend on?
	3. Are there missing values in the data? How do you plan to solve this problem ? 
	4. Do some attributes take on inconsistent or significantly deviated values?
	5. How do you plan/solve these identified issues?
 
week of the semester for practice . The pair will present the exploratory analysis performed in Jupyter Notebook to their trainee . Subsequently , one member of the pair electronically submits the report to the AIS system by Sunday, October 30 , 2022 , 11:59 p.m.
 
## Phase 2 - data preprocessing (in week 9): 20 points
week of the semester for practice . The pair will present the pre-processing performed in Jupyter Notebook to their trainee. Subsequently , one member of the pair electronically submits the report to the AIS system by Sunday 20 November 2022 23:59 .

## Phase 3 - machine learning (on the 12th day of the week): 20 points
week of the semester for practice . The pair will present the results of machine learning to their trainee in a Jupyter Notebook ) . Subsequently , one member of the pair electronically submits the report to the AIS system by Sunday 11/12/2022 23:59 .
 
