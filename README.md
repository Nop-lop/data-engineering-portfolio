## Data Engineering Portfolio
Welcome to my Data Engineering Portfolio page! Be sure to also check my [Data Science and Machine Learning Projects]()

## Projects

### Bike Rental Management ([writeup]())
A relational database with analytics-ready views connecting Citi Bike and public weather datasets. The project involves:

- Inspecting and cleaning both datasets
- Developing a relational database structure
- Implementing the database in PostgreSQL and inserting the dataset
- Developing flexible analytics-ready views on top of the relational database

### Subscrciber Cancellation Pipeline ([writeup]())
A semi-automated bash+python pipeline to regularly transform a messy SQLite database into a clean source of truth for an analytics team. The pipeline

- Performs unit tests to confirm data validity
- Writes human-readable errors to an error log
- Automatically checks and updates changelogs
- Updates a production database with new clean data

### NoSQL Cloud Deployment ([writeup]())
A project to deploy the output of subscriber-pipeline to a MongoDB database on DigitalOcean Cloud. The project includes

- Creating a new MongoDB instance on DigitalOcean
- Connecting to the cloud MongoDB using MongoDB Compass
- Uploading the clean dataset as a NoSQL Collection
- Validating the final dataset

------
Let the data-wars ensue! ⚔️ ⚔️
