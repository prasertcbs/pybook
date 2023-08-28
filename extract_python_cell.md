## extract code block
(?<=)```\{\.python.+?(?=)```
(?<=)```python.+?(?=)```

/gms

## replace with ##
(?<=)```\{\.python.+?(?=)="

## replace with \n
"\}\n