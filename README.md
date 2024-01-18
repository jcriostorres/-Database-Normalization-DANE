### DATA MODELING TO CHARACTERIZE THE DISABLED POPULATION IN COLOMBIA

With the participation of the Organización Nacional de Ciegos Españoles (ONCE) and the University of Antioquia, this project aims to create a data normalization and cleaning model using the Python programming language to characterize the disabled population in Colombia through the use of secondary sources such as databases and statistical reports from DANE. The project also aims to access the main indicators related to the integration of people with disabilities in the job market, as well as other complementary analyses, which will be visually represented on the Observatorio sobre discapacidad y mercado de trabajo en España ODISMET website as a means of disseminating knowledge and research to interested members of the public.

**Table of Contents**

[TOC]

#Problem Statement
It is essential to have access to suitable secondary sources that guarantee the quality and criteria of the indicators needed by Odismet to present the issues on its web platform. These indicators are classified into six thematic modules:

- Labor integration and trends in the job market.
- Working conditions and professional trajectories.
- Education and vocational training.
- Employment policies for people with disabilities.
- Social benefits.
- Actions aimed at job creation.
- Occupation and training for employment.

Similarly, it is necessary to investigate whether the chosen DANE data is suitable for Modeling and Normalization, using methods of data cleaning and preparation. Data cleaning is the process of detecting and correcting or eliminating corrupt or inaccurate records from a set of records, table, or database. It involves identifying incomplete, incorrect, inaccurate, or irrelevant parts of the data for subsequent replacement, modification, or elimination of dirty or imprecise data

#Justification
It is important for Colombia to generate a comprehensive report with a detailed appendix of indicators and variables related to Disability and the labor market, distributed across the six thematic modules previously mentioned in the problem statement. Each indicator should be systematically presented through tables, maps, and statistical graphs, accompanied by a detailed explanation of the main results obtained. Furthermore, the intention is to create a data model that allows for processing and analyzing all the information collected and produced by DANE, including its structure and relationships between them.

#Objective

Create a Data Normalization model to characterize the population with disabilities in Colombia, using secondary sources from Dirección Nacional de Estadística DANE.

##Specific objectives

1. Identify the main indicators based on secondary sources and guidance from the ONCE Foundation.

3. Conduct a critical analysis related to the quality and coherence of the data obtained from different secondary sources.

5. Normalize the data to characterize the population with disabilities (Extract, Transform, Load).

7. Prepare a report containing the baseline of the main indicators of the population with disabilities in Colombia.

#Theoretical Framework

To consolidate all statistical data on disability in Colombia from the National Administrative Department of Statistics (DANE), the entity responsible for planning, surveying, processing, analyzing, and disseminating official statistics in Colombia, it is necessary to meet quality standards. This involves processes and methods of normalization and cleaning, which will be further elaborated below:

- **Data Quality Management**
- **ISO/IEC 25012 standard**
- **Data Cleaning**: Python libraries such as Pandas with functions like dropna() to remove rows with missing values, fillna() to fill in missing values, etc.
- **Normalization**: Box-Cox Transformation method.

The key tools for creating the normalized data model include:
- Python programming language
- Jupyter Notebook, a Python IDE used for data science
- Python libraries such as Pandas and Numpy
- Microsoft Excel spreadsheets
- GitHub, allowing the uploading of code repositories to store them in the Git version control system.

Additionally, it is important to follow a reference guide for Data Analytics projects such as CRISP-DM, which includes descriptions of the normal phases of a project, the necessary tasks in each phase, and an explanation of the relationships between tasks. It consists of 6 phases:

1. **Business Understanding**: Understand the business and determine the required tools.
2. **Data Understanding**: Understand the data and its structure.
3. **Data Preparation**: Address data behavior, missing or outlier data, normalization, etc.
4. **Modeling**: Begin working to make predictions or classifications.
5. **Evaluation**: Check if model results align with project objectives and make sense.
6. **Deployment**: Implement the data in a production environment to observe results (IBM Documentation, 2021).

#Results

A total of eleven indicators were successfully identified using the information provided by DANE. These indicators meet the parameters set by ONCE for the opening of the observatory and were subsequently loaded into the content manager Colombia Odismet:

** 1. [Población con discapacidad en Colombia](https://odismet.co/banco-de-datos/datos-sociodemograficos "Población con discapacidad en Colombia")**
**2. [Grupos de discapacidad](https://odismet.co/banco-de-datos/condiciones-de-vida "Grupos de discapacidad")**
**3. [Población en edad activa con discapacidad en Colombia](https://odismet.co/banco-de-datos/datos-sociodemograficos "Población en edad activa con discapacidad en Colombia")**
**4. [Tasa de prevalencia de la población con discapacidad en edad activa](https://odismet.co/banco-de-datos/datos-sociodemograficos "Tasa de prevalencia de la población con discapacidad en edad activa")**
**5. [Tasa de empleo de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Tasa de empleo de la población con discapacidad")**
**6. [Tasa de desempleo de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Tasa de desempleo de la población con discapacidad")**
**7.[ Tasa de actividad de la población de la población con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales " Tasa de actividad de la población de la población con discapacidad")**
**8. [Tasa de riesgo de pobreza o pobreza multidimensional](https://odismet.co/banco-de-datos/condiciones-de-vida "Tasa de riesgo de pobreza o pobreza multidimensional")**
**9. [Ocupados por tipo de empleo](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Ocupados por tipo de empleo")**
**10. [Proporción de trabajadores independientes con discapacidad](https://odismet.co/banco-de-datos/trabajo-y-condiciones-laborales "Proporción de trabajadores independientes con discapacidad")**
**11. [Nivel de formación alcanzada por las personas con discapacidad](https://odismet.co/banco-de-datos/educacion-y-formacion-profesional "Nivel de formación alcanzada por las personas con discapacidad") **
