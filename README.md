# Data-Processing

The script will read csv files  in Raw_data.zip and make a directory 'output_data' and process the raw data in csv  into such as format:
where its sorted by date, with columns DL and UL and each wit h2 sub-columns 9am and 4pm.

## Todo
The date is hardcoded, this needs to be changed to be abstract!
The output path needs to be modified so that data is sorted into months in Output_data directory. i.e. ' output_data/{month}/... otherwise it will overwrite data inside output_data
