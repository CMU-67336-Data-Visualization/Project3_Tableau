# 67-336 Project 03: Tableau + Observable

## Analyzing Pittsburgh Police Incidents with Tableau

**Course:** 67-336 Building Data Visualization into Information Systems  
**Instructor:** Shihong Huang  
**TAs:** Wenchao Hu, Lexi Kronowitz  
**Due Date:** TBD  
**Submission Format:** **Deployed Observable Notebook Link & Tableau Public Dashboard Link**

---

## Assignment Overview

This project provides an opportunity to analyze public safety data using Tableau and communicate your finding using Observable. You will create two interactive dashboards using publicly available datasets from the Western Pennsylvania Regional Data Center (WPRDC). Your work should uncover meaningful insights and demonstrate best practices in visual storytelling and dashboard design. In addition to building dashboards in Tableau, you will create a project write-up and reflection in Observable. Finally, your notebook should be deployed using Vercel. 

---

## Learning Objectives

- Analyze and visualize real-world public safety data in Tableau.
- Identify meaningful trends and patterns in Pittsburgh crime data.
- Apply principles of interactivity and design in dashboard creation.
- Communicate findings in a reproducible and web-published Observable notebook.
- Reflect critically on your analytical and design decisions.

---

## Dataset

Use the following datasets from the Western Pennsylvania Regional Data Center (WPRDC):

- [Police Incident Blotter](https://data.wprdc.org/dataset/police-incident-blotter)
- [Arrest Data](https://data.wprdc.org/dataset/arrest-data)

Review the metadata, variable descriptions, and time ranges. You may choose to filter, clean, or transform the data prior to visualization.

---

## Step 1: Define Your Data Story

Begin by selecting a focused analytical question or theme. Your data story should be driven by this question and supported by the data. Suggested directions include (but not limited to):

- Crime trends over time (by week, month, or year)
- Spatial distribution or hotspots by neighborhood or zone
- Patterns by time of day or day of week
- Distribution of crime types or severity
- Relationship between incident types and arrest frequency

Clearly articulate the story your visualizations aim to tell.

---

## Step 2: Build Two Interactive Dashboards in Tableau

Using Tableau, develop two separate dashboards, each providing a distinct perspective on your data story. Please make sure it is specific, relevant, and researchable. The dashboards must be interactive, allowing users to explore the data through filters, tooltips, or other user actions.  

Example dashboard formats include:

**Dashboard 1: Time-Series Analysis**  
- Show trends over time (e.g., incidents by month or week)  
- Include filtering by crime type or location  
- Use tooltips to show incident details  

**Dashboard 2: Geographic or Categorical Analysis**  
- Map view of incident or arrest locations by neighborhood or zone  
- Filters for incident category or time range  
- Use color, shape, or size to indicate patterns  

Publish both dashboards to Tableau Public and ensure they are publicly accessible. You will state your analytical question clearly in your Observable introduction.

---

## **Step 3: Create an Observable Notebook**

Use Observable (https://observablehq.com/) to create a dashboard that serves as your final project report. Refer to lab 02 to get a refresher on how to do this! 

### 3.1 Structure Your Notebook
Your Observable notebook should include:

- A project title and introduction (describe your question and why it matters)
- Embedded Tableau dashboards
- Summary and analysis of findings
- Your written reflection (see Step 4) 
- References to datasets or outside sources

### 3.2 Embed Tableau Dashboards

#### Instructions:
1. **Publish** your dashboard to Tableau Public. Make sure your dashboard is publicly accessible on Tableau Public.
2. **Click "Share"**, and copy the embed code provided in the "Embed Code" section.
3. In Observable, paste the embed code in an HTML cell.

#### Example:
```js
md`<iframe src="https://public.tableau.com/views/YOUR_VIEW" width="800" height="600"></iframe>`
```

- An introduction to your project and data story (ie. what is your analytical question, why you choose these questions / theme, and what you hope to show to your dashboards, etc)
- Embedded links to your Tableau dashboards.

---

## Step 4: Write a Reflection (in Observable)

Include this reflection as a section within your Observable notebook. Address the following questions (600-800 words):
- What data story did you focus on, and why?
- What insights emerged from your analysis?
- What design decisions did you make, and what were your reasons?
- What challenges did you encounter, and how did you resolve them?
- What would you change or improve with more time?

---

## Step 5: Deploy with Vercel 

Refer to previous lab instructions on how to deploy your Observable notebook using Vercel. Share the deployed Vercel link in your submission. 

---

## Submission Requirements / Checklist

Submit the following:

1. Vercel deployed link of your Observable notebook
2. A working link to your Tableau Public dashboards  

Ensure your submissions are viewable without login or permission requests.

---

## Grading Rubric (100 Points)

| Category                 | Criteria                                                               | Points |
|--------------------------|------------------------------------------------------------------------|--------|
| Data Story Definition    | Clarity, focus, and relevance of chosen story supported by the data    | 15     |
| Visualization Quality    | Effective use of chart types, encodings, and clarity                   | 20     |
| Interactivity            | Functional and purposeful interactive elements (filters, tooltips)     | 20     |
| Design and Storytelling  | Logical structure, layout, labeling, and visual hierarchy               | 20     |
| Technical Accuracy       | Accurate use of Tableau tools and correct data representation          | 15     |
| Reflection               | Depth of analysis, clarity of explanation, and thoughtful insights      | 10     |

---
 
## Additional Resources

- Tableau Public: https://public.tableau.com/  
- WPRDC Datasets: https://data.wprdc.org/group/public-safety  
- Tableau Visual Analytics Best Practices: https://help.tableau.com/current/guides/everyone_visual_analytics/en-us/eva_best_practices.htm  
- Observable Tutorials and Guides: https://observablehq.com/collection/@observablehq/observable-for-teams

---

## Notes

- Pay attention to design details: labels, axes, color usage, and interactivity should enhance clarity.
- Avoid excessive visual decoration (chartjunk).
- Ensure your dashboards and Observable notebook are accessible to a general audience.
- Your Observable notebook should serve as your central write-up and submission portal. Treat it like a live data report.

