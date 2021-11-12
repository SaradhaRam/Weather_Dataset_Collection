# Weather_Dataset_Collection

#Step1 - 
Add all the Pthon libraries / dependencies

#Step2 - Check the inputfile using pandas or read using csv.reader ( 2 ways )

#Step3 - In the <input_file.csv> make sure you have your store list file. ( required file )
I have used 6 fields ( storename, store#, Latitude, Longitude ,Begindate, Enddate )
example: abc,123,40.0,70.0,date1,date2

#Step4 -  Call the API using the base URL. Add your API KEY 

You will get the weather data for the begin and end date that you have mentioned in the base URL.
using the csv.writer the file will be stored by store name. 

#Step5 - <YOUR DIRECTORY PATH> should be the file path that you have received from the csv writer. 
  
#Step6 - use the csv.reader to read the file received.
  select only the required rows and write it to a file using csv.writer
  

