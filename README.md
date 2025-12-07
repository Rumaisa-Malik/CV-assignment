# CV-assignment


\* Important: Individual Assignment

Assignment No: 02

Software Construction and Development (Theory and Lab)

	Assignment Instructions

•	Individual Assignment  

•	Assignment with Proper well formatted front page with Name and Registration No:

•	Create a PDF document that includes all the processes and procedures you used.

•	Submit in soft format on GCR in PDF file.

•	Submit hard copy on (08-12-2025) 

•	After due date not accept \*

Q .1.	What is Git and github describe in detail? 

Q .2.	What is conflict in source code management and how to resolve it?

Objective - Each student will create their own HTML CV page in the CV-assignment project. - Add a link to your CV in the header menu. - Use Git branches for all work and push to GitHub.

1\.	Step 0: Install Git 

a.	Download Git for Windows: https://git-scm.com/downloads

b.	Install with default options.

c.	Open Git Bash.

d.	Check installation: git –version

2\.	Step 1: Configure Git Set your name and email:

a.	git config --global user.name "Your Name"

b.	git config --global user.email your.email@example.com

c.	Check settings: git config –list

3\.	Step 2: Clone the project 1. Open Git Bash. 2. Navigate to your desired folder:

a.	cd C:/Users/HP/Documents/NetBeansProjects/

b.	Clone the repository: git clone https://github.com/sharifdev1214/CV-assignment.git

c.	cd CV-assignment

d.	Check remote: git remote -v

4\.	Step 3: Check and switch branch

a.	git branch –a

b.	git checkout main

5\.	Step 4: Create your own branch

a.	git checkout -b <your\_name\_branch>

b.	Example: git checkout -b haider\_branch

c.	Confirm branch: git branch

6\.	Step 5: Create your CV

a.	In NetBeans, navigate to CV-assignment/src/main/webapp

b.	Right-click → New → Folder → Name it cv

c.	Copy mahad.jsp into cv and rename it to your name: cv/mahad.jsp → cv/.jsp

d.	Edit your-name.jsp with your personal info.

7\.	Step 6: Add your CV link to header

a.	Open header.jsp

b.	Find the dropdown menu for CVs.

c.	Copy the example link:

i.	<a class="dropdown-item" href="<%= root %>/cv/mahad.jsp">Mahad Hassan</a>

d.	Paste it below and change the file name and display name:

i.	<a class="dropdown-item" href="<%= root %>/cv/haider.jsp">Haider Ali</a>

8\.	Step 7: Test your CV - Run the project in NetBeans.

a.	Open your CV page via dropdown menu: http://localhost:8080/CV-assignment/cv/.jsp

b.	Verify everything shows correctly.

9\.	Step 8: Save your work in Git

a.	git add cv/<yourname>.jsp header.jsp

b.	git commit -m "Add my CV and navigation link"

10\.	Step 9: Push your branch to GitHub

a.	git push -u origin <your\_name\_branch>

b.	Example: git push -u origin haider\_branch

c.	For future updates:

i.	git add \*

ii.	git commit -m "Update CV"

iii.	git push

11\.	Step 10: Pull updates from main branch

a.	git pull origin main

b.	Resolve conflicts if any:

i.	git add .

ii.	git commit

12\.	Step 11: Submit - Your branch on GitHub now contains your CV and header link.

a.	Teacher can see it: https://github.com/sharifdev1214/CV-assignment/tree/

\* Important Tips.

	Always work in your own branch.

	Copy mahad.jsp

	do not edit the original.

	Keep CV layout consistent.

	Test your page in the browser before pushing.

	Commit and push frequently.

	Pull from main before pushing to avoid errors.

Best of Luck



