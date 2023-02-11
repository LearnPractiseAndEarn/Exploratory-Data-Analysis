# Exploratory-Data-Analysis
notes from book "Practical Statistics for Data Scientists"

Data comes from many sources: sensor measurements, events, text, images, and vid‐ eos.\
a major challenge of data science is to harness this torrent of raw data into actionable infor‐ mation.\
\
to apply the statistical concepts ,unstructured raw data must be processed and manipulated into a structured form.
One of the commonest forms of structured data is a table with rows and columns
\

There are two basic types of structured data: numeric and categorical. 
\\
Numeric data comes in two forms: continuous, such as wind speed or time duration, and discrete, such as the count of the occurrence of an event. 
\
Categorical data takes only a fixed set of values, such as a type of TV screen (plasma, LCD, LED, etc.) or a state name (Ala‐ bama, Alaska, etc.). 
Binary data is an important special case of categorical data that takes on only one of two values, such as 0/1, yes/no, or true/false. 
Another useful type of categorical data is ordinal data in which the categories are ordered; an example of this is a numerical rating (1, 2, 3, 4, or 5).

\
Data is typically classified in software by type.\
• Data types include numeric (continuous, discrete) and categorical (binary, ordinal).\
• Data typing in software acts as a signal to the software on how to process the data.\


The typical frame of reference for an analysis in data science is a rectangular data object, like a spreadsheet or database table.
Rectangular data is the general term for a two-dimensional matrix with rows indicat‐ ing records (cases) and columns indicating features (variables); data frame is the spe‐ cific format in R and Python.\
The data doesn’t always start in this form: unstructured data (e.g., text) must be processed and manipulated so that it can be represented as a set of features in the rectangular data (see “Elements of Structured Data” on page 2). 
\Data in relational databases must be extracted and put into a single table for most data analysis and modeling tasks.
