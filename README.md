# Behavior-cleaning
Cleans and formats outputs of fish and invertebrate behavior data exported 
from Noldus Observer software

Data are exported as .xlsx files
Attributes are stored in the column 'Observation', separated with underscore,
using a consistent order

Important to note that the datetime columns refer to when the video was
scored, not when the video was created

Typically an export contains both abundance and behavior data, this code 
extracts and formats just the behavior data
