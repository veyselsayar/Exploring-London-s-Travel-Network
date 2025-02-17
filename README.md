London, or as the Romans called it "Londonium"! Home to 
over 8.5 million residents
 who speak over 
300 languages
. While the City of London is a little over one square mile (hence its nickname "The Square Mile"), Greater London has grown to encompass 32 boroughs spanning a total area of 606 square miles!

underground train leaving a platform

Given the city's roads were originally designed for horse and cart, this area and population growth has required the development of an efficient public transport system! Since the year 2000, this has been through the local government body called Transport for London, or TfL, which is managed by the London Mayor's office. Their remit covers the London Underground, Overground, Docklands Light Railway (DLR), buses, trams, river services (clipper and 
Emirates Airline cable car
), roads, and even taxis.

The Mayor of London's office make their data available to the public 
here
. In this project, you will work with a slightly modified version of a dataset containing information about public transport journey volume by transport type.

The data has been loaded into a Snowflake database called TFL with a single table called JOURNEYS, including the following data:

TFL.JOURNEYS
Column	Definition	Data type
MONTH	Month in number format, e.g., 1 equals January	INTEGER
YEAR	Year	INTEGER
DAYS	Number of days in the given month	INTEGER
REPORT_DATE	Date that the data was reported	DATE
JOURNEY_TYPE	Method of transport used	VARCHAR
JOURNEYS_MILLIONS	Millions of journeys, measured in decimals	FLOAT
Note that in Snowflake all databases, tables, and columns are upper case by default.

You will execute SQL queries to answer three questions, as listed in the instructions.


https://www.datacamp.com/datalab/w/1895d986-638c-4237-b99a-4b5c300b0d6d/edit
