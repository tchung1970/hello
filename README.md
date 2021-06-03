# header 1
## header 2
### header 3
#### header 4

### create a new repository on the command line
	$ echo "# hello" >> README.md
	$ git init
	$ git add README.md
	$ git commit -m "first commit"
	$ git branch -M main
	$ git remote add origin git@github.com:tchung1970/hello.git
	$ git push -u origin main

### push an existing repository from the command line
	$ git remote add origin git@github.com:tchung1970/hello.git
	$ git branch -M main
	$ git push -u origin main

### simple version
	$ vi README.md            
	$ git add .
	$ git commit -m .
	$ git push

### one line version
	$ git add .; git commit -m .; git push

### test
	$ git add .; git commit -q; git push
