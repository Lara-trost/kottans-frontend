# kottans-frontend

## Git та GitHub

### Version Control with Git (Udacity)
 
![Version Control with Git](./git-one.png)

  ##### назвіть (хоча б одну) річ яка була для вас новою
  З Git не працювала раніше.

- ##### назвіть (хоча б одну) річ яка вас здивувала
Кожен крок документується! 

- ##### назвіть (хоча б одну) річ яку ви збираєтесь використовувати у майбутньому
Some Git commands are:
 * git init * *створити новий репозиторій* *
 * git clone <path-to-repository-to-clone> * *клонувати репозиторій* *
 * git status * *визначити статус репозиторію* *
 * git log * *відобразити коміти сховища* *
 * git log --one line * *однією лінією* *
 * git log --stat * *перегляд змінених файлів* *
 * git log -p * *перегляд змін у файлі* *
 * git log -p --stat * *скільки файлів було змінено і кількість змінених рядків* *
 * git log -p -w * *ігнорувати пробіли* * 
 * git add <file1> <file2> ... <fileN> * *переміщення файлів із робочого каталогу до проміжного індексу* *
 * gid add . * *додати все* *
 * git show  * *показати комміт* *
 * git commit -m "My commit" * *додати комміт до репо* *
 * git diff * *перегляд внесених але ще не зафіксованих змін* *
 * git tag -a <tagName> -m "my version 1.4" * *додати таг до комміту* *
 * git tag -d <tagName> * *видалити таг* *
 * git branch * *список гілок у сховищі* *
 * git branch <branchName> <SHA> * *створити гілку* *
 * git branch -d <branchName> * *видалити гілку* *
 * git checkout <branchName> * *перейти на гілку* *
 * git log --oneline --decorate * *відображення гілок* *
 * git checkout -b footer master * *створити нову гілку та переключитися на неї* *
 * git log --oneline --decorate --graph --all * *переглянути всі гілки одразу* *
 * git reset --hard HEAD^ * *скасувати злиття* *
 * git merge <name-of-branch-to-merge-in> * *злиття гілок* *
 * git commit --amend * *зміна останнього комітту* *
 * git revert <SHA-of-commit-to-revert> * *повернення комміту* *
 * git reflog * *отримати доступ до стертого вмісту* *
 * git reset <reference-to-commit> * *скидання (стертя) комміту* *
 * git reset --mixed * *візьме зміни, внесені в комміт і перемістить їх до робочого каталогу* *
 * git reset --soft * *візьме зміни, внесені в комміт і перемістить їх до індекcу проміжку* *
 * git reset --hard * *візьме зміни, внесені в комміт і зітре їх* *
  .gitignore
  fileName



## Linux CLI, and HTTP
 
### Linux Survival
![Linux](./task_linux_cli/linux.png)
![Quiz 1](./task_linux_cli/linux-one.png)
![Quiz 2](./task_linux_cli/linux-two.png)
![Quiz 3](./task_linux_cli/linux-three.png)
![Quiz 4](./task_linux_cli/linux-four.png)
 
##### назвіть (хоча б одну) річ яка була для вас новою
  Linux
- ##### назвіть (хоча б одну) річ яка вас здивувала
Команди Linux і Windows схожі
 
- ##### назвіть (хоча б одну) річ яку ви збираєтесь використовувати у майбутньому
 
cd, pwd, rm, rmdir, find, finger ...
 
### HTTP: Протокол, який повинен розуміти кожний веб-розробник
 
##### назвіть (хоча б одну) річ яка була для вас новою
 
Порт за налаштуванням для HTTP – 80.
Методи:
 - GET: для запиту ресурсу.
 - POST: для створення нового ресурсу.
 - PUT: для оновлення існуючого ресурсу.
 - DELETE: для видалення існуючого ресурсу.
 - HEAD: подібний до GET, проте не передається тіло повідомлення.
 - TRACE: використовується для отримання від сервера інформації про "стрибки", через які пройшов запит. Його можна використовувати для діагностики.
 - OPTIONS: для отримання підтримуваних сервером можливостей. На стороні клієнта його можна використовувати для зміни запиту в залежності від можливостей, підтримуваних сервером.
 
 Інструменти для перегляду мережного трафіку за HTTP:
 - інспектор Chrome/Webkit
 - проксі для налагодження веб-застосунків, наприклад, Fiddler
 - Charles Proxy (для OSX)
 - програми з інтерфейсом командного рядка  curl, tcpdump та tshark.
