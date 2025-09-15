# Experiment-11
## Pytest Installation
# Aim:
To install Pytest and to write test cases for a program and to test using Pytest.
# Pytest:
It is a testing framework that allows users to write test codes using python programming language. It helps you to write simple and scalable test case for databases, API’s or UI. Pytest is mainly used for writing tests from simple unit tests to complex functional tests.
# Procedure:
Installation on Windows:

1.Navigate to folder where the python is installed.
2.Open scripts folder and copy the address location.
3.Open command prompt and execute “cd copied_address_Location”.
4.Execute “pip install pytest”.
Creating File:

1.The file to be tested should have name as test_*.py or *_test.py
2.File should be located in the same folder where pytest module is installed
Creating a sample program:

1.Function to be tested should has name def test_*();
2.Inside the function the line to be tested should has assert keyword at the beginning.
Terminologies in Pytest:

F – Failed

– Passed S

– Skipped X

– xpassed x

– xfailed

Eg:

Parameterized Addition Program:

File name: test_parameter.py
```
import pytest 
@pytest.mark.parameterize(“input1, input2, output”,[(5,5,10),(3,5,12)])
```
```
def test_add(input1, input2, output):
  assert input1 + input2 == output
```
for execution : execute “pytest test_parameter.py”.
# Output
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/447728b3-d4c1-4c97-bd85-9f1b9ef1921b" />

# Result
Thus, we have installed pytest, implemented and executed a parameterized addition program and the output is verified successfully.
