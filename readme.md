adf_ile: contains all the created services

Task_1: Move files from Blob to Adl
  * Create Blob storage
  * Create Azure lake storage
  * Create linked Services for both blob and adl
  * Create Datasets for both
  * Setup ADF pipeline for migrating files
  * Use 'Copy Data' activity and establish link with source and sink
  * Publish the pipeline for saving
  * Debug/Triger Now option to run the pipeline
  * Use Monitor tab to view the status of the pipeline
	* Check Adl to view the migrated files
  
 Task_2: Delete files from Adl
  * Create ADF pipeline
  * Use 'Delete' activity
  * link Source and logging to the containers
  * Publish and run the pipeline
