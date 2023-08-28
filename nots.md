1 #!/bin/bash
2 #for OSX use python
3 python -m http.server
4 #for Linux use python3
5 python3 -m http.server
6 cd /c/Users/ellen/OneDrive/Desktop/webkehityksenperusteet23~
7 cd /Users/ellen/OneDrive/Desktop/webkehityksenperusteet23
8 mkdir git-tests
9 cd git-tests/
10 ls
11 ls -l
12 git init
13 ls -la
14 git status
15 touch mallitiedosto
16 git add mallitiedosto
17 git status
18 git status
19 git status
20 git add .
21 git commit -m "initial commit"
22 git log
23 git remote -v
24 git remote add origin https://github.com/ellenjarvenpaa/git-tests.git
25 git remote -v
26 git push -u origin main
27 git push -u origin master
28 git branch dev
29 git branch
30 git checkout dev
31 git status'
32 git status'
33 git status
34 git touch toinen-tiedosto
35 touch toinen-tiedosto
36 git status
37 git add .
38 git commit -m "korjaus"
39 git status
40 git checkout main
41 git checkout master
42 git merge dev
43 git diff dev
44 git checkout -b dev-ville
45 git clone https://github.com/mattpe/git-intro.git
46 git remote add origin https://github.com/ellenjarvenpaa/githubexercises.git
47 git remote help
48 cd githubexercises
49 git remote --help
50 git remote -v
51 cd git-intro
52 git remote -v
53 git remote add origin https://github.com/ellenjarvenpaa/githubexercises.git
54 git remote set-url origin https://github.com/ellenjarvenpaa/githubexercises.git
55 git remote -v
56 git add .
57 git status
58 git commit -m "moi"
59 git push -u origin main
60 touch nots.md
61 history
62 git status
