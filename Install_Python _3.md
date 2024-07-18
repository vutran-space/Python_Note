#Step 1 — Setting Up Python 3
```python
sudo apt update && sudo apt -y upgrade
````
```python
sudo apt install -y python3-pip
````
```python
sudo apt install build-essential libssl-dev libffi-dev python-dev
````

#Step 2 — Setting Up a Virtual Environment
```python
sudo apt install -y python3-venv
````
```python
mkdir environments
cd environments
````
```python
python3 -m venv my_env
````
```python
ls my_env
````
```python
Output
bin include lib lib64 pyvenv.cfg share
````
```python
source my_env/bin/activate
````
```python
Output
(my_env) root@tool-net-sgn:/home/user/environments#
````
