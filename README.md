1. Please download Test.zip.001, Test.zip.002, Test.zip.003 and Test.zip.004 and unzip to D:\

2. Download SampleTalendMongoDB.zip and import to your Talend Workspace.

3. Open and run MainJob.
	This will :
	a. Unarchive the .gz files in D:\Test\rawdata
	b. Combine the files into pipe delimited as requested in D:\Test\dataextract folder
	c. Import pipe delimited files to local MongoDB instance
	d. Import dimension data into local MongoDB instance
	e. Create necessary indexes to improve performance

4. Run queries in result_query.txt in MongoDB
5. Verify results as per result.out
