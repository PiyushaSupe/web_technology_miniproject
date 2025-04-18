# web_technology_miniproject
Inventory Management System 

Flow of the Project


The project follows a logical and modular flow from landing to role-based operations. Below is a simplified summary of the system's workflow:
•	Landing Page: Acts as the entry point of the application, offering navigation to login and signup pages.
•	User Registration:
o	New users access the Signup Page.
o	During signup, users choose their role: Admin, Employee, or Worker.
o	Workers and employees are registered with pending approval.
o	Admin accounts are added directly or via admin backend.
•	Admin Dashboard:
o	Admins can approve or disapprove pending users.
o	They can add, update, or delete users from the system.
o	Once approved, users can log in and access their respective panels.
•	Role-Based Panels:
o	Admin Panel: Manages user permissions and oversees system activity.
o	Employee Panel:
	Can add inventory items into the system.
	Can assign tasks to workers.
o	Worker Panel:
	Can view assigned tasks.
	Can mark tasks as completed, updating the system in real time.
•	Database Design:
o	users table: Stores all registered users and their roles/status.
o	inventory table: Stores inventory items and their details.
o	tasks table: Tracks task details, assignments, and completion statuses.
This structured flow ensures that every function is processed through proper authentication and data validation, ensuring integrity and role-based access control throughout the system.




![image](https://github.com/user-attachments/assets/f11d686e-d939-47cb-9cbd-e2ac7c27c5c6)
