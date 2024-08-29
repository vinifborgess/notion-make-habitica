# Cross-Platform Task Integrator using Habitica, Make and Notion
This project shows how to automate tasks across different platforms to improve productivity and management of daily activities.

![Image](https://github.com/vinifborgess/notion-make-habitica/blob/main/Cross-Platform%20Task%20Integrator%20using%20Habitica%2C%20Make%20and%20Notion%20-%20Architecture.png)

## Project description
In this repository, you will learn how to use an automation tool to connect Habitica, a gamification platform that encourages the development of healthy habits, with Notion, a powerful organization and productivity solution. By integrating these tools, you will be able to automate the creation of items in a Notion database whenever a new task is added to Habitica.

## Tools
👾 Habitica: An app that turns habit formation and task management into a game, offering virtual rewards to help users stay motivated.

🪢 Make: An automation solution that lets you create custom workflows to automate repetitive processes like database updates or file organization.

💭 Notion: A versatile platform that lets you manage notes, tasks, projects, and more in an intuitive, customizable environment.

## Main Goal
Demonstrate how to create automation flows that connect Habitica to Notion, making it easier to manage tasks between these two tools.

## Table of Contents

1. [Introduction](#preparing-make-environment)
2. [Scenario](#build-a-scenario)
3. [Database](#setting-up-the-habitica-configs)
4. [Habitica Step](#setting-up-the-habitica-configs)
5. [Notion Step](#setting-up-the-notion-configs)
6. [Conclusion](#run-and-improve-your-productivity)
 
## Preparing Make environment
Go to [Make](https://www.make.com/en). Click on the "Get started free" button, and choose an option to sign up for the platform.

After answering a few questions and completing the registration, you'll be taken to your dashboard.

## Creating the Task Integrator

## Build a Scenario
Now, let's create a "scenario," which is a predefined set of tasks and actions you can configure and reuse to automate specific processes. Instead of building a workflow from scratch, we'll select an existing scenario that fits our needs. On the left-hand menu, click "More," then select "Templates."

## Creating database in Notion using Habitica

In the search bar at the top right corner, type "Habitica" and choose the option that allows you to create database items in Notion using Habitica.

## Setting up the Habitica configs

Click on "Create new scenario from template" on the left side.

We'll start by setting up Habitica. Click on the Habitica icon, then select "Create a webhook." You can keep the default Webhook name or rename it as you wish. After that, click on "Create a connection."

Next, let's establish the connection between Make and Habitica. For this, you'll need your API Key and User ID from Habitica. 

In Habitica, go to your account settings in Habitica and click on "Site Data" to access this information.

Copy and paste the details into the corresponding fields in Make. 

Once you've filled them in, click "Save," and then click "OK" to finish. Your connection with Habitica is finally set up.

## Setting up the Notion configs

The process for Notion is quite similar. Click on the Notion icon, select "Create a connection," choose "Notion Public," and either keep or change the name of the connection as you prefer. Then, select the Notion page that contains the database you want to link with Habitica.

With the Notion connection established, you'll need to select which database to use. In the "Enter a Database ID" field, choose "Select from the list," click "Search," and after the search is complete, select the desired database.

## Run and improve your productivity!

Below that, you'll see the fields representing the properties of your database. Choose the appropriate type for each field and click "OK" to complete the setup. 

Return to the dashboard and remember to save your changes!

Finally, activate the integration flow by clicking the "ON" button on the right side. 

Now you have a connection between Habitica and Notion that allows you to create items in Habitica and view them in both platforms!
