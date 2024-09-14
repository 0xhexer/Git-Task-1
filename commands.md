git clone https://github.com/0xhexer/Git-Task-1    


 cd Git-Task-1 


cat README.md 


git branch melvin  

vim melvin.txt


git add -f melvin.txt 


git commit -m "i added melvin.txt to main"


 git checkout melvin    

ls

vim melvin.md 

git add -f melvin.md 


git commit -m "i added melvin.md to melvin"

git log --oneline 

vim melvin.md 


git checkout main

vim README.md 

 git log     

git add README.md   


git commit -m "readme had my name" 

git reset --soft HEAD~1

git commit -m "readme dosent have my name " 


