# python-netcat
an implementation of netcat like tool in python

# installtion
```
git clone https://github.com/0xkr3pt0n/python-netcat.git
cd python-netcat
python3 netcat.py
```

# Example usage

### setting up a listner
```
python3 netcat.py -t 192.168.1.102 -p 5555 -l -c
```

### TCP connect
```
python3 netcat.py -t 192.168.1.102 -p 5555
```
