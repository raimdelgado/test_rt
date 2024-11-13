
# test_rt

Tool to measure latency of real-time tasks in Linux based on cyclictest and gnuplot.

## Dependencies

Install rt-tests and gnuplot 

```bash
  sudo apt-get install rt-tests gnuplot
```

If test_rt is not executable after download, run the following command:  

```bash
  sudo chmod +x test_rt
```


## Usage Example
To run test_rt, run the following command:
This will run for 10 seconds and the output files will be stored in ./test_rt_{date_time}

```bash
  sudo ./test_rt 
```

Add duration(in seconds) of the test as an argument.
For example, 10 seconds.

```bash
  sudo ./test_rt 10
```
