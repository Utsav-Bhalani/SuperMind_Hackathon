# Social Media Performance Analysis Module

![Astra DB Logo](https://github.com/Utsav-Bhalani/SuperMind_Hackathon/blob/master/Images/Astra_DB_logo.png)
![Langflow Logo](https://github.com/Utsav-Bhalani/SuperMind_Hackathon/blob/master/Images/Langflow_logo.png)

### Project link : https://chatbot-tau-peach.vercel.app/

## Overview

This project is part of the Level Supermind Hackathon and focuses on analyzing social media performance metrics using Langflow and DataStax Astra DB. The project provides actionable insights into engagement data, helping optimize social media strategies.

## Features

### Dataset Simulation

Created a dataset with the following fields:
- **Post Type**: Types of posts such as image, video, or text.
- **Post Content**: Description or caption of the post.
- **Likes**: Number of likes received.
- **Comments**: Number of comments received.
- **Reach**: Number of users the post reached.
- **Platform**: Social media platform (e.g., Instagram, LinkedIn).

The dataset was stored in DataStax Astra DB for analysis.

### Data Storage
Leveraged DataStax Astra DB for scalable and secure data storage and querying.

### Workflow Creation
Developed a workflow using Langflow that:
- Accepts an input message in natural language.
- Queries Astra DB to compute engagement metrics such as average likes, comments, and reach.
- Uses GPT integration to generate actionable insights.

### Insights Generation
**Examples**:
- "Video posts on Instagram drive 2x more engagement than text posts."
- "Image posts on LinkedIn have a 30% higher reach than video posts."

### Tools & Technologies

- **Langflow**  
  Model Used: META LLAMA 3.1 - 8b  
  Used for designing workflows and GPT integration for insights generation.
  
- **DataStax Astra DB**  
  A reliable NoSQL database used for storing and querying social media data.

---

## How It Works

### Dataset Creation
Simulated a dataset with the following columns:
- **Post Type**: Image, Video, Text.
- **Post Content**: Description or caption of the post.
- **Likes**: Number of likes received.
- **Comments**: Number of comments received.
- **Reach**: Audience reach of the post.
- **Platform**: Social media platform (e.g., Instagram, LinkedIn).

The dataset was stored in DataStax Astra DB, enabling fast and efficient querying.

### Workflow Execution
Built a Langflow workflow that:
- Accepts inputs (post type, platform).
- Queries Astra DB to calculate average engagement metrics like likes, comments, and reach.
- Uses GPT for generating actionable insights.

### Insights Generation
The GPT integration provides insights to guide social media strategies, such as which post types perform best on specific platforms.

---

## Screenshots

![Langflow Workflow](https://github.com/Utsav-Bhalani/SuperMind_Hackathon/blob/master/Images/LangFLow.jpeg)

![Output Example](https://github.com/Utsav-Bhalani/SuperMind_Hackathon/blob/master/Images/Output.png)

---

## Authors

**Team Name**: Team YETI

- **Member 1**: Raj Desai
- **Member 2**: Om Modi
- **Member 3**: Utsav Bhalani
- **Member 4**: Mohit Patel

Feel free to contact us!!

![team Logo](https://github.com/Utsav-Bhalani/SuperMind_Hackathon/blob/master/Images/teamlogo.jpg)
