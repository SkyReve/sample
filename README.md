# sample
Sample application using SkyReve

## Quick Start
1. Follow the simulation using the code under ```./skyreve/blog/recent/get.apy```
2. Open ```./apps/html/index.html``` on your browser.

# Blog Sample

A simple HTML-based blog web application to test the Skyreve Platform blog API.

## Setup Instructions

### 1. Create a new project in [Skyreve](https://app.skyreve.cloud)
1. Go to the Skyreve space
2. Click "New Project"
3. Fill in the project details
4. Click "Create"

![Create Project](frontend/images/create-project.png)

### 2. Create a data table named "Blog"
1. In your project, go to the "Data" menu
2. Create a new table with the following columns:
   - title (text)
   - content (text)
   - posted_at (timestamp)

![Create Table](frontend/images/create-table.png)

### 3. Create a REST API endpoint
1. Go to "API" section
2. Create a new endpoint with:
   - Method: GET
   - Path: /blogs
   - Select the blogs table as the data source

![Create API](frontend/images/create-api.png)

### 4. Find your API URL
1. In the API section, locate your endpoint URL
2. Copy this URL to use in the tester

![API URL](frontend/images/api-url.png)

### 5. Deploy to staging/production (Optional)
Use the deployment options to push your changes to staging or production environments.

![Deploy](frontend/images/deploy.png)

### 6. Fork from staging/production (Optional)
Create a fork from staging or production to make changes without affecting the live environment.

![Fork](frontend/images/fork.png)
