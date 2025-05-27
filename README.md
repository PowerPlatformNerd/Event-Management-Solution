# 📅 Event Management App

## Overview  
The **Event Management App** is a **Power Platform** model-driven solution that helps users efficiently plan, manage, and track events. Built on **Microsoft Dataverse**, it provides event lifecycle tracking, attendee registration, and guided processes — all in a low-code environment using Power Apps.

## Features  
- 🗓️ **Event Lifecycle Management** – Create and manage events with details like name, date, location, capacity, and status.  
- 🙋 **Attendee Registration** – Link registrations to specific events and capture attendee information such as name, email, and registration date.  
- 🔄 **Business Process Flow** – Visual guidance through event stages: Planning → Open → Closed.  
- 🧩 **Custom Forms & Views** – Intuitive forms and views tailored for quick data entry and review.  
- 📈 **Extensibility** – Integrate with Power Automate, Power BI, or add custom columns and dashboards.

## Prerequisites  
- 🔹 **Power Platform environment** (Dataverse enabled).  
- 🔹 **Power Apps license** with table creation and app development permissions.  
- 🔹 *(Optional)* Power Automate for workflow automation.
  
## 🧩 App Components

| Component                 | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Event Table**           | Stores event-specific data: name, date, location, capacity, and status.     |
| **Registration Table**    | Captures attendee details linked to events through a lookup field.          |
| **Business Process Flow** | Guides users through event stages: Planning → Open → Closed.                |
| **Model-Driven App**      | Includes navigation, views, forms, and automation tailored for event ops.   |
| **Forms & Views**         | Custom views and forms for easy data entry and management.                  |

## Installation  

### 1️⃣ Download Unmanaged Solution  
```sh
EventManagementSolution_1_0_0_2.zip
```
### 🔄 Import the Solution into Power Platform  

1. Open [Power Apps](https://make.powerapps.com).  
2. Navigate to **Solutions** in the left-hand menu.  
3. Click **Import Solution**.  
4. Select the downloaded file:

    ```sh
    EventManagementSolution_1_0_0_2.zip
    ```

5. Click **Next** and follow the import prompts.  
6. Once completed, open the **Event Management App** from your solutions list.

![image](https://github.com/user-attachments/assets/fa70850d-f477-4061-bea7-b5c0f363c4e8)
