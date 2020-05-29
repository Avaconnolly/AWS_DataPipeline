# AWS_DataPipeline
Exporting MySQL data to S3 using AWS data pipeline using the following objects: copyactivity, EC2resource, MySQLdatanode, S3datanode, SNSalarm
Following the AWS developer guide 

Benefits:
-Handle lots of data
-Accomidate a variety of data formats 
-Accomidate multiple data stores (S3, RDS, EC2, etc) 
-Reduce costs 
-"Drag and drop" console within the AWS interface 
-Built on a highly distributed, efficient infrastructure 
-Easy to dispatch work to one, or multiple machines/places 
-Offers full control and customization capabilities 

AWS Date Pipeline is a service that helps move & process data reliably between different computing & storage services & data at different times. You can effectively access data at it's holding location, transform & process it to the optimal scale & transfer results to S3, RDS, DynamoDB, and EMR. Fault tolerant, reproducible, and scalable is the gold standard. 

Step 1: Create the pipeline (make sure to configure the success & access figures) 
-Current point (5/29): ARN error codes 
Step 2: Create S3 bucket as a data output (done)
Step 3: Create and launch MySQL database as the data source (create a table, add test data values to the table) 
Step 4: Save and validate the pipeline 
Step 5: Verify the pipeline definition 
