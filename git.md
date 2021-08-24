```git status```    
Проверка статуса проекта git

```git add *file_name```  
```git add .```  
Добавление файла **file_name** в отслеживаемые (добавление в индекс), либо добавление в индекс всех файлов    

```git commit -m "Commit message"```  
Создание "слепка" всех отслеживаемых файлов проекта  
![Before commit](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/11_commit.png)
![After commit](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/12_commit.png)
![Before commit_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/13_commit.png)
![After commit_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/14_commit.png)  
1 - до коммита, 2 - после коммита, 3 - до коммита если есть новая ветка, 4 - после коммита если есть новая ветка  

```git branch```  
Создание новой ветки  
![Before new_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/21_branch.png)
![After new_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/22_branch.png)  

```git checkout New_branch_name```  
```git checkout Commit_hash```  
```git checkout Branch_name^```  
```git checkout HEAD^```  
```git checkout HEAD~3```  
Перенести HEAD на новую ветку. Можно также перенести на определенный коммит, на родительский коммит, на определённое количество коммитов назад  


```git checkout -b *New_branch_name*```  
Одновременное создание новой ветки и переключение на неё  

```git merge *Branch_name```  
Объединяет коммит указанной ветки с активной веткой  
![Before merge](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/31_merge.png)
![After merge](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/32_merge.png)  

```git rebase Branch_name```  
Копирует текущую ветку со всеми коммитами и присоединяет к последнему коммиту указанной ветки
![Before rebase](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/41_rebase.png)
![After rebase](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/42_rebase.png)  

```git branch -f main HEAD~3```  
```git branch -f main HEAD~3```  
Перенести ветку на несколько коммитов назад или к определённому коммиту  

```git reset HEAD~1```  
```git reset Commit_hash```  
Удаление коммита/коммитов и откат к предыдущему (для локального репозитория)  
![Before reset](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/51_reset.png)  
![After reset](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/52_reset.png)  


```git revert HEAD```  
```git revert Commit_hash```  
Удаление коммита/коммитов и откат к предыдущему (для удалённого репозитория)  
![Before reset](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/61_revert.png)  
![After reset](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/62_revert.png)  


**Полезные ссылки:**  
https://learngitbranching.js.org/ - тренажёр по Git на английском
