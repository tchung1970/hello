<html>
<pre>
<b>create a new repository on the command line</b>
echo "# hello" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:tchung1970/hello.git
git push -u origin main

<b>push an existing repository from the command line</b>
git remote add origin git@github.com:tchung1970/hello.git
git branch -M main
git push -u origin main
</pre>
</html>
