
### Q1) How do you handle schema changes in ADF?
#### I would enable schema drift in ADF Mapping Data Flow so that the pipeline can handle changes in the source schema, such as new columns being added, without requiring manual changes to the pipeline.
#### For example, if a new Department column is added to the source, schema drift allows ADF to process the new column dynamically.

### Q2) What are triggers in ADF and how do you schedule pipelines?
#### Triggers in ADF are used to automatically start a pipeline based on a specific condition or schedule.
#### There are mainly three types of triggers:
#### Schedule Trigger – Runs a pipeline at a specific time or at regular intervals, such as every day at 10 PM.
#### Tumbling Window Trigger – Runs pipelines for fixed, continuous time windows, such as processing data hour by hour.
#### Event-based Trigger – Starts a pipeline when a specific event occurs.

### Q3) How do you optimize ADF pipelines?
#### 
