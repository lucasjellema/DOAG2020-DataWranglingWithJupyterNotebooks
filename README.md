# DOAG2020-DataWranglingWithJupyterNotebooks
Sources for my DOAG2020 session on Data Wrangling with Juypter Notebooks

Open an Ubuntu 20.04 environment on Katacoda using this URL in your browser:

https://www.katacoda.com/courses/ubuntu/playground2004

```
mkdir work
cd work
git clone https://github.com/lucasjellema/DOAG2020-DataWranglingWithJupyterNotebooks
```
Then start the Docker container:
```
docker run --rm -p 10000:8888 -v "$PWD":/home/jovyan/work -e JUPYTER_ENABLE_LAB=yes jupyter/minimal-notebook
```
Open Browser Window at Port 10000

Add the next content to a cell and execute the cell:
```
# initialize environment by installing some Python3 libraries through pip
%pip install pandas
%pip install matplotlib
```
