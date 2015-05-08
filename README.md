# runTools
### About
This repository provides two convenient automated testing tools for testing a formal test suite against a C++ program. They are written entirely in Bash script. *runSuite* runs a C++ program on each test in the test suite and reports on any tests whose output doesn't match the expected output. *runValgrind* runs a C++ program on each test in the test suite and reports on any tests which causes the program to have a memory error.

### Execution
#### runSuite
```Bash
./runSuite [suite-file] [program]
```
#### runValgrind
```Bash
./runValgrind [suite-file] [program]
```

> Note: **suite-file** is the test suite file and **program** is a compiled C++ program. **suite-file** contains a list of stems, from which the names of files containing the input and expected output of each test are constructed. For example, *./runSuite mySuite.txt ./myProgram* will run myProgram on each test in mySuite.txt.

### License
* runSuite and runValgrind are licensed under the [MIT license](https://github.com/elailai94/Automated-Testing-Tools/blob/master/LICENSE.md).
* runValgrind is a property of Kush Patel.
