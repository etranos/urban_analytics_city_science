1.  create a project as quarto website locally

2.  then new repository on git, the local project already has git, connect with the repository and then follow the `docs` publishing process:

https://quarto.org/docs/publishing/github-pages.html

3.  On the repo attributes: pages `local` and `/docs`

4.  library(quarto) quarto.cmd preview on terminal keeps the development server on and automatically re-renders what is changed. quarto_render() or quarto.cmd renders

5.  For Git: git add --all 
             git commit -m "..."
             git push
