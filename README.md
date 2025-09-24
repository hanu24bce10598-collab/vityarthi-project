# Campus Course & Records Manager (CCRM)
Author: Ananjay Goyal

## Overview
Java SE console project demonstrating OOP, enums, builder, singleton,
file I/O with NIO.2, recursion, and menu-driven CLI.

Prepared by **Ananjay Goyal**  
Generated on 2025-09-23 12:00:49Z

## Compile & Run
Linux/macOS:
```bash
javac -d out $(find src -name "*.java")
java -cp out edu.ccrm.cli.CCRMApp
```

Windows PowerShell:
```powershell
Get-ChildItem -Recurse -Filter *.java | % { $_.FullName } | ForEach-Object { $_ } > sources.txt
javac -d out @sources.txt
java -cp out edu.ccrm.cli.CCRMApp
```

## Structure
- src/edu/ccrm/domain → domain classes & enums
- src/edu/ccrm/service → service classes
- src/edu/ccrm/io → import/export & backup
- src/edu/ccrm/util → utilities
- src/edu/ccrm/config → singleton config
- src/edu/ccrm/cli → main CLI app
- test-data → sample CSVs
- screenshots → put your own screenshots
