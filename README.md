# WEB-3350-Final-Project
Final Project in WEB 3350 


Idea:
Monthly Financial Planner


1. Executive Summary & Project Description 
Family Financial Planner
A shared family budget planner in income/expense tracker. Used by any number of family members to combine and compare income as well as budgeting needs and requirements. Allowing anyone signed in to edit or create new financial categories and limits. As well as document their income and personal expenses.


2. Feature Breakdown & UI Wireframes
Wire frame in figma : LINK 		password: web3350

Route 1 - Login/Sign up 
Route 2 - Home/Dashboard (list of incomes/expenses - balance out)
Route 3 - Input income/expense 
Route 4 - expense/income detail


3. Technical Architecture and Specifications 
State Management Plan
Each page handles individual states, with the dashboard passing filters down as props. Authentication tokens shared through an Auth page.
Backend& Async Operations
Firebase Realtime Database with locked mode and limited write ability through the website
Custom Hooks
useAuth: a wrapper around an AuthenticationContext for user, login, signup, logout, and isAuthenticated
useFirebase: a wrapper for fetching loading and error states. Automatically adding the base URL and the user’s authentication token
useBudgetData? : crud operations
Authentication
All write/edit will be password protected. And any income pages will be password protected as well
Testing Strategy
Do the links send users to the correct page
Do all numbers on income and expenses add together to the correct amount


4. Work Breakdown & Team Responsibilities

Task Management: trello

Lists for individual people added for ease of screenshot. More tasks and roles can be allocated later.

Git: Git branches will be created for specific tasks and overarching projects. After they are completed Byron will merge them into main and make sure they do not cause errors with other pushes.
Communication: Tasks will be marked off as they are completed in trello. Discord will be used for updates, and when help is required. Shared documents are linked in discord, with Figma, Google Docs, and Trello acting as supplementary communication branches.



When working on the project, please make a new branch for distinct things you are working on and push it to that branch.
When merging if there are no problems feel free to merge to main. If not and you can't get all of the conflicts worked out let me know in discord and I'll merge the branches. -Byron
