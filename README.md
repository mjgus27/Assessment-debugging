## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

1. Fork or clone this repo.
2. Fill missing dependencies and author section in `pyproject.toml`, fix any other problems if exists.
3. Fix bugs prevent the app `main.py` from running, or cause any errors if the app is running.
4. Change port the app ruuning on to `10030`.
5. Update `README.md` with an instruction about how to run this app:
   1. Choose either Arch Linux or Fedora Linux, and don't mess with the system `python` environment.
   2. Use a modern python package manager that respects `pyproject.toml` and `.python-version`, rather than `pip`.
   3. Setup virtual environment, start the app, and access the app.
6. Commit and push all the changes, and provide a link to your own repo in your submission in the last.


## Instructions 

1. Clone this repo
2. Ensure python (version 3.10 or 3.11) and uv are installed. Use "uv python pin 3.1x" if there are incompatible versions present.
3. Run "uv sync" to grab dependencies
4. Run "uv run python main.py" to start the app and access in the browser at localhost:10030
