Learning .gitignore
!!! 

Для исключения папки .code из всех проектов для локального пользователя
необходимо выполнить команду
git config --global core.excludesFile .code/
После выполнения этой команды  в файле .gitconfig находящийся как правило в 
домашнем каталоге пользователя выставляется переменная core.excludesFile
 cat .gitconfig 
[core]
	editor = vim
	excludesFile = /.code/
