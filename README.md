"# BL_2115000992" 
Procedure for the Task:
    1  echo "Hello World"
    2  touch .gitignore
    3  echo "a.txt" >> .gitignore
    4  echo "Aloo kachalu" >> a.txt
    5  git add .gitignore
    6  git commit -m "Add .gitignore file/ second commit"
    7  git push -u origin main
    8  git checkout -b feature
    9  echo "Mahesh Babu" >>South.txt
   10  git add South.txt
   11  git commit -m "Commiting south.txt or first commit in feature branch"
   12  git push
   13  git push --set-upstream origin feature
   14  echo "RAJPAL YADAV" >> north.txt
   15  git commit -m "Commiting north.txt or second commit in feature branch but it is not copying data in main branch"
   16  git add north.txt
   17  git commit -m "Commiting north.txt or second commit in feature branch but it is not copying data in main branch"
   18  git push -u origin main
   19  git push

