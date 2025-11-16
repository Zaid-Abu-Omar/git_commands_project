#Udacity project : Git & GitHub setup 
This project demonstrates how to set up a GitHub repository, link it with a local project, improve documentation using Markdown, and understand the concept of refactoring.
1. **creating repository in GitHub 
- First I created a profile in GitHub
- Created a new repository and declared it as git_commands_project
- set the repository to be public
2. **creating the project locally**  
- Open the project at the local device
- prompoted the command 'git init' to start the repsoitory as a project
- adding the files to staging area using 'git add'
- making the first commit
```bash
git commit -m"adding the first editing version for the file"
```
3. **Linking the local reopsitory to GitHub**
- Added the remote repository:
```bash
git remote add origin <repository_url>
```
- Pushed changes to GitHub:
```bash
git push -u origin main
``` 
4. **Improving documentation with markdown**
   - Created a `README.md`file.
   - Used Markdown to format the text:
     - `#` for main headings
     - `##` for subheadings
     - `-` for bullet lists
     - `` ` `` for code snippets
## Section IV: Refactor Code (Example)

Since this project doesn't have real code yet, here's a small example to show the refactoring workflow:

### Original Code
```python
numbers = [1, 2, 3, 4, 5]

total = 0
for n in numbers:
    total += n

squares = []
for n in numbers:
    squares.append(n**2)

print("Total:", total)
print("Squares:", squares)
### Refactoring Code
numbers = [1, 2, 3, 4, 5]

total = sum(numbers)
squares = [n**2 for n in numbers] 
print("Total:", total)
print("Squares:", squares)
