# Email Validation Tool

## Overview

This tool validates email addresses and categorizes them into deliverable and undeliverable lists. It processes input files and generates two output files: one for valid emails and another for invalid emails.

## Input and Output

### Input Format

Run the tool using the following command:

```bash
node index.js -i "InputFilePath" -o "OutputFolderPath"
```

```
It will create two new files inside the output folder path.

1) success.csv -> In this all the verified emails will present.
2) failure.csv -> In this all the failed emails will present.
```

# file formats
## input file format 
1) emails.csv
```
email
GaganSharma@hotmail.com
sharmagagan192@gmail.com
sharmagagan192@brainalive.com
chaitanya@brina.live
priya@braina.live
priya@yahoo.com
hamid@braina.live
sdfghjkl@brina.live
gagan@braina.live
```


## output file formats

1) success.csv
```
Email
sharmagagan192@gmail.com
priya@braina.live
hamid@braina.live
```

2) failure.csv
```
Email
sharmagagan192@brainalive.com
chaitanya@brina.live
sdfghjkl@brina.live
gagan@braina.live
```
