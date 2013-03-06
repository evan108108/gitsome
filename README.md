GitSome
=======

An Experimental Git Dating Site: Alpha

##How to create a profile
* Step 1: Clone the repo 

```
% git clone git@github.com:evan108108/gitsome.git
```
* Step 2: Create a new branch from the profile branch with your profile name

```
% git checkout Your_Git_Username -b profile
```
* Step 3: Create your profile by editing the file profile.md 
* Step 4: Change the name of profile.md to 'Your_Git_Username.md'
* Step 5: Commit and push your profile edits to your branch 

```
% git rm profile.md
% git add Your_Git_Username.md
% git commit -m "Updated profile"
% git push origin Your_Git_Username
```

##How to find a mate
* Step 1: Browse the branches and look for a profile that interests you.
* Step 2: Checkout the branch of the user profile you want to date.

```
% git checkout Some_Username
```
* Step 4: Copy your 'Your_Git_Username.md' to the matches DIR
* Step 5: Commit and push

```
% git add matches/Your_Git_Username.md
% git commit -m "Added new match"
% git push origin This_Branch_Name
```

##Create a date
* Step 1: In your branches `dates` folder create a file with the name of the user you wish to date 
* Step 2: Commit and push to your branch
* Step 3: Submit a pull request to the user you wish to date.

##Accept a date
* Step 1: Simply merge any pull requests on your branch to except
