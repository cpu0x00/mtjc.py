# Multi-Threaded JWT Cracker #


```
usage: mtjc.py [-h] --cookie COOKIE --wordlist WORDLIST [--threads THREADS] [--verbose] [--force]

options:
  -h, --help            show this help message and exit
  --cookie COOKIE, -c COOKIE
                        JWT token to crack (HS256)
  --wordlist WORDLIST, -w WORDLIST
                        wordlist to use
  --threads THREADS, -t THREADS
                        threads to work with (default: 100)
  --verbose, -v         verbose the bruteforce attempts (affects the script's performance)
  --force               forces the bruteforcer to continue despite the (invalid base64 error)

(M)ulti (T)hreaded (J)WT (C)racker
```

- example:

`mtsb.py -c 'COOKIE_HERE' -w wordlist.txt -t 100`