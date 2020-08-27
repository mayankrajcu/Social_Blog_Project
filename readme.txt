Title:		A social blog project

Internal Title: Puppy Blog

Technologies:	Python 3.7.4
		Flask 1.0.2
		MySQL 
		packages used in requirements.txt

Launch:		Launch via app.py				
		

Contents of Project:-
	project organization:
		CORE--->
		USERS--->
		BLOG POSTS--->
	Project Views:
		CORE---> Index || Info
		USERS---> Register || Login || Logout || Account || User Posts
		BLOG POSTS---> Create || Update || Delete || Blog Post {CRUD Operations}
	Project Models:
		USERS--------> 	>Id
		  /\		>Profile Image
		  |		>Email
		  |		>Username
		  |		>password
		  |		>Posts
		  |
		BLOG POSTS--->	>Id
				>User_Id
				>Date
				>Title
				>Text