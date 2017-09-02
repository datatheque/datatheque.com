# Datatheque

[Hugo Docs](https://gohugo.io/documentation/)

#### Start Jupyter
```bash
workon venv_notebooks
jupyter notebook notebooks
```

#### Convert Notebook to HTML
```bash
jupyter nbconvert --to html --template basic notebook.ipynb
```

#### Create a new Post
```bash
hugo new posts/new-post.md
```

#### Add Notebook to Post
Insert the following in the content of your post (after the front matter)
```
{{< readfile file="notebooks/notebook.html" >}}
```