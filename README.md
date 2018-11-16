# code-gov-repos-parser
Parse out information from code.gov repos

# Why?
Repeating a lot of code between front-end and code-gov-data

# Usage
```
import { getAgencies } from '@code.gov/repos-parser

fetch("https://api.code.gov/repos?api_key=DEMO_KEY")
.then(response => response.json())
.then(data => data.repos)
.then(getAgencies)
.then(console.log)
```

# Contact
code@gsa.gov
