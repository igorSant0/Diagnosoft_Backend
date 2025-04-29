# 🩺 Integrating Project - Back-end

This repository contains back-end files related to the development of a health-focused system for the **Integrating Project** course.

The system allows doctors to create **customized forms** to conduct **clinical searches**, aiming to **improve diagnostic accuracy** for patients.

---

## ⚙️ Requirements

- install [Docker](https://www.docker.com/)

---


## How to execute the environment

### 1. Clone this Repository

```bash
git clone [https://seu-repositorio.git](https://github.com/igorSant0/Diagnosoft_Backend.git)
```


### 2. Build the Containers

to build a container:

```bash
docker compose build 
```

To force a reconstruction without the cache:

```bash
docker compose build --no-cache
```

### 4. Up the project

After to build, run:

```bash
docker compose up
```

