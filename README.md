# Symfony-Job-Management-System
A job management system using the symfony PHP framework

To generate database schema from models - use doctrine:schema:create

This was a project to show off my understanding of simple CRUD using symfony - this includes an authentication system, 
create job listings, read job listings as well as individual listings and delete listings. Update listings is on the
agenda and user security restrictions to restrict access to certain endpoints.

Here is the very basic, barebones landing page view - this was made using bootstrap and basic components.
![Screenshot from 2023-06-26 01-27-27](https://github.com/rypwhite/Symfony-Job-Management-System/assets/48073843/61d433b2-07cd-43e7-a476-18c1791a7ac6)

Here is the view of ALL active job listings on the site
![Screenshot from 2023-06-26 01-28-18](https://github.com/rypwhite/Symfony-Job-Management-System/assets/48073843/5e83df03-a551-4785-b8cf-bb30a673cdb0)

Here is the individual view foreach job (specifically selected from the database)
![Screenshot from 2023-06-26 01-28-53](https://github.com/rypwhite/Symfony-Job-Management-System/assets/48073843/bb3acc73-7fe3-4aeb-b504-0298f128e2ac)

Here is the create jobs view, which will interact with the database and insert a record using our "Job" model
![Screenshot from 2023-06-26 01-29-44](https://github.com/rypwhite/Symfony-Job-Management-System/assets/48073843/1e6ba727-467c-4649-9db5-7a7f06a2aeec)

Here is the manage jobs view, this table will output all the information we store about each job (more to come) as well as functions (both just delete the job, edit TODO)
![Screenshot from 2023-06-26 01-30-15](https://github.com/rypwhite/Symfony-Job-Management-System/assets/48073843/986bf340-0c90-49b8-b01a-7cd902c1bf22)
