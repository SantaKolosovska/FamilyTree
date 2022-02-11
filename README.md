# FamilyTree app

This was the final project for SGT Java part I . 
Our group consisted of three people - Laila Duffy, me and Marina Toporkova. 
Project's goal was to create an app where a user could input his/her family members and build a 
family tree. For now the app uses database file with fake family members. 
To achieve the goal we used graphs and database. Future improvements 
would include traversing the graph to establish different kinds of 
relationships and displaying the family tree visually.

These options are provided in the app menu:
1. The list of all people in the Family Tree.
2. Info about a person (write name).
3. The oldest person in the Family Tree.
4. The youngest person in the Family Tree.
5. Find out who have birthdays in chosen month.
6. Add a person to the Family Tree.
7. Add relationships between persons in the Family Tree.
8. Update a person in the Family Tree.
9. Remove a person from the Family Tree.

## How to use 
Run the project on your IDE and follow the instructions in console.

![family_tree_menu](https://user-images.githubusercontent.com/86738044/153578816-b3cbd676-fc2e-4b18-864a-feadae44d832.jpg)

Example using menu option to view info about a family member:
![family_tree_member_info](https://user-images.githubusercontent.com/86738044/153581151-dbdd3304-2e34-475a-b85f-f552ce4d61fd.jpg)

Example using menu option to find out which family members have birthday in given month:
![family_tree_month2](https://user-images.githubusercontent.com/86738044/153581150-d2be226e-6079-48b6-9023-c8166206d8a4.jpg)\

&nbsp;
## Database structure
We used two tables - one for persons and the other one for relationship between two persons.
![family_tree_db_structure](https://user-images.githubusercontent.com/86738044/153579962-70d90fc9-d433-42cd-9530-3ba1e1d21916.jpg)

Persons table: 

![family_tree_persons_table](https://user-images.githubusercontent.com/86738044/153579968-62cfacce-dedd-4d8f-b611-2c008b8f269e.jpg)

Relationships table: 

![family_tree_relationships_table](https://user-images.githubusercontent.com/86738044/153579967-4cdbc75c-478f-42dc-a581-e0004d3361a5.jpg)\

&nbsp; 
## Family tree that was used for our database 
In the end we also included relatives with same name, but they're not included in this version of the family tree
![alt text](https://github.com/SantaKolosovska/FamilyTree/blob/master/family_tree.jpg)

