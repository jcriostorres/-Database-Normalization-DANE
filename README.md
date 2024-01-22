### DATA MODELING TO CHARACTERIZE THE DISABLED POPULATION IN COLOMBIA

With the participation of the Organización Nacional de Ciegos Españoles (ONCE) and the University of Antioquia, this project aims to create a data normalization and cleaning model using the Python programming language to characterize the disabled population in Colombia through the use of secondary sources such as databases and statistical reports from DANE. The project also aims to access the main indicators related to the integration of people with disabilities in the job market, as well as other complementary analyses, which will be visually represented on the Observatorio sobre discapacidad y mercado de trabajo en España ODISMET website as a means of disseminating knowledge and research to interested members of the public.

**Table of Contents**

* [Problem Statement](#problem-statement)
* [Justification](#justification)
* [Objective](#objective)
* [Specific Objectives](#specific-objectives)
* [Theoretical Framework](#theoretical-framework)
* [Results](#results)
* [Suggestions](#suggestions)
* [Special Thanks](#special-thanks)
* [Links](#links)


# Problem Statement
It is essential to have access to suitable secondary sources that guarantee the quality and criteria of the indicators needed by Odismet to present the issues on its web platform. These indicators are classified into six thematic modules:

- Labor integration and trends in the job market.
- Working conditions and professional trajectories.
- Education and vocational training.
- Employment policies for people with disabilities.
- Social benefits.
- Actions aimed at job creation.
- Occupation and training for employment.

Similarly, it is necessary to investigate whether the chosen DANE data is suitable for Modeling and Normalization, using methods of data cleaning and preparation. Data cleaning is the process of detecting and correcting or eliminating corrupt or inaccurate records from a set of records, table, or database. It involves identifying incomplete, incorrect, inaccurate, or irrelevant parts of the data for subsequent replacement, modification, or elimination of dirty or imprecise data.

   - Workbook Name: 
   - Datasets: [Labor market (Employment and unemployment DANE) Historical](https://www.dane.gov.co/index.php/estadisticas-por-tema/mercado-laboral/empleo-y-desempleo/geih-historicos) and [National Quality of Life Survey ECV 2021 DANE](https://www.dane.gov.co/index.php/estadisticas-por-tema/salud/calidad-de-vida-ecv/encuesta-nacional-de-calidad-de-vida-ecv-2021])
     
  
# Justification
It is important for Colombia to generate a comprehensive report with a detailed appendix of indicators and variables related to Disability and the labor market, distributed across the six thematic modules previously mentioned in the problem statement. Each indicator should be systematically presented through tables, maps, and statistical graphs, accompanied by a detailed explanation of the main results obtained. Furthermore, the intention is to create a data model that allows for processing and analyzing all the information collected and produced by DANE, including its structure and relationships between them.

# Objective

Create a Data Normalization model to characterize the population with disabilities in Colombia, using secondary sources from Dirección Nacional de Estadística DANE.

## Specific objectives

1. Identify the main indicators based on secondary sources and guidance from the ONCE Foundation.

3. Conduct a critical analysis related to the quality and coherence of the data obtained from different secondary sources.

5. Normalize the data to characterize the population with disabilities (**Extract, Transform, Load**).

7. Prepare a report containing the baseline of the main indicators of the population with disabilities in Colombia.

# Theoretical Framework

To consolidate all statistical data on disability in Colombia from the National Administrative Department of Statistics (DANE), the entity responsible for planning, surveying, processing, analyzing, and disseminating official statistics in Colombia, it is necessary to meet quality standards. This involves processes and methods of normalization and cleaning, which will be further elaborated below:

- **Data Quality Management**
- **ISO/IEC 25012 standard**
- **Data Cleaning**: Python libraries such as Pandas with functions like:
  
| Function name | Description                    |
| ------------- | ------------------------------ |
| `dropna()`    | Remove rows with missing values|
| `fillna()`    | Fill in missing values         |



The key tools for creating the normalized data model include:

- Microsoft **Excel** spreadsheets
- **Python** <code><a href="https://www.python.org/" target="_blank"><img height="45" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></a></code> programming language
- **Jupyter Notebook**  <code><a href="https://jupyter.org/" target="_blank"><img height="45" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg"></a></code>  a Python IDE used for Data Science
- Python **libraries** such as:
  
| libraries     | Description  |
| ------------- | ------------- |
| Pandas        | Has applications for data analytics, wrangling, and cleaning. <code><a href="https://pandas.pydata.org/" target="_blank"><img height="45" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg"></a></code>  |
| Numpy         | Python’s basic numerical computation package. <code><a href="https://numpy.org/" target="_blank"><img height="45" src="https://www.vectorlogo.zone/logos/numpy/numpy-ar21.svg"></a></code> |
| Matplotlib    | Can create a variety of graphs, such as line graphs, scatter graphs, histograms, heat plots, and interactive 2D graphs. <code><a href="https://matplotlib.org/" target="_blank"><img height="45" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg"></a></code>  |
| Plotly        | Can create a high-quality data visualizations, such as scatter plots, heatmaps, histograms, box plots, bubble charts, and polar charts.  |
| Seaborn       | Can create visualizations of statistical data. It is built on top of Matplotlib and provides a high-level interface for creating static.  |

- **Normalization**: **Box-Cox** Transformation method.
- **Tableau** <code><img height="40" width="80" src="https://raw.githubusercontent.com/logo/Tableau/master/images/logo.svg"></code> : It helps users create different charts, graphs, maps, dashboards, and stories for visualizing and analyzing data, to help in making business decisions.
- **GitHub** ![GitHub](https://img.shields.io/badge/-GitHub-181717?&logo=github) : allowing the uploading of code repositories to store them in the Git version control system.

Additionally, it is important to follow a reference guide for Data Analytics projects such as CRISP-DM, which includes descriptions of the normal phases of a project, the necessary tasks in each phase, and an explanation of the relationships between tasks. It consists of 6 phases:

1. **Business Understanding**: Understand the business and determine the required tools.
2. **Data Understanding**: Understand the data and its structure.
3. **Data Preparation**: Address data behavior, missing or outlier data, normalization, etc.
4. **Modeling**: Begin working to make predictions or classifications.
5. **Evaluation**: Check if model results align with project objectives and make sense.
6. **Deployment**: Implement the data in a production environment to observe results (IBM Documentation, 2021).

# Results

After conducting a selection criterion of various secondary sources with the help of Splicing Tables and a data dictionary, there are several reasons why DANE data was chosen for this project (Great Integrated Household Survey - GEIH and National Quality of Life Survey - ECV), taking into account the ISO/IEC 25012 standard. Completeness was not found, which is the degree to which all data attributes are present. Some DANE data tables did not comply with the dimensions or areas required by the Odismet Indicators. In the case of Portability, it was evident in the second part of the project during data preparation for normalization and modeling that it lacked the capability to be transferred to a hardware or software environment such as Jupyter Notebook or a CSV file

It was observed that missing values were represented either as NaN or "Unnamed," which could affect the efficiency of data processing. It is important to note that the DANE data identified as indicators are stored in xlsx files with multiple sheets. These sheets have headers filled with design elements, images, footers, and merged cells instead of clear column titles. This indicates that the data is not clean for data analysis. Consequently, basic cleaning of rows and columns using Python methods was indispensable.
A total of eleven indicators were successfully identified using the information provided by DANE. These indicators meet the parameters set by ONCE for the opening of the observatory and were subsequently loaded into the content manager Colombia Odismet:

 1. [Población con discapacidad en Colombia](https://odismet.co/banco-de-datos/datos-sociodemograficos "Población con discapacidad en Colombia")
 2. [Grupos de discapacidad](https://odismet.co/banco-de-datos/condiciones-de-vida "Grupos de discapacidad")
 3. [Población en edad activa con discapacidad en Colombia](https://odismet.co/banco-de-datos/datos-sociodemograficos "Población en edad activa con discapacidad en Colombia")
 4. [Tasa de prevalencia de la población con discapacidad en edad activa](https://odismet.co/banco-de-datos/datos-sociodemograficos "Tasa de prevalencia de la población con discapacidad en edad activa")
 5. [Tasa de empleo de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Tasa de empleo de la población con discapacidad")
 6. [Tasa de desempleo de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Tasa de desempleo de la población con discapacidad")
 7. [Tasa de actividad de la población de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales " Tasa de actividad de la población de la población con discapacidad")
 8. [Tasa de riesgo de pobreza o pobreza multidimensional](https://odismet.co/banco-de-datos/condiciones-de-vida "Tasa de riesgo de pobreza o pobreza multidimensional")
 9. [Ocupados por tipo de empleo](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Ocupados por tipo de empleo")
 10. [Proporción de trabajadores independientes con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Proporción de trabajadores independientes con discapacidad")
 11. [Nivel de formación alcanzada por las personas con discapacidad](https://odismet.co/banco-de-datos/educacion-y-formacion-profesional "Nivel de formación alcanzada por las personas con discapacidad")


# Suggestions

Collaborating with DANE to improve the quality and availability of disability data in Colombia is an excellent idea. Establishing agreements for the exchange of information and joint development of standardized protocols and methodologies can be beneficial for both parties. This collaboration can help ensure the accuracy and consistency of data, thereby facilitating more effective analysis and informed decision-making on disability-related issues. Additionally, strengthening the relationship with DANE could contribute to the continuous improvement of data collection and reporting processes in the field of disability.

# Special Thanks
- [Universidad de Antioquia](https://www.udea.edu.co/wps/portal/udea/web/inicio/unidades-academicas/ingenieria/estudiar-facultad/pregrados/ingenieria-sistemas)
- Ana Lucía Pérez Patiño
- Astrid Duque Ramos
- Organización Nacional de Ciegos Españoles (ONCE)
- [Kaggle](https://www.kaggle.com/learn/data-cleaning) [![Kaggle](https://img.shields.io/badge/-Kaggle-20beff?style=flat&logo=Kaggle&logoColor=white)](https://kaggle.com/sachin93)



# Links
- Github: `<link>` [Database-Normalization-DANE](https://github.com/jcriostorres/Database-Normalization-DANE)
- Observatory: `<link>` [Odismet](https://odismet.co/banco-de-datos/datos-sociodemograficos)

![ViewCount](https://views.whatilearened.today/views/github/jcriostorres/jcriostorres.svg) [![Thanks!](https://img.shields.io/badge/Thanks%20for%20visiting-!-1EAEDB.svg)](https://verma-anushka.github.io/anushkaverma/)
