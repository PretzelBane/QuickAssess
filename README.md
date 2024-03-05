# QuickAssess
Data analysis package to do a quick assessment on equipment and work orders
The idea is to select a list of equipment IDs of interest and get a single Excel workbook with all the data and charts necessary to get a good idea of the reliability of the selected equipment.
Prociding cleaned-up, formatted dataframes also allows for initial investigation into any findings of interest from the charts.

A list of equipment IDs is submitted to SAP Business Objects which produces an Excel file of data that is the basis of this assessment
The analysis is done in R
A set of dataframes and plots are produced that show the status of various reliability & maintenance aspects

The Input file uploaded here is a sample
It is outputted by Buisiness Objects in a particular format that is necessary to work with this R-project

The Output file upladed here is a sample
It is the results of the R-project run on the sample input file
