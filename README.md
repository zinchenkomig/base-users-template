# QuickStart
First things first you need pipx
```bash
sudo apt install pipx
```
Now you can install copier. We use it to make this template work.
```
pipx install copier
```
Now you can initialize your project.
```
mkdir myproject
cd myproject
copier copy git@github.com:zinchenkomig/base-users-template.git .
```
It will ask you to fill data for the project templates.
Now your template is good to go.