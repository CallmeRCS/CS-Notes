# 🔐 Access Control Models

1. **Least Privilege**
    - Principle where users, processes, or systems are given **only the minimum access** necessary to perform their tasks.
    - Reduces attack surface and limits potential damage.

2. **RBAC (Role-Based Access Control)**
    - Access is assigned **based on roles** within the organization.
    - Example: All “HR staff” get read/write access to employee records, while “Finance staff” do not.

3. **ABAC (Attribute-Based Access Control)**
    - Access decisions are based on **attributes** (user, resource, environment).
    - Example: A policy could allow access only if the user’s department = "Finance" **AND** time = "Business Hours".

4. **DAC (Discretionary Access Control)**
    - The **owner of the resource** decides who has access.
    - Example: A file owner can share or revoke access at will.
    - Weakness: Users may share with unauthorized individuals.

5. **MAC (Mandatory Access Control)**
    - Access is controlled by **central authority** based on security classifications / TAGs (e.g., Top Secret, Confidential). 
    - Users cannot change permissions.
    - Common in government and military environments.