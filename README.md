# exercise-mr

Exercise of a Map-Reduce

We have 4 csv files in the dataset folder in  src/main/resources with the next structure.

```
date,concept,amount
yyyy/MM/dd,string value,double value
2014/10/23,gas,456.34
2014/03/03,groceries,6.34
...

```

All the dates are belonging to the same year. We want to generate as many files as months in that year. Showing the average value for that day and concept. See the next example

For the input 

```
2014/10/23,gas,10
2014/10/23,gas,15
2014/10/23,gas,20
2014/10/23,car,20
2014/10/23,car,25
```

the output will be:

```
2014/10/23,gas,15
2014/10/23,car,22.5
```


