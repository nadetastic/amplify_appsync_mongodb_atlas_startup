
# Accelerate Application Modernization: Low Code Application Development with AWS Amplify, AppSync, and MongoDB Atlas

In today’s fast-paced digital landscape, turning innovative ideas into fully functional applications quickly and efficiently is essential for developers, startups, and business consultants. This repository is designed to empower you to do just that. By leveraging AWS Amplify for seamless front-end development, AppSync for robust and scalable backend services, and MongoDB Atlas for a flexible and powerful database solution, it offers a comprehensive, low-code solution that drastically reduces development time while maintaining high standards of performance and scalability.

This repository provides a starter template for building applications with React+Vite and AWS Amplify, seamlessly connecting to MongoDB Atlas. It simplifies the setup for authentication, API integration, and database capabilities. With a foundational React application pre-integrated with AWS Amplify, this template is optimized for scalability and performance, making it perfect for developers, startups, and business consultants seeking to jumpstart their projects with pre-configured AWS services like Cognito, AppSync, and MongoDB Atlas


## AWS Amplify
AWS Amplify is a comprehensive development platform that simplifies the creation of full-stack applications with minimal configuration. It provides a set of tools and services that integrate seamlessly with popular frameworks like React, Angular, and Vue, enabling developers to easily set up scalable backends, manage authentication, and deploy applications with a few simple commands. The 2.0 features of AWS Amplify enhance support for CI/CD workflows, improve the developer experience with the Amplify CLI, and expand capabilities for backend infrastructure as code. These updates facilitate easier management and deployment of cloud resources, integration of serverless functions, and connection to MongoDB Atlas data sources through AWS AppSync and DataAPI, thus significantly reducing the time and effort required to build and scale modern applications

## AWS AppSync
AWS AppSync is a fully managed service that simplifies the development of GraphQL APIs by automatically handling data fetching, real-time updates, and offline synchronization. It seamlessly integrates with various data sources, including MongoDB Atlas through DataAPI and Drivers, allowing developers to build scalable and flexible applications with ease. AppSync’s features include built-in support for real-time data updates and offline access, reducing the complexity of managing data interactions and enhancing application performance

## MongoDB Atlas

MongoDB Atlas is a fully managed cloud database service known for its operational excellence and scalability. It offers advanced features like automated backups, scaling, and monitoring, ensuring high availability and performance. Notably, Atlas includes Vector Search capabilities, which are optimized for Generative AI use cases, enabling efficient search and retrieval of high-dimensional data. This feature enhances the ability to perform complex queries and data analysis, making it ideal for applications requiring sophisticated data interactions and AI-driven insights

## Reference Architecture 

![Reference Architecture](/images/Reference_Architecture.png)


## Prerequisites

MongoDB Atlas

AWS Account


## Features

- **Authentication**: Setup with Amazon Cognito for secure user authentication.
- **API**: Ready-to-use GraphQL endpoint with AWS AppSync.
- **Database**: Real-time database powered by MongoDB Atlas.


## Deploying to AWS

### Step 1

#### Set up the MongoDB Atlas cluster


#### Set up the DATA API with API Key

![Set up Data API](/images/setup_DataAPI.png)

![Generate API Key](/images/generate_API_KEY.png)



### Step 2

Clone the GitHub Repository

``` git clone https://github.com/mongodb-partners/amplify_appsync_mongodb_atlas_startup.git```

### Step 3

Setup the AWS CLI credentials

``` aws configure ```

### Step 4

#### Deploy the To-do Application in AWS Amplify


Open the AWS Amplify console and Select the Github Option 


![GitHub Repo Selection](/images/GitHub.png)


Configure the GitHub Repository

![AWS Amplify GitHub Repo](/images/GitHub_Configuration.png)


Select the GitHub Repository and click Next

![AWS Amplify GitHub Repo](/images/GitHub_Repo_Selection.png)



Set all other options to default and deploy

![alt text](/images/amplify_console_overview.png)


#### Configure the Environment Variables






For detailed instructions on deploying your application, refer to the [deployment section](https://docs.amplify.aws/react/start/quickstart/#deploy-a-fullstack-app-to-aws) of our documentation.

## Contributing


## License

