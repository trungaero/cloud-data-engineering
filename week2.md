# What is Data Engineering?
1. Batch vs Streaming vs Events
2. Building CLI tools with Click
3. Building Containerized Command-line tools
4. Advanced testing techniques for Code

# Objectives
1. Analyze best practices in Data Engineering
2. Apply software engineering best practices in testing to Command-line-tools
3. Build Python Command-line tools

# What is data engineering
the ability to build pipelines that transport data or transform data at a periodic basis (SW engineering around the movement and transport of data)

e.g: big data operations with Spark, event-driven infrastructures with AdaBoost lambda, handling jobs (nightly jobs that collect analytics and creat sales forecast)

## Batch vs Streaming vs Events

### Events:
do not consume resources until necessary

e.g: upload an image to S3, the code attached to such event performs converting from PNG to JPEG

### Batch 
batch job is a scheduled job

e.g: nightly job collecting data from db and perform forecast

### Streaming
in streaming job, data is constantly being updated

e.g: stock prices constantly update, forecast on stream

