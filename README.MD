# Jest Analyzer

This utility give analysis of your Jest test files
<br>Currently following analysis are implemented

- Number of test cases per file
- Assertions are present inside test-case or not

### How to run the utility

- `npm i`
- `npm run start -- --test_dir=\<JEST-TEST-DIR\>`
- It will output you the analysis

### Create Executable
- `npm run build` 
- It will create executable inside `build/jestAnalyzer.exe`
- To run the executable `<PATH-TO-EXE>/jestAnalyzer.exe --test_dir=<TEST-DIR>`