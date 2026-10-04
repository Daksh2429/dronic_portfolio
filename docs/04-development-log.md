# DroniC — Development Log

## Phase 1: Development Environment

**Status:** Completed

### Activities

- Cloned the existing GitHub repository into VS Code.
- Verified the local and remote Git configuration.
- Created a Python virtual environment using `py -m venv .venv`.
- Configured `.gitignore` to exclude the environment, local database, cache files, and environment secrets.
- Installed Django 5.2.17.
- Initialized the Django project using `django-admin startproject config .`.
- Started the Django development server.
- Applied Django's initial database migrations.
- Committed and pushed the initial project structure to GitHub.

### Key Concepts Learned

**Virtual Environment:** Isolates Python dependencies for a specific project.

**Git Staging:** Selects changes to include in the next commit.

**Git Commit:** Saves a checkpoint in local repository history.

**Git Push:** Transfers local commits to the remote repository.

**Django Project:** Contains project-wide configuration and management utilities.

**Migration:** Applies database schema changes defined by Django applications.

**Development Server:** Provides a local environment for testing HTTP requests and responses.

### Challenges Encountered

- Git Bash initially did not recognize the global `python` and `pip` commands.
- Used the Windows Python launcher (`py`) to create the virtual environment.
- Corrected a command spelling error when starting `manage.py`.
- Learned the difference between Windows paths and Git Bash paths.

### Next Milestone

Create the `core` Django application and implement the first custom URL and view.