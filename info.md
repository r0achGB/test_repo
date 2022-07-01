# Основные команды Git

*	git status – получить информацию от git о его текущем состоянии

*   git add – добавить файл или файлы к следующему коммиту

* ### Interaction with a remote repository. You can use

-   **git fetch** to download all the changes from the remote repository
-   **git clone remote_repository_URL** to download remote version of the necessery repository

> The git clone is a composite command: it not only
> downloads all the changes, but also tries to merge
> all the branches on the local computer and in
> the remote repository.

-   **git pull** to download all the changes from the remote repository and automatically merge with current local version
-   **git push** to upload current local version of the repository to remote repository
    > Authorization required on the remote repository
