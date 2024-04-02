As a Senior Data and Analytics Engineer at Odido (formerly T-Mobile), I specialize in creating, managing, and optimizing data pipelines, databases, and analytical frameworks. My goal is to empower data-driven decision-making and enhance business intelligence. I excel in developing ETL processes, streamlining data workflows, and ensuring data reliability. I am proficient in SQL, Python, and BI tools like ThoughtSpot, as well as cloud platforms such as AWS. I collaborate effectively with diverse teams to leverage data strategically, driving insights and innovation across the organization.

Below, I outline the projects I've led and my key responsibilities at Odido.

# Project Background
At Odido, the Business Intelligence (BI) team manages data migration, ingestion, transformation, quality assurance, visualization, and documentation. Our focus areas include Finance, B2B (mobile and fixed data), and B2C (mobile and fixed data). We have multiple teams of skilled analytics engineers with deep domain knowledge in these areas, working together seamlessly to deliver top-notch results to internal stakeholders.

# B2C Fixed Team
The B2C fixed team is primarily tasked with managing Odido's fixed data ingestion, transformation, and visualization processes. Additionally, we successfully orchestrated the migration of data from Informatica to the AWS cloud, implemented rigorous data quality checks, and comprehensively documented all pipelines on Confluence.

My responsibilities within the B2C fixed team encompass a myriad of tasks, including:

## Data Ingestion: 
Utilizing tools like AWS DMS, Appflow, Lambda, and Sharepoint to ingest data from diverse sources.
## Data Transformation: 
Employing techniques such as data modeling, SQL, Python, and AWS Glue for data transformation, with AWS Redshift serving as our data warehouse.
## Business Intelligence: 
Leveraging ThoughtSpot as our primary BI tool at Odido, I'm responsible for crafting and delivering actionable insights to stakeholders.
## Team Management: 
In my capacity as a developer within a scrum team, I oversee developers' capacity and sprint planning.
## Tele2 Reports: 
Following the Tele2 acquisition by Odido, I've taken charge of generating B2C fixed data closing base reports for internal stakeholders.

# Data Pipelines
Below I've mentioned all the data pipelines I developed or developed together with other developers.

## Customer Lifecycle Status
The Customer Lifecycle Status pipeline is a vital tool in the B2C fixed stream. It helps track how customers interact with Odido's services over time. This includes when they sign up for new internet connections, activate their orders, add new products like faster internet speeds or TV packages, switch to new technologies like Fiber, and change addresses.

This pipeline is valuable for internal teams because it answers important questions like:

- How many customers have requested new connections?
- How many have recently activated their orders?
- How many have stopped using Odido's services?
- How many are still under Odido's one-year contract?

By understanding these trends, teams can make better decisions to improve customer satisfaction and retention.

## Case Ratio
The Case Ratio pipeline was created to track how customers interact with Odido's customer care and how their issues are resolved. It helps stakeholders answer questions such as:

- How many customers call each week/month/quarter to report problems with their orders or products?
- How many calls occur when orders/products are in different stages like processing, activation, moving, or termination?

## Fiber Network Coverage
The Fiber Network Coverage pipeline helps Odido understand the availability of new fiber technology for internet access in different neighborhoods. It provides answers to questions such as:

- When will fiber be available in a specific neighborhood?
- How many homes are currently covered by fiber technology?
- How many homes have applied for fiber connections?

## Other Pipelines
- Recently Activated Customers Feedback Report
- Fixed Sales Orders Pipeline
- Fixed Churn Orders Pipeline
- Hardware dashboard

When creating these pipelines, we utilized different data modeling techniques alongside methods like truncate and load, upsert, or SCD2 to smoothly insert data into the data warehouse.
