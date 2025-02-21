# Add-and-Manage-user
<h2>Introduction</h2>

In this lab, you’ll learn how to add users and manage user access in a system. These skills can be used when working with authentication technology. You’ll use Linux commands in the Bash shell to complete this lab.

<h2>What you’ll do</h2>

You have multiple tasks in this lab:
- Add a new employee
- Change ownership of a file
- Add the new employee to a new group
- Delete the employee from the system

<h1>Task 1. Add a new user</h1>
A new employee has joined the Research department. In this task, you must add them to the system. The username assigned to them is researcher9.

1.Write a command to add a user called researcher9 to the system.

Next, you need to add the new user to the research_team group.

2.Use the usermod command and -g option to add researcher9 to the research_team group as their primary group.

![image](https://github.com/user-attachments/assets/3418553f-cf64-47e7-879b-79df91d06ed3)

Task 2. Assign file ownership
The new employee, researcher9, will take responsibility for project_r. In this task, you must make them the owner of the project_r.txt file.

The project_r.txt file is located in the /home/researcher2/projects directory, and owned by the researcher2 user.

Use the chown command to make researcher9 the owner of /home/researcher2/projects/project

![image](https://github.com/user-attachments/assets/64cee0d8-8001-4b02-ac18-46d8e740113e)


<h1>Task 3. Add the user to a secondary group</h1>
A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.

In this task, you must add researcher9 to a secondary group (sales_team). Their primary group is still research_team.

Use the usermod command with the -a and -G options to add researcher9 to the sales_team group as a secondary group.

![image](https://github.com/user-attachments/assets/6675dde4-c080-43d4-a968-4adb54062bbc)

<h1>Task 4. Delete a user</h1>
A year later, researcher9, decided to leave the company. In this task, you must remove them from the system.

1.Run a command to delete researcher9 from the system:

2.Run the following command to delete the researcher9 group that is no longer required:

![image](https://github.com/user-attachments/assets/014abe54-9948-4971-856a-1bc070b72ae5)
