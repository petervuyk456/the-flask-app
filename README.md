## Startup Instructions

```bash
python -m venv .virtualenv
source .virtualenv/Scripts/activate
pip install -r requirements.txt
flask --app main --debug run
```

## Teardown Instructions
```Bash
deactivate
```

## Topics we touched on

Install all of this...
- `vscode` (or Visual Studio Code) - it's a code editor or an IDE, an integrated development environment (IT'S AWESOME)
- `git` - version control, saving changes, working with multiple
  - To use this package, go to Github, create an account
  - Add me on Github
  - I will add you to repo
  - Run this
    ```
    git clone <https code path>
    cd the-flask-app
    code .
    ```
- `python`:
  - `flask` - barely touched but we know it makes websites or something like that

Other topics
- `terminal` - use basic commands to make your life easier and stay in the IDE
- `markdown` - text formatting as you type
- `linux/windows` - different operating systems, windows can be fucking annoying sometimes to code so go to WSL (Windows Subsystem Linux) if you get desperate



NOTE: for lots of installations, you gotta make sure the new shit gets in your PATH
one line at a time:
    - Get your PATH
      - bash: `echo $PATH | tr ':' '\n'`
      - powershell: `$env:Path -split ';'`
    - Using your path, find what you installed. If you cannot find it, it's either not installed, you searched for the wrong thing, or you need to refresh your environment
      - refresh env: restart your IDE or terminal
      - searching: 
        - bash: `echo $PATH | tr ':' '\n' | grep python`
        - powershell: `$env:Path -split ';'` *not sure what the grep command is on powershell, look it up
