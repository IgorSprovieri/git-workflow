# Git Workflow

This repository have a purpose to practice git workflow

## Steps to run the project

1. Clone this repository:

```
git clone https://github.com/IgorSprovieri/git-workflow.git
```

2. Open the project and change the file text.txt:

```
src/text.txt
```

## Initial Commit

1. Create your branch:

```
git branch main
```

2. Add all files:

```
git add .
```

2. Commit the changes:

```
git commit -m "initial commit"
```

3. Push the commit to the branch

```
git push -u origin main
```

## Create a development branch

### Explanation

You can create a development branch to develop your application and the final versions you commit to main branch

### Steps

1. Create your development branch:

```
git branch development
```

2. Switch to development branch:

```
git checkout development
```

3. Add all files:

```
git add .
```

4. Commit the changes:

```
git commit -m "initial commit"
```

5. Push the commit to the development branch

```
git push -u origin development
```

## Git ignore

### Explanation

Git ignore serves to hide sensitive or unnecessary files

### Steps

1. Create a example secret txt:

```
secret.txt
```

2. Open the .gitignore file:

```
/.gitignore
```

3. Add the files that you want to ignore:

```
secret.txt
```

## Add a final version on main

### Explanation

If you have a stable version of your application, you can clone the development branch to the main

### Steps

1. Change to main branch:

```
git checkout main
```

2. Clone the development branch:

```
git merge development
```

3. Push your main branch:

```
git push -u origin main
```
