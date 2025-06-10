# Profit-Calculator
A project to calculate project-wise profits based on employee allocation.

# Organisation Structure and Profit Requirements

## Organization Name 
** Triassic Solutions Private Limited **

###  Feature: Create Organization (Admin Only)

As an administrator, I should be able to create a new organization in the Profit Explorer system. This organization will serve as the root unit for departments and projects.

### Requirements

- **Organization Name**  
  - Type: Text  
  - Max Length: 15 characters  
  - Mandatory: Yes

- **Organization ID**  
  - Auto-generated (e.g., ORG01, ORG02...)  
  - Max Length: 5 characters

###  Access

- **Admin**: Can create a new organization  
- **All users**: Can view organization details

  ![admin](https://github.com/user-attachments/assets/bdbf0d21-5939-444a-a682-264a6d076b3c)


  ##  Department Management

###  Feature: Manage Departments (Admin Only)

From the `Config > Department` submenu, admins can view, create, edit, and delete departments within an organization.

###  Department List View

Each department entry will include:
- Department ID
- Department Name
- Description

###  Admin Capabilities

- **Add Department**: Opens a popup to input details
- **Edit Department**: Opens the same popup pre-filled
- **Delete Department**: Prompts confirmation before deletion

###  Add/Edit Department – Popup Fields

- **Department ID**: Auto-generated
- **Name**:  
  - Max Length: 15 characters  
  - Mandatory: Yes
- **Description**:  
  - Max Length: 255 characters  
  - Optional

###  Access

- **Admin**: Full CRUD (Create, Read, Update, Delete)  
- **All users**: View only

  ![department](https://github.com/user-attachments/assets/635fa219-2096-4265-971b-6d3c811bf458)


  ##  Project Management – Profit Explorer

###  Feature: Manage Projects (Admin Only)

Admins can manage multiple projects under departments, assign associates (employees), and track cost, duration, and revenue for accurate profitability analysis.

###  Project List View

Each project listed under a department will display:
- Project ID
- Project Name
- Department Name
- Description
- Start Date
- End Date
- Total Associates
- Status (e.g., Active, Completed)

###  Admin Capabilities

- Add Project  
- Edit Project  
- Delete Project  
- Assign Associates to Project  
- Update Associate Allocation and Cost  
- Remove Associate from Project

![proj](https://github.com/user-attachments/assets/a5aab76b-bd4b-41e0-8109-ad99418b40e4)


### Add/Edit Project – Popup/Form Fields

##  Associate (Employee) Assignment to Project

Associates can be allocated to projects with specific allocation percentages, working duration, and hourly cost.

![project](https://github.com/user-attachments/assets/da2920a7-9686-4764-8738-bd80c5580e79)









  









  