На стороні клієнта застосування, що використовує HTTP, розпізнається за допомогою набору <IP, port>.
Встановлення з'єднання між двома кінцевими вузлами локальної мережі (ЛМ) – процес, що складається з декількох етапів:
 - встановлення відповідності імені хоста IP-адресі за допомогою DNS
 - встановлення з’єднання з сервером
 - відправлення запиту
 - очікування відповіді
 - закриття з'єднання
 Постійні з'єднання – довготривалі з'єднання, що залишаються відкритими, доки клієнт їх не закриє. Паралельні з'єднання – створюється набір із декількох з'єднань (звичайно максимум – шість з'єднань).
 ##### назвіть (хоча б одну) річ яка вас здивувала
Дуже багато теоретичної інформації, яку складно зрозуміти без практики.
 
- ##### назвіть (хоча б одну) річ яку ви збираєтесь використовувати у майбутньому
Методи: GET, POST, PUT, DELETE, HEAD ...

## Git Collaboration

###  Introduction to Git and GitHub

![github week three](./task_git_collaboration/github-one.png)
![github week three(2)](./task_git_collaboration/github-two.png)
![github week four](./task_git_collaboration/github-three.png)
![github week four(2)](./task_git_collaboration/github-four.png)

##### назвіть (хоча б одну) річ яка була для вас новою

git-remote - * *керування набором відстежуваних репозиторіїв* *
![Lists remote repos](https://git-scm.com/docs/git-remote)
git-fetch — * *завантажує об’єкти та посилання з іншого репозиторію* *
![git fetch](https://git-scm.com/docs/git-fetch)
git-branch - * *список, створення або видалення гілок* *
![git branch](https://git-scm.com/docs/git-branch#Documentation/git-branch.txt--r)
![merge conflicts](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-merge-conflicts)
![Resolving a merge conflict using the command line](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)
![git rebase branchname](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)

 Форкінг - це спосіб створення копії даного репозиторію. При спільній роботі над проектами, розміщеними на GitHub, типові робочі процеси спочатку створюють вилку репо, а потім працюють над цією локальною вилкою. Таким чином, ми можемо зрештою об'єднати наші зміни назад в основне репо, створивши запит на витягування. Pull Request - це комміт чи серія коммітів, які ви надсилаєте власнику репозиторію, щоб він включив його у своє дерево.
 ![pull request](https://docs.github.com/en/pull-requests) 
 ![About pull request merges](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/about-pull-request-merges) 
![Style Guides](https://google.github.io/styleguide/)
![About pull request reviews](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews) 
![The Perfect Code Review Process](https://medium.com/osedea/the-perfect-code-review-process-845e6ba5c31)
![What is Code Review?](https://smartbear.com/learn/code-review/what-is-code-review/) 
![Linking a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) 
![Setting guidelines for repository contributors](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) 
![What is CI/CD?](https://stackify.com/what-is-cicd-whats-important-and-how-to-get-it-right/)
![Travis CI Tutorial](https://docs.travis-ci.com/user/tutorial/) 

##### назвіть (хоча б одну) річ яка вас здивувала
 
Ця інформація потрібна була на початковому етапі при створенні репозиторію в Github. Це б зекономило купу часу.

 ##### назвіть (хоча б одну) річ яку ви збираєтесь використовувати у майбутньому

 pull request, Code Review

 ### learngitbranching

![learngitbranching-one](./task_git_collaboration/git-two.png)

![learngitbranching-two](./task_git_collaboration/git-three.png)

- ##### назвіть (хоча б одну) річ яка була для вас новою
git fetch, git cherry-pick, git pull ...
- ##### назвіть (хоча б одну) річ яка вас здивувала
Сленг в IT - суміш англійської та української.
- ##### назвіть (хоча б одну) річ яку ви збираєтесь використовувати у майбутньому
Some basic Git commands are:
* git rebase * *в основному автоматизована cherry-pick. Він визначає серію комітів, а потім вибирає їх один за одним у тому самому порядку в іншому місці.* *
* git rebase -i * *змінити порядок комітів, пропустити якісь коміти, об'єднати коміти в один.* *
* git cherry-pick <Commit1> <Commit2> <...> * *команда використовується для того, щоб прийняти зміни, внесені в один комміт Git, і спробувати повторно ввести їх як новий коміт у гілці, на якій ви зараз перебуваєте.* *
* git describe <посилання> * *описати, де ти є відносно найближчого орієнтира.* * 
* git fetch * *зв’язується з віддаленим репозиторієм і отримує всю інформацію, яка знаходиться в цьому сховищі, якої немає у вашому поточному, і зберігає її у вашій локальній базі даних.* *
* git pull * *по суті, є комбінацією команд git fetch і git merge, де Git отримуватиме дані з віддаленого пристрою, який ви вкажете, а потім негайно намагатиметься об’єднати його з гілкою, на якій ви перебуваєте.* *
* git pull --rebase * *Якщо поточна гілка та віддалена розійшлися, користувачеві потрібно вказати, як узгодити розбіжні гілки за допомогою --rebase або --no-rebase* *
* git push * *використовується для зв’язку з іншим репозиторієм, обчислення того, що ваша локальна база даних має, а віддалена — ні, а потім передає різницю в інше сховище. Для цього потрібен доступ для запису до іншого репозиторію, тому він зазвичай якимось чином автентифікується.* *
* git put * *Git отримає зміни із заданого віддаленого сховища. а потім відразу спробує злити їх до поточної гілки* *
* git remote add <name> <url> * *є інструментом керування вашим записом віддалених сховищ. Це дозволяє зберігати довгі URL-адреси як короткі дескриптори, наприклад «походження», щоб вам не потрібно було їх постійно вводити. Ви можете мати кілька таких, і git remoteкоманда використовується для їх додавання, зміни та видалення.* *


