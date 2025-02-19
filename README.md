# Learn_Git_Branching

# Level 1

## Task 1
```bash
1. git commit
```
![](/Level_1_task_1.png)
## Task 2
```bash
1. git checkout -b bugfix
```
![](/Level_1_task_2.png)

## TASK 3
```bash
1. git checkout -b bugFix
2. git commit
3. git checkout main
4. git commit
5. git merge bugfix
```
![](/Level_1_task_3.png)
## Task 4
```bash
1. git checkout -b bugfix
2. git commit
3. git checkout main
4. git commit
5. git chekout bugfix
6. git rebase main
```
![](/Level_1_task_4.png)

# Level 2

## Task 1
```bash
1. git checkout c4
```
![](/Level_2_task_1.png)
## Task 2
```bash
1. git checkout c4
2. git checkout c4^
```
![](/Level_2_task_2.png)
## Task 3
```bash
1. git checkout C2~1
2. git branch -f main C6
3. git branch -f bugFix C1~1
```
![](/Level_2_task_3.png)
## Task 4
```bash
1. git reset C3^
2. git checkout pushed
3. git revert C2
```
![](/Level_2_task_4.png)

# Level 3

## Task1
```bash
1. git cherry-pick C3 C4 C7
```
![](/Level_3_Task1.png)
## Task 2
```bash
2. git rebase -i C5~4
```
![](/Level_3_Task2.png)
# Level 4

## Task 1
```bash
1. git checkout main
2. git cherry-pick C4
```
![](/Level_4_Task1.png)
## Task 2
```bash
1. git rebase -i HEAD~2
2. git commit --amend
3. git rebase -i HEAD~2
4. git checkout main
5. git merge caption
```
![](/Level_4_Task2.png)
## Task 3
```bash
1. git checkout main
2. git cherry-pick C2
3. git commit --amend
4. git cherry-pick C3
```
![](/Level_4_Task3.png)
## Task 4
```bash
1. git checkout C5~1
2. git tag v0 C1
3. git tag v1 C2
```
![](/Level_4_Task4.png)
## Task 5
```bash
1. git commit
```

![](/Level_4_Task5.png)
# Level 5

## Task 1
```bash
1. git rebase main bugFix
2. git rebase bugFix side
3. git rebase side another
4. git rebase another main
```
![](/Level_5_Task1.png)
## Task 2
```bash
1. git branch bugFix C2
```
![](/Level_5_Task2.png)
## Task 3
```bash
1. git checkout one
2. git cherry-pick C4 C3 C2
3. git checkout two
4. git cherry-pick C5 C4 C3 C2
5. git branch -f three C2
```
![](/Level_5_Task3.png)




