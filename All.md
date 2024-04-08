## To create a virtual env:-
		python -m venv myenv
Then enter into the ‘myenv’/Other name of envirment created And new environment python
 or enter below code:-
myenv\Scripts\Activate
if getting error, enter this first:-
		Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

## To Close virtual env:-
		deactivate



## To push on github:-
1)	git init
if getting err:- winget install --id Git.Git -e --source winget
2)	git add .

3)	git commit -am "Done"

4)	git remote add origin <link> (e.g:- https://github.com/LetsDoIt298/Python.git)
If error:-  git remote set-url origin <link> e.g:- https://github.com/LetsDoIt298/Python.git)

5)	git push origin master


## Check the Origing url:-
		git remote -v

## To check the branches:-
		git branch -r

## To push in existing branch:-
		git checkout <BranchName> (e.g:- test_branch)
		git push origin <BranchName> (e.g:- test_branch)

## To create a new branch :-
		git checkout -b <BranchName> (e.g:- test_branch)
		git push origin <BranchName> (e.g:- test_branch)

## To Get the code from github to Local system:-
1) To get the code/all data in the current folder:-
			git clone -b <branck_name> <link> . (e.g:- git clone -b Version_1  https://github.com/LetsDoIt298/My-Site.git .)
   To get all code in a folder:-
			git clone -b <branch_name>  <link> <folder_name> (e.g:- git clone -b Version_1  https://github.com/LetsDoIt298/My-Site.git Test)




For ATS

python.exe -m pip install --upgrade pip
pip install -r requirements.txt
streamlit run "e:/Python/1) Application Tracking System(ATS)/app.py"

