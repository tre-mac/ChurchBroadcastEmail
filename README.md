# ChurchBroadcastEmail

Church Email Broadcaster (Azure Automation Project) Overview

The Church Email Broadcaster is a cloud-based automation workflow built entirely on Microsoft Azure that automatically sends out weekly Bible reading plan emails to church members.


Every Monday and Friday, the system retrieves the current week’s reading plan from a cloud database and sends a customized email to each member. Future updates will add Member Group Targeting so the pastor can message the entire church or specific teams like the Dream Team (Setup Team).

This project demonstrates how to combine Azure Logic Apps and Azure Cosmos DB into an automated communication system with virtually minimum maintenance.

🔧 Tech Stack

Automation & Orchestration: Azure Logic Apps
Database: Azure Cosmos DB (NoSQL JSON documents)
Email Service: Outlook Connector (Microsoft 365 Integration)
Scheduling: Recurrence Trigger (Automated twice-weekly runs)
Cloud Platform: Microsoft Azure
Monitoring: Logic App Run History & Execution Logs

💡 Features

📅 Automated Scheduling – Sends emails every Monday and Friday at noon without manual intervention.
📖 Dynamic Reading Plan Retrieval – Logic App queries Cosmos DB for the current week’s reading plan.
📬 Personalized Emails – Each member receives a customized HTML message with their name and the week’s plan.
🎯 Member Group Targeting (Planned) – Send updates to the full congregation or specific groups like the Dream Team.
⚡ Fully Serverless – No traditional servers or local infrastructure needed.

This project highlights the power of Azure serverless automation — connecting data, logic, and communication tools to streamline real-world processes.
