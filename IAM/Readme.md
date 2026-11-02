IAM- AWS identity and access management: Helps root user to manage who can access what of the resources.(authentication and authorization) 
IAM components:-
Users : IAM users are the users that are given limited access to certain resources. There access is limited by root user, and need root users permission to access the resources they are not allowed to view.  
Policies : The set of rule of instructions that limits the users access.
Groups : We can make groups in which we have pre set permissions or policies, we can put the IAM users in the groups accordingly so we don't have to do policy setting for each.
Roles : Temporarily assumed identity by the user.
Practical
Making an IAM user with compulsory password change:
<img width="1758" height="895" alt="image" src="https://github.com/user-attachments/assets/c8efca26-01f3-453c-ba9e-9cd1a5ee21d6" />

Adding user to the group developers:
<img width="1759" height="894" alt="image" src="https://github.com/user-attachments/assets/392f6c70-4f10-439b-971c-63a1910bae14" />

Logs in as IAM user to find access denied to multiple services:
<img width="1774" height="886" alt="image" src="https://github.com/user-attachments/assets/9ca9abca-f2f0-41ae-bceb-51c12c504939" />

