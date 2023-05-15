
# medbase docs
MkDocs with material theme

### Previewing as you write
```bash
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```
Preview: [localhost:8000](localhost:8000)


### Build docs
```bash
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build
```


### Deployment
Pushing changes to `main` branch will trigger the GitHub Action to build and deploy the docs to GitHub Pages.
Your documentation should shortly appear at https://cepheivv.github.io/medbase-docs/.
