## FastAPI + React + Docker + Nginx

### Getting Started
1. Clone the repo and cd the directory.
2. Set up the virtual env for python backend - `virtualenv virtual`
3. Activate virtualenv `. virtual/bin/activate` and install dependencies - `pip install -r app/requirements.txt`. Once installed, you can deactivate virtualenv.
4. Install ui dependencies - `yarn --cwd ./ui `. `--cwd ./ui` allows to specify directory where package.json is located.
5. You are all set up. Now run `./develop.sh` and you have live development environment. Make changes to app or ui code and it will hot-reload.