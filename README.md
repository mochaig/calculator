# Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910

## What will it do
Add, subtract, multiply, and divide two numbers; display the result.
Aswell as this, it will have a recursive interface so you can do more than one calculation without rerunning the code.
## How to run it
Run: ./run.sh
Also works from cd ~/h-drive/calculator/run.sh
Stop by pressing Ctrl + C
Enter the first number, operator (+ - * /), then the second number.
The program prints Result: followed by an answer.

#To test
Activate the SCCM4910 virtual environment using this command: source /opt/python-venv/sccm-4910/bin/activate
Then check pytest: python3 -m pytest --version
Then to acivate the test run: ./check.sh

#Expected results

test_add: 5
test_subtract: 2
test_multiply: 12
test_divide: 3
test_ divide_uneven: 2.5
test_ negative_addition: -5
test_ multiplicaton_ by_zero: 0

exit status: 0 = all passed, 1 = at least one failure.
