---
name: Data quality inquiry
about: Submit information about a float or profile with which you have an issue or
  question.
title: ''
labels: ''
assignees: cgrdn

---

** Metadata **

Provide the float number, the cycle number of concern, filename, what variable you believe may contain erroneous or inappropriately flagged data. You should also provide the file version/date of last update and md5 hash value. 

The date of last update can be found in the netCDF variable 'DATE_UPDATE' in the format YYYYMMDDHHMM. 

You can get the md5 hash value by running the following on a linux/unix machine: 

```
echo [filename] | md5
```

or by running the following on a windows machine in Command Prompt: 

```
certutil -hashfile [filename]
```

** Reason and Recommendation**

Why do you believe there should be a change to this data? Do you have an outcome you would expect or recommend (ex. "Change flag for data between 200-250dbar from 1 to 4")

** Evidence **

Provide evidence for your issue. This is a good section to submit supporting plots and/or code.
