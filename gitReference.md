#### Working with git cheatsheet

- Starting with new project
  - Using UI
    - Goto github/gitlab and create new repository
    - Copy URL
    - Clone to local using following command
      ```
      > git clone [-b <branch name>] <copied repo URL(https/ssh)>
      ```
      i.e.
      ```
      > git clone https://github.com/poojasharma401/blog-explorer.git
      ```
    - Go to your project directory
      ```
      cd <directory path>
      ```
  - Using git bash
    - Go to your project folder and
    - Init new project
      ```
      git init [-b <main>]
      > git add .
      > git commit -m <First commit>
      > git remote add origin  <REMOTE_URL> 
        i.e.
      > git remote add origin  "https://github.com/poojasharma401/learning-git.git"
      > git remote -v
      > git push origin main

      ```
- Adding files
  - Create your required files
  - Add them
    ```
    > git add .
    ```
  - Give a commit message
    ```
    > git commit -m <commit message, what changes you have made and why>
    ```
  - Take a pull
    ```
    git pull origin <branch name>
    ```
  - Finally push your code
    ```
    git push origin <branch name>
    ```
