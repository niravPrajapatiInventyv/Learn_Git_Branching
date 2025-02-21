#  Git Remote Branch Tasks

## Level 2

### Task 1
```bash
1 git fetch
2 git rebase o/main side1
3 git rebase side1 side2
4 git rebase side2 side3
5 git rebase side3 main
6 git push 
```
![](/Remote_Task/Level2_task1.png)

### Task 2
```bash
1 git rebase  o/main side1
2 git rebase side1  side2
3 git rebase side2 side3
4 git rebase side3 main
5 git push
```
![](/Remote_Task/Level2_task2.png)

### Task 3
```bash
1 git checkout -b side o/main
2 git commit
3 git pull --rebase
4 git push
```
![](/Remote_Task/Level2_task3.png)

### Task 4
```bash
1 git push origin main
2 git push orgin foo
```
![](/Remote_Task/Level2_task4.png)


### Task 5
```bash
1 git push origin foo:mian
2 push origin main^:foo
```
![](/Remote_Task/Level2_task5.png)

### Task 6

```bash
1 git fetch origin C3:foo
2 git fetch origin C6:main
3 git checkout foo
4 git merge main 
```
![](/Remote_Task/Level2_task7.png)

### Task 7
```bash
1 git push origin :foo
2 git fetch origin :bar
```
![](/Remote_Task/Level2_task7.png)


### Task 8
```bash
1 git pull origin C3:foo
2 git pull origin C2:side
```
![](/Remote_Task/Level2_task8.png)

