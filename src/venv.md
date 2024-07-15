# installing and creating a virtual environment

So we want to create a virtual environment for our project

let's run this simple command on our terminal

```bash
 python -m venv djangoproject
```
![pyhton3 error](./assets/python3%20error.png)

Whaaat,as it turns ouot linux users need to call in *python3* instead of just *python* Okay let's add the `python3` thing

```bash
pyhton3 -m venv djangoproject
```
![virtualenv missing](./assets/venv%20missing.png)

Okay let's sovle this issue  by installing the virtual environment as suggested

```bash
sudo apt install python3.0.10-venv
```

You will be asked to confirm the operation type **`Y`** to confirm
![confirm operation](./assets/env%203.png)

let's  now create our virtual environment


```bash
python3 -m venv djangoproject
```
![create venv](./assets/env%204.png)

## Kudos you have now created a virtual environment for your project