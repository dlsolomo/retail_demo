The first phase will consist of realtime reporting on the daily sales.  For this phase, the example data can be modified  so that all transaction dates are changed so that they all happen in the same day.  This will simulate 0.5M transactions/day.  This could be as low as 5 transactions/second which may not provide interesting realtime charts.

The initial dataset is created with:

```
# setup python libaries
$ pip install -r requirements.txt
```
and then 

```
# download and prepare the dataset
$ python prepare.py
```
