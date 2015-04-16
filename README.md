# Automated Testing Tools
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

> suite-file

### License
* runSuite and runValgrind are licensed under the [MIT license](https://github.com/elailai94/Automated-Testing-Tools/blob/master/LICENSE.md).
* runValgrind is a property of Kush Patel.
