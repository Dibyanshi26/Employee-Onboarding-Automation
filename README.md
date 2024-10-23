# Employee Onboarding Process Automation and Dashboard

## Project Overview
This project focuses on **automating the employee onboarding process** using Power Automate, while creating a Power BI dashboard for data analysis and tracking. The goal is to streamline the onboarding process by automating responses, gathering feedback, and visualizing key metrics related to employee onboarding activities. This solution helps HR departments track the onboarding status, monitor key metrics, and make data-driven decisions to improve the process.

## Technology Stack
- **Power Automate**: Automates the onboarding process, including task assignments, approvals, and email notifications.
- **Power BI**: For data visualization and reporting, creating interactive dashboards to monitor employee onboarding progress.
- **Microsoft Forms**: Used to collect responses from employees.
- **SharePoint**: Utilized for storing employee data and responses.

---

## Features

### 1. Employee Onboarding Process Automation
- **Automated Task Creation**: When a new employee response is submitted, the workflow **automatically creates a new task** in SharePoint and assigns it to the responsible team.
- **Conditional Approval Workflow**: The process includes **conditional approval**, where responses are reviewed and email notifications are sent based on the approval conditions.
- **Email Notifications**: Automated emails are sent to the concerned parties, ensuring the onboarding steps are followed without manual intervention.

#### Key Automation Steps:
1. **Trigger**: When a new response is submitted, the workflow fetches the response details.
2. **Create Task**: The workflow creates a new item in SharePoint for tracking.
3. **Approval Request**: An approval request is generated and sent to the HR manager.
4. **Email Notifications**: Based on the approval, emails are sent to the employee with further instructions.

---

### 2. Employee Onboarding Dashboard (Power BI)
- **Interactive Visualizations**: The dashboard provides a quick overview of employee onboarding status, including:
  - Number of employees who have set up their laptops.
  - Whether 1:1 meetings have been held with team members.
  - Completion of scheduled trainings.
  - Distribution of job titles and other key metrics.
  
- **Real-time Data Updates**: The dashboard pulls data from SharePoint, ensuring real-time updates of onboarding metrics.
- **Custom Filters**: Users can filter the data based on employee responses, departments, or other relevant fields.

---

## Screenshots

1. **Power Automate Flow**  
   ![Power Automate Flow](https://github.com/your-repo-link/power-automate-flow.png)

2. **Power BI Dashboard**  
   ![Power BI Dashboard](https://github.com/your-repo-link/power-bi-dashboard.png)


---

## Installation and Setup

### Prerequisites
- Microsoft Power Automate and Power BI licenses.
- Access to SharePoint for data storage and task management.

---

### Steps to Set Up

#### **Power Automate Workflow:**
1. **Open Power Automate** and create a new flow starting with a trigger when a new response is submitted (from Microsoft Forms).
2. **Add actions** to create items in SharePoint, start approval processes, and send emails based on conditions.
3. **Save the workflow** and test it by submitting sample responses.

#### **Power BI Dashboard:**
1. **Create a Power BI report** connected to SharePoint as the data source.
2. **Design the dashboard** with relevant visuals, such as bar charts, tables, and filters, to display onboarding progress.
3. **Publish the dashboard** to Power BI Service for real-time updates.

---

## Conclusion
This project automates the employee onboarding process, reduces manual intervention, and provides a **data-driven approach** to track the efficiency of onboarding activities. The Power BI dashboard enables the HR team to monitor onboarding tasks, track progress, and improve the overall employee experience through actionable insights.

---

## Future Improvements
- **Integration with Microsoft Teams** for better collaboration.
- **Post-onboarding employee surveys** to gather feedback after the onboarding process.
- **Predictive analytics** to monitor future onboarding metrics for proactive improvements.
