```bash
#!/bin/bash
name="feel2code"
job="Developer"
langs=("English" "Russian")
progs=("Python" "Shell")
dbs=("MySQL" "ClickHouse" "Postgres" "MongoDB")
os="Linux lover"
tools=("i3" "SpacEmacs")

profile="Name: $name\nJob: $job\nLang: ${langs[*]}\nProg: ${progs[*]}\nDB: ${dbs[*]}\nOS: $os\nTools: ${tools[*]}"
echo -e "$profile"
```
