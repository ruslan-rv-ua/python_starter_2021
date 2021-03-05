# mkdocs_website

template for creating websites with MkDocs site generator

1. Using this repo as template create new one with `new_repo_name`
1. Clone your new repo
1. Go to repo's folder:
	
	cd `new_repo_name`
	
1. Create and activate new virtual environment:
	
	python -m venv .venv
	.venv\scripts\activate
	
1. Install requirements:
	
	pip install -r requirements.txt
	
1. Run continuous rendering:

	run.bat
	
1. Edit `mkdocs.yml`

1. Make files, add navigation in `mkdocs.yml`

1. When ready, build and deploy:

	build.bat
	git add .
	git commit
	git push
	
1. Customize repository to publush your site
	

## Docs

- [MkDocs](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
