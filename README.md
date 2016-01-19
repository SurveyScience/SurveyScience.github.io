# SurveyScience.github.io

##Instructions for adding a new post

This can be done from **entirely** within the github web interface!

1. Click on the `_posts` directory.
2. Locate the most recently dated post (date of post is given in the filename). Click on that file.
3. Click on `Raw` to view the actual file contents.
4. Copy the preamble (between the `---`'s) at the top of the page.
5. Click back twice to get back to the `_posts` directory.
6. Click on `+` sign or `New File` after `SurveyScience.github.io/_posts/` to create a new file.
7. Type filename in the box after `SurveyScience.github.io/_posts/`. The filename **must** have the format: <pre>YYYY-MM-DD-<i>optional-text</i>.markdown</pre> where the date must be the date of the Survey Science lunch the post is referring to.
8. Paste the copied preamble into the file and edit the title line to be the subject of the Survey Science lunch, and the date line to be the date of the Survey Science lunch.
9. Type details e.g. the talk title and abstract below the lower set of `---`. Formatting can be applied by writing in markdown (see below).
10. Underneath `Commit new file` at the bottom type a short description of the change, e.g. "adding post for Dec 13 lunch".
11. Commit file.
12. Refresh the [website](http://surveyscience.github.io/) to check the changes. Note it may take a few mintues for the changes to become live.



##How to write markdown

See this [page](https://help.github.com/articles/markdown-basics/).

Note one thing, the \# behaves differently: for each \# you add at the beginning of a block of consecutive text makes the text one font size larger than the default.

##How to add people's slides

This must be done within your own local copy of the repo, then the changes must be pushed to the repo hosted on github.

1. Clone the repo (if you haven't already) by typing `git clone https://github.com/SurveyScience/SurveyScience.github.io.git` in a terminal
2. Copy the slides (pdf format preferred) into the `slides` directory
3. Navigate to the root directory of your local copy of the repo and type `git add [slides_filename.pdf]`
4. Now type `git commit -a -m "Adding [someone's] slides"`
5. Push the changes back to the remote repository: `git push origin master`. You will be asked for your github username and password. Note you may have to do a `git pull` first if your local copy of the repository isn't up to date.
6. Add a link to these slides within the corresponding post in the `_posts` directory. In the `.markdown` file the link should probably look like this: `[link text](../../../../../../slides/slides.pdf]`
7. Verify the link to the slides by checking them at the webpage `http://surveyscience.github.io/` 


##How to add a person to the people page
