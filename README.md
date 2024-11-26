# maybank
Test assigned by maybank
Job: A batch job that consists of one or more steps.
Step: A step within a job that performs a unit of work (such as reading, processing, and writing).
ItemReader: Reads data from a source (like a database, file, etc.).
ItemProcessor: Processes the data between read and write operations (e.g., transforming or filtering).
ItemWriter: Writes the processed data to a destination (like a database or file).
JobLauncher: A component used to trigger the execution of a job.
JobRepository: Stores the job execution metadata such as job status, parameters, and step execution status.
JobExecution: Stores the status and details of a job's execution.
StepExecution: Stores the status and details of a step's execution
