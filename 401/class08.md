# Class 08--Access Control (ACL)

## [5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

- What is Role Based Access Control (RBAC) and why do we care? 

  - It is the idea assigning access to users based on their role.  It is easier to audit, implement and secure.  

- Describe a Role/Permission hierarchy that you might implement using RBAC. 

  - Roles for database 

  - User role—read only  

  - Writer role—read and create 

  - Editor role—read, create, and update 

  - Admin role—read, create, update, and delete 

  - What approach might you take to implement RBAC? 

  - Inventory your systems 

  - Analyze your workforce and create roles 

  - Assign people to roles 

  - Never make one-off changes 

  - Audit

## [Wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

- If Authentication is “you are who you say you are,” what is Authorization? 

  - It is what you are allowed to do based on your role 

- Name three primary rules defined for RBAC. 

  - Role assignment – you can use permissions only if you have a role

- Role authorization – you must be authorized to have your role 

  - Permission authorization – you can use permissions only if the permission is authorized for you active role 

- Describe RBAC to a non-technical friend. 

  - RBAC is like the military hierarchy. Each rank would be a role with certain permission or authority and like roles high ranks (more permissions) can do more than lower ranks (lower permissions) 

## [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

- What Are access rights Associated with? The User? or The Role? Explain. 

  - The access rights are associated with the role and the role is assigned to the user.  

  - `{ User } => { Role } => { Rights }` 

- Access Rights, or Authorization, is activated after a user successfully does what? 

  - Authenticate themselves to the system  

- Explain how RBAC might benefit a business. 

  - Policy need not be updated when a person leaves a role 

  - New employee should be able to active the desired role 

  - Switch roles to gain access to other resources 

## Things I want to know more about

+ How to implement RBAC in a database.
+ Can you use RBAC in a database.

© Marco Villafana 401d51