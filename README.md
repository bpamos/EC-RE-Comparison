# EC-RE-Comparison
EC-RE comparison

Compare ElastiCache and Redis Enterprise DB options. 
This only goes over single redis db deployments in ElastiCache & Redis Enterprise for Memory bound sizing.
Compare all available ElastiCache Cache Node deployment options to their respective Redis Enterprise deployment options.

This analysis can not really be used to determine a estimated pricing of a customer ElastiCache deployment vs a Redis Enterprise deployment.
It is more of a deep dive into how ElastiCache goes about deployment configurations and sizing vs Redis Enterprise.

For real Redis Enterprise to ElastiCache deployment comparison it is important to incorporate multi-tenancy and throughput needs. This repo does not do that.


# getting started

```
Create your virtual environment
* python3 -m venv ./venv
Install requirements
* pip install --upgrade pip
* pip3 install -r requirements.txt
(you may need to update your path with the python directory)
Open Jupyter notebook (it will open in a browser window)
* jupyter notebook
    - notebook/EC-RE-Comparison-Simplified.ipynb
```