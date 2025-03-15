Mini-Procedure:

Download the Data: Go to the Bgeometrics website.

Download the XLS file containing NUPL and Bitcoin / SOPR and BITCOIN price data.
The two files must start on the same date and end on the same date.

Save the files in CSV format.
The file names must match those included in the code. 

print("Columns in bitcoin-nupl.csv:", nupl_data.columns)
print("Columns in bitcoin-sopr-spent-outpu.csv:", sopr_data.columns)

Prepare the Data for Python:

Open the CSV file in Excel or a text editor.

Ensure the DateTime column contains dates without the time ("00:00:00").

Remove the time, keeping only the YYYY-MM-DD format (then use Ctrl+H)

Replace commas with periods in the BTC Price,NUPL/Sopr columns (select the column, then use Ctrl+H).
