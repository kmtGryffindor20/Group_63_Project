# Group_63_Project
This is the merged repository for the backend and frontend of the FilmFusion web application.

## Accessing Submodule Repositories

This project uses Git submodules to manage certain dependencies. A Git submodule allows you to keep another Git repository in a subdirectory of your repository.

The submodules used in this project are:

1. Backend
   - Path: `backend`
   - URL: `https://github.com/kmtGryffindor20/FilmFusion.git`
2. Frontend
   - Path: `frontend`
   - URL: `https://github.com/kmtGryffindor20/FilmFusion-Frontend.git`

To clone the repository along with its submodules, use the following command:

```bash
git clone --recursive https://github.com/kmtGryffindor20/Group_63_Project.git
```

If you've already cloned the project and want to pull the submodules, use:

```bash
git submodule update --init --recursive
```
