# Hello world 
## _in this tutorial_
* #### I will show you the basic commands of the git
* ##### a little trick with the markdown files, 
* ###### and how to write tutorials
######  so people who will look at your profile 
###### can be aware of what your repository is about

# RU

> [Конечно, вот некоторые основные команды для работы с **Git** через терминал:][git]

1. **`git init`** - Инициализирует репозиторий **Git** в текущей директории. Создание локального репозитория в папке вашего проекта.

2. **`git add <filename>`** - Добавляет изменения в указанный файл в индекс. Добавления файла из локального репозитория в файлы которые необходимо загрузить в удаленный репозиторий.

3. **`git add .`** - Добавляет все изменения в текущей директории в индекс.

4. **`git commit -m "<commit message>"`** - Создает коммит с указанным сообщением. После добавления файлов которые надо загрузить на удаленный репозиторий, их надо обозначить, для того чтобы их можно было загрузить на гитхаб.

5. **`git status`** - Показывает текущий статус репозитория. Этой командой проверяем какие файлы добавлены для загрузки на удаленный репозиторий, а какие файлы мы не добавляли( они не будут загружены).

6. **`git log`** - Показывает историю коммитов в репозитории.

7. **`git branch`** - Показывает список всех веток в репозитории.

8. **`git checkout <branch name>`** - Переключает ветку на указанную ветку.

9. **`git merge <branch name>`** - Сливает указанную ветку в текущую ветку.

10. **`git push <remote name> <branch name>`** - Отправляет изменения в указанную ветку на удаленный репозиторий. Загрузка всех файлов которые отмечены для загрузки в удаленный репозиторий, из локального репозитория.

11. **`git pull <remote name> <branch name>`** - Получает изменения из указанной ветки на удаленном репозитории. Для коммандной разработки, когда есть несколько разработчиков, для того чтобы можно было работать с кодом других разработчиков.

12. **`git clone <remote repository URL>`** - Клонирует удаленный репозиторий в текущую директорию. Скачивает указанный репозиторий в директорию в которой выполняеться команда ( если в терминале вы находитесь на рабочем столе, то удаленный репозиторий скачаеться к вам на рабочий стол) 
Для этого метода есть два способа работы с удаленными репозиториями, через htpps и ssh

> Надеюсь, это поможет вам начать работу с Git через терминал!


# EN 

> [Of course, here are some basic commands for working with Git via the terminal:][git]

1. **`git init`** - Initializes the Git repository in the current directory. Creates a local repository in your project folder.

2. **`git add <filename>`** - Adds changes to the specified file to the index. Adding a file from a local repository to files to be uploaded to a remote repository.

3. **`git add .`** - Adds all changes in the current directory to the index.

4. **`git commit -m "<commit message>"`** - Creates a commit with the specified message. After adding files to be uploaded to the remote repository, they need to be marked so they can be uploaded to the githab.

5. **`git status`** - Shows the current status of the repository. This command checks which files have been added for upload to the remote repository, and which files we have not added (they will not be uploaded).

6. **`git log`** - Shows the commit history of the repository.

7. **`git branch`** - Shows a list of all branches in the repository.

8. **`git checkout <branch name>`** - Switches the branch to the specified branch.

9. **`git merge <branch name>`** - Merges the specified branch into the current branch.

10. **`git push <remote name> <branch name>`** - Sends changes to the specified branch to a remote repository. Upload all files that are marked for upload to the remote repository from the local repository.

11. **`git pull <remote name> <branch name>`** - Retrieves changes from the specified branch on the remote repository. For team-based development when there are multiple developers, so that you can work with code from other developers.

12. **`git clone <remote repository URL>`** - Clones the remote repository into the current directory. This downloads the specified repository into the directory where you ran the command (if you are on the desktop in the terminal, the remote repository is downloaded to your desktop). 
There are two ways to use remote repositories for this method, via htpps and ssh

> I hope this helps you get started with Git via the terminal!


[git]:[https://git-scm.com/docs/git]
