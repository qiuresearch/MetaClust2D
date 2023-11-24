# MetaClust2D
Meta-cluster database of RNA secondary structures

## Tasks
### 1. A simple web server of our MetaClust database to enable search and download

We can refer to this site: http://zhaoserver.com.cn/RPocket/RPocket.html . We would aim for a much simpler site to begin with, though probably with better aesthetics.

Let's first host it on our own machine for testing.

### 2. Explorative data analysis of the RNAnet database

The entire database (in SQLite3 format) is available at https://evryrna.ibisc.univ-evry.fr/evryrna/rnanet/rnanet_home

Ideally, we like to accomplish the following:
* Understand the information within
* Additional analysis to obtain Clustering information, etc.
* Generate an updated database (SQL format or conversion to pandas)
* Implement a similar server as Task 1.

### 3. Web-based visualization of database statistics

Let's look into the use of Plotly with Python.
