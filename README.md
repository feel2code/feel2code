```bash
#!/bin/bash
name="feel2code"
job="Developer"
langs=("English" "Russian")
skills=("Python" "Shell" "ClickHouse" "DBT")
os="GNU/Linux"
tools=("vim")

profile="Name: $name\nJob: $job\nLang: ${langs[*]}\nSkills: ${skills[*]}\nOS: $os\nTools: ${tools[*]}"
echo -e "$profile"
```
