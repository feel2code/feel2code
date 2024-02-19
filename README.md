```bash
#!/bin/bash
name="feel2code"
job="Developer"
langs=("English" "Russian")
progs=("Python" "Shell")
dbs=("ClickHouse" "Postgres" "Vertica" "MySQL" "IBM DB2" "MongoDB")
os="Arch linux"
tools=("i3" "Neovim")

profile="Name: $name\nJob: $job\nLang: ${langs[*]}\nProg: ${progs[*]}\nDB: ${dbs[*]}\nOS: $os\nTools: ${tools[*]}"
echo -e "$profile"
```
