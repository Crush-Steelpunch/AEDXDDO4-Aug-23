## Github Actions

- In Github, go to **Actions** and create a new **Simple workflow**
- edit the actions file to add more `run` statements
  - If you edit it in your local repo you may need to modify your PAT.
  - example run statements
    - `date`
    - `cat /etc/os-release`
    - |
      ```bash
      yum update
      yum install -y bsdmainutils
      cal
      ```
- save the yaml file with any name (default was `blank`)
- see the action running
- If it fails try to fix it (with help if needed)
