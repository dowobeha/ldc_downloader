# LDC package downloading tool

Bash script by Lane Schwartz (dowobeha@gmail.com)
based on Python code (https://github.com/jonmay/ldcdl) by Jonathan May (jonmay@isi.edu)

04 March 2016


# Requirements:

* bash
* curl
* sed
* tr
* LDC login/password


# Usage:

```
$ ./ldcdl.py -h
usage: ldcdl.sh [LDC_ID1] ... 

Get corpus from LDC


$ ./download-ldc-corpora LDC99T42
2016-26-04 16:26:49 UTC-06  Removing previously downloaded files: cookies.txt corpora.tsv     ...
2016-26-04 16:26:49 UTC-06  Enter LDC login credentials                                       ...

Enter email address: lanes@illinois.edu
Enter Password: 

2016-26-04 16:26:54 UTC-06  Accessing LDC login page                                          ...
2016-26-04 16:26:54 UTC-06  Logging in to your LDC account                                    ...
2016-26-04 16:26:55 UTC-06  Accessing list of your LDC corpora                                ...

A list of the LDC corpora associated with your account has been saved to corpora.tsv


2016-26-04 16:26:56 UTC-06  Downloading LDC99T42 from https://catalog.ldc.upenn.edu/download/...
```

# Known Issues

* None