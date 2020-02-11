# Branch Prediction Simulator

### Setting up the python virtual env and installing dependencies
```sh
$ python3 -m venv branchenv
$ source branchenv/bin/activate
$ pip install -r requirements.txt
```

### Executing the script
```sh
$ python branchsim.py -f [filename] -n [n] -m [m] -k [k]
```

 - *m* takes value in the range (0-11)
 - *k* takes value in the range (1-12)
 - *n* takes value 1 or 2
 - *f* input file name
 - Default values for m,n and k are  6, 1 and 8 respectively

### Example
```sh
$ python branchsim.py -f gcc-10K.txt -n 1 -m 6 -k 8
```
