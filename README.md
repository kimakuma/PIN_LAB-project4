![header](https://capsule-render.vercel.app/api?type=soft&color=006EDB&fontColor=DEEAF7&height=200&section=header&text=PIN_LAB&desc=Project%204&descAlignY=80&fontSize=90)
# PIN_LAB: Project 4

Distribution WAV file recorder linked Cloud Database based on Docker on Jetson Nano board

---

## Navigation
1. [Description](#Description)
2. [Getting started](#Getting-Started)
3. [Architecture](#Architecture)

---

## Description
Distribution WAV file recorder linked Cloud Database based on Docker on Jetson Nano board
- Recording(Saving) WAV file and Playing WAV file via Atlas(MongoDB)
- Distribution via Docker

---

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Installing & Setting (based on Code)
- Installing the pip
    - pip: for Python 2.x
    - pip3: for Python 3.x
```console
sudo apt-get install python-pip3
```

- Installing the PyMongo
    - ref: https://kb.objectrocket.com/mongo-db/how-to-install-pymongo-and-connect-to-mongodb-in-python-363
```console
pip3 install pymongo
```

- More packate to install are in Dockerfile

### Installing & Setting (based on Docker)

### Running the tests
```console
gcc {file_name.cpp} -lasound -Wno-write-strings -o {exe_name}
```

### docker
[kimakuma8/ubuntu:project3](https://hub.docker.com/layers/kimakuma8/ubuntu/project3/images/sha256-a7c68cba54a68254646067b6d37e700e0ff1d643d7900beafe8b2a5fcd9ea4f2?context=repo)

---

## Architecture
### Docker


### Architecture

---

## Stacks
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=C&logoColor=white"> <img src="https://img.shields.io/badge/Raspbian-A22846?style=for-the-badge&logo=Raspberry Pi&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
