IAM- AWS identity and access management: Helps root user to manage who can access what of the resources.(authentication and authorization) 
IAM components:-
Users : IAM users are the users that are given limited access to certain resources. There access is limited by root user, and need root users permission to access the resources they are not allowed to view.  
Policies : The set of rule of instructions that limits the users access.
Groups : We can make groups in which we have pre set permissions or policies, we can put the IAM users in the groups accordingly so we don't have to do policy setting for each.
Roles : Temporarily assumed identity by the user.
Practical
Making an IAM user with compulsory password change:
<img width="1910" height="972" alt="image" src="https://github.com/user-attachments/assets/8256f255-8451-497c-bf8e-ad3862ea2fab" />
Adding user to the group developers:
<img width="1902" height="965" alt="image" src="https://github.com/user-attachments/assets/a56a860a-38b3-4f84-9d49-37d9aa2d3996" />
Logs in as IAM user to find access denied to multiple services:
<img width="1917" height="957" alt="image" src="https://github.com/user-attachments/assets/f5d75473-561f-498b-aaaa-00f325023108" />
