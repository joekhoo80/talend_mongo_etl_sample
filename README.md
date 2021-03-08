#Instructions 

1. Please download *Test.zip.001*, *Test.zip.002*, *Test.zip.003* and *Test.zip.004* and unzip to *D:\*
1. Download *SampleTalendMongoDB.zip* and import to your Talend Workspace.
1. Open and run *MainJob*. This will :
	1. Unarchive the .gz files in *D:\Test\rawdata*
	1. Combine the files into pipe delimited as requested in *D:\Test\dataextract* folder
	1. Import pipe delimited files to local MongoDB instance
	1. Import dimension data into local MongoDB instance
	1. Create necessary indexes to improve performance

1. Run queries in *result_query.txt* in MongoDB
1. Verify results as per *result.out*
