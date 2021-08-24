**git status**  
Проверка статуса проекта git

**git add *file_name***  
Добавление файла **file_name** в отслеживаемые (добавление в индекс)
Можно добавить все измененные/добавленные файлы
```
git add .
```  

**git commit -m **"Commit message"****  
Создание "слепка" всех отслеживаемых файлов проекта  
![Commit_before](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/11_commit.png)
![Commit_after](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/12_commit.png)
![Commit_before_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/13_commit.png)
![Commit_after_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/14_commit.png)  
1 - до коммита, 2 - после коммита, 3 - до коммита если есть новая ветка, 4 - после коммита если есть новая ветка  

**git branch**  
Создание новой ветки
![Commit_after_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/21_branch.png)  
![Commit_after_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/22_branch.png)  

**git checkout *New_branch_name***  
Переключение на новую ветку  

**git checkout -b *New_branch_name***  
Одновременное создание новой ветки и переключение на неё  

**git merge *Branch_name***  
Объединяет коммит указанной ветки с активной веткой  
![Commit_after_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/31_merge.png)  
![Commit_after_with_branch](https://github.com/jeksifrost/python_interview_Q-A/blob/main/images/git/32_merge.png)  




**Полезные ссылки:**  
https://learngitbranching.js.org/ - тренажёр по Git на английском
