[![Locust-Flask with Github Actions](https://github.com/kb1907/Locust-Flask/actions/workflows/main.yaml/badge.svg)](https://github.com/kb1907/Locust-Flask/actions/workflows/main.yaml)

# Flask-Locust-Github-Actions

Locust-Flask-Github Actions folder for MLOPS 2022 Data Scientist Trainees and DS Aspirants.

![1](https://user-images.githubusercontent.com/51021282/175612530-a24a9066-01c0-4e2c-b31d-3e0a3b1a5a59.png)



![2](https://user-images.githubusercontent.com/51021282/175612594-eece4468-f5bf-407d-8f3f-3e5729cb0f71.png)



![3](https://user-images.githubusercontent.com/51021282/175612737-830373cc-ad88-48f8-af91-698b8411ef79.png)



### New environment

```bash
    conda create -n flask-locust  python=3.9 -y
```

Activate the environment

```bash
    conda activate flask-locust
```

Requirements File

```bash
    touch requirements.txt
```

### Connect to Github

```bash
git init
```

```bash
git add .
```

```bash
git commit -m "first commit"
```

oneliner updates for readme

```bash
git add . && git commit -m "update Readme.md"
```

pushing changes to new repo

```bash
git remote add origin https://github.com/kb1907/Locust-Flask.git
git branch -M main
git push -u origin main
```

### Run `make all` to install python libraries, lint project, run tests.

### Run `locust` to see load test


