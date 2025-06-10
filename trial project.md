# Profit-Calculator
A project to calculate project-wise profits based on employee allocation.

# Organisation Structure and Profit Requirements

## Organization Name 
** Triassic Solutions Private Limited **

###  Feature: Create Organization (Admin Only)

As an administrator, I should be able to create a new organization in the Profit Explorer system. 

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

  ![mainmenu](https://github.com/user-attachments/assets/74fa2bcb-116a-4ba5-9c58-0acce06883e0)



 ##  Department Management

###  Feature: Manage Departments (Admin Only)

From the `Config > Department` submenu, admins can view, create, edit, and delete departments within an organization.

![deptmnt](https://github.com/user-attachments/assets/305e205a-5bfc-4653-a03f-75d5f6e61994)


![department](https://github.com/user-attachments/assets/54a48b4c-8c3c-4e45-bcf3-e0401d5e35ce)


###  Department List View

Each department entry will include:
- Department ID
- Department Name
- Description

  ![dept](https://github.com/user-attachments/assets/9eb61c32-b704-48fe-be24-6b027c2648d2)


###  Admin Details

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

- **Admin**: Functions (Create, Read, Update, Delete)  
- **All users**: View only


 ##  Project Management – Profit Explorer

###  Feature: Manage Projects (Admin Only)

Admins can manage multiple projects under departments, assign associates (employees), and track cost, duration, and revenue for accurate profitability analysis.

![config](https://github.com/user-attachments/assets/a18ccbff-e3ad-4136-b338-c5626cf957d3)


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

  ![project details](https://github.com/user-attachments/assets/bbcd2d7c-7187-41c8-a950-c0cce88e1f78)




###  Admin Tasks

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

###  Login Requirements

- **Login Form **
  - **User ID**
    - Type: Text
    - Mandatory: Yes
  - **Password**
    - Type: Password
    - Mandatory: Yes
  - **Login Button**
    - On click, authenticates user and retrieves employee information.
   
      ![employee](https://github.com/user-attachments/assets/fca72158-7d81-400f-952c-fb30046324ef)

   
      ![user](https://github.com/user-attachments/assets/a22e76f3-e6f3-4312-97d8-e6ff7726efc0)


- **Authentication Logic**
  - Validates credentials against stored user data.
  - On success, redirect to dashboard and display employee summary.
    
![profit](https://github.com/user-attachments/assets/3fc3b77d-4c4b-4a7c-9b92-37cfc1a52721)






