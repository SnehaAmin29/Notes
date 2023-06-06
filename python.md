		
		Git - Version Control System
-------------------------------------------------

git --version


private- add collaborator- accept invitation

Add a README file
This is where you can write a long description for your project. Learn more about READMEs.

while using command git clone 
paste it using mouse like right click and paste
If you use ctrl + v, it won't work, bcz it hides an character in begining

adding modifications .............

--------------------------------------------------

$ git status    **
On branch main
Your branch is up to date with 'origin/main'.

--------------------------------------------------
// create a new file named python.md
 
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        python.md

nothing added to commit but untracked files present (use "git add" to track)

--------------------------------------------------
git add .        **//to add all the new files to git
                 //everytime you make modification you need to run this command.

--------------------------------------------------

$ git status         **
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   python.md

-----------------------------------------------------------------
If you are getting error for AUTHOR IDENTITY UNKNOWN 
When you are commiting, you need to 
set you user email and name else committ will not be done

git config --global user.email "snehaamin295@gmail.com"              **
git config --global user.name "SnehaAmin29"                          **

git commit -m "Mention here whatever message you want to give"       **


   local       Stage        Repo
   
-----------------------------------------------------------------

git push origin main       ** // main is nothing but main branch, origin is current directory
                                you are working include
								
---------------------------------------------------------------------------------

So  basically  steps you need to follow : 

1.  git clone  url
2.  git add .           
3.  git status 
4.  git commit -m "Mention here whatever message you want to give" 
5.  git push origin main      

--------------------------------------------------------------------------






