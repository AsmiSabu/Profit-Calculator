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




### Add/Edit Project – Popup/Form Fields

##  Associate (Employee) Assignment to Project

Associates can be allocated to projects with specific allocation percentages, working duration, and hourly cost.

###Employees
