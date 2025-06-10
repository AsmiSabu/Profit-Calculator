# Profit-Calculator
A project to calculate project-wise profits based on employee allocation.
![MENU1](https://github.com/user-attachments/assets/cfcc2c12-20b5-4571-8b72-4fbaf0fad882)
![Menu2](https://github.com/user-attachments/assets/fae0a1d4-5be6-4bc8-9eaa-92a5409034fd)
![MENU3](https://github.com/user-attachments/assets/88653310-d540-4924-a26a-3219de5ed751)



# Organisation Structure and Profit Requirements

## Organization Name 
**Triassic Solutions Private Limited**

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

![Menu2](https://github.com/user-attachments/assets/5becb4be-5eb7-4a11-954f-fd2b392a4387)


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
![department](https://github.com/user-attachments/assets/41d013e4-9f3b-4602-bbc0-bdfe8c54f32a)

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

###  Feature: Manage Projects (Admin and Manager only)

 Managers can manage multiple projects under departments, assign associates (employees), and track cost, duration, and revenue for accurate profitability analysis.

**Select project**
= Project can be selected from main menu


![Menu2](https://github.com/user-attachments/assets/89c24f45-4966-4f59-8d67-424cc0fd1c45)

![PROJECTLOGIN](https://github.com/user-attachments/assets/faa89cb5-0e74-470e-8b30-cd24d6e5c704)


**Add project**
- Managers can add new projects
- **The deleting of project needs the approval of the admin**
![project1](https://github.com/user-attachments/assets/74ff8a7c-ada7-4151-938c-45f7a1ff1f00)

![project2](https://github.com/user-attachments/assets/ca4962e2-78f5-49e8-8554-3a5ab02b782c)

### Employee allocation 
**Editing,allocating employees,updating rate(per hour),resource allocation in a project can be done by  manager**


![1](https://github.com/user-attachments/assets/a3058f9c-0ddf-427a-8280-66b93de224a9)

**Employee allocation list includes following fields**

- Number of employees
- Employee ID
- Employee name
- Resource
- % allocation
- Rate(per hour)
- Start date
- End date

##  Associate (Employee) 
![user](https://github.com/user-attachments/assets/c97a5960-84ae-4078-9829-894addf719cb)

- user/manager/admin can access the employee
- The user can enter employee by using user id and password

  
![user2](https://github.com/user-attachments/assets/f9555be5-5461-4d3b-80de-8d43953c03c6)


**Employee list consist of the following fields**
 - Employee ID(auto-generated)
 - Employee name(auto-generated)
 - Salary(per month)(auto-generated)




**financial year**

![MENU3](https://github.com/user-attachments/assets/23306459-ab69-4ff7-b334-3e78c13113d7)


- Users can edit their salary details(like changing the monthly salary)
- The increased salary will shown as the new salary per annum(auto-generated)

![SALARY](https://github.com/user-attachments/assets/9e0e05c5-09d1-4ee4-968d-f5ed278a6562)


## Details of all the users(employees)

![MENU3](https://github.com/user-attachments/assets/635918fa-1b63-48a4-9204-012e8d69b6ba)

- As an admin only i can view the full details of all the employees
- Admin can edit and delete employee


**Details of all employees contains the following fields**
![salary2](https://github.com/user-attachments/assets/202daa6c-98cf-464a-8860-6b1dc629aea3)

- Employee ID
- Employee Name
- Experience(Previous project %allocation)
- Cost of the employee
- Total cost of the employees (auto generated)
- Revenue made
- Total revenue made(auto-generated)
  
## Profit calculator
![MENU1](https://github.com/user-attachments/assets/1dba6760-d636-4c8a-a44c-469205a66a27)

- As an admin only I can access the profit calculator
  
![PROFIT](https://github.com/user-attachments/assets/2967a3d8-cfbf-473c-9c4e-5bbde73a62c4)

**PROFIT CALCULATOR LIST CONSIST OF FOLLOWING FIELDS**
- Revenue(auto-generated)
- Cost(auto-generated)
- Profit(auto-generated)


**Profit analysis consist of the following fields**
- Revenue of the organisation
- Total cost (auto generated from details of all the employees by considering cost of all employees)
- Profit
