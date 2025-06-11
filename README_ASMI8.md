Profit-Calculator
A project to calculate project-wise profits based on employee allocation. MENU1 Menu2 MENU3

Organisation Structure and Profit Requirements
Organization Name
Triassic Solutions Private Limited

Feature: Create Organization (Admin Only)
As an administrator, I should be able to create a new organization in the Profit Explorer system. This organization will serve as the root unit for departments and projects.

Requirements
Organization Name

Type: Text
Max Length: 15 characters
Mandatory: Yes
Organization ID

Auto-generated (e.g., ORG01, ORG02...)
Max Length: 5 characters
Access
Admin: Can create a new organization

All users: Can view organization details

Department Management
Feature: Manage Departments (Admin Only)
From the Config > Department submenu, admins can view, create, edit, and delete departments within an organization.

Menu2

Department List View
Each department entry will include:

Department ID
Department Name
Description
Admin Capabilities
Add Department: Opens a popup to input details
Edit Department: Opens the same popup pre-filled
Delete Department: Prompts confirmation before deletion
Add/Edit Department – Popup Fields
department

Department ID: Auto-generated
Name:
Max Length: 15 characters
Mandatory: Yes
Description:
Max Length: 255 characters
Optional
Access
Admin: Full CRUD (Create, Read, Update, Delete)

All users: View only

Project Management – Profit Explorer
Feature: Manage Projects (Admin and Manager only)
Managers can manage multiple projects under departments, assign associates (employees), and track cost, duration, and revenue for accurate profitability analysis.

Select project = Project can be selected from main menu

Menu2

PROJECTLOGIN

Add project

Managers can add new projects
The deleting of project needs the approval of the admin project1
project2

Employee allocation
Editing,allocating employees,updating rate(per hour),resource allocation in a project can be done by manager

1

Employee allocation list includes following fields

Number of employees
Employee ID
Employee name
Resource
% allocation
Rate(per hour)
Start date
End date
Associate (Employee)
user

user/manager/admin can access the employee
The user can enter employee by using user id and password
user2

Employee list consist of the following fields

Employee ID(auto-generated)
Employee name(auto-generated)
Salary(per month)(auto-generated)
financial year

MENU3

Users can edit their salary details(like changing the monthly salary)
The increased salary will shown as the new salary per annum(auto-generated)
SALARY

Details of all the users(employees)
As an admin only i can view the full details of all the employees
Admin can edit and delete employee
MENU3

Details of all employees contains the following fields salary2

Employee ID
Employee Name
Experience(Previous project %allocation)
Cost of the employee
Total cost of the employees (auto generated)
Revenue made
Total revenue made(auto-generated)
Profit calculator
MENU1

As an admin only I can access the profit calculator
PROFIT

PROFIT CALCULATOR LIST CONSIST OF FOLLOWING FIELDS

Revenue(auto-generated)
Cost(auto-generated)
Profit(auto-generated)
Profit analysis consist of the following fields

Revenue of the organisation(auto-generated)
Total cost (auto generated from details of all the employees by considering cost of all employees)
Profit(auto-genrated)
