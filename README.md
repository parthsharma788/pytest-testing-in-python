# pytest-testing-in-python

## This project has two modules:

#### com.automationpanda.example.calc_func contains math functions.
#### com.automationpanda.example.calc_class contains a basic Calculator class.


## Running Tests
pytest has many command line options with a powerful discovery mechanism:

python -m pytest to discover and run all tests from the current directory
python -m pytest -v to explicitly print the result of each test as it is run
python -m pytest tests/test_calc_func.py to run only the math function tests
python -m pytest tests/test_calc_class.py to run only the Calculator class tests
python -m pytest --junitxml=results.xml to generate a JUnit-style XML test report
python -m pytest -h for command line help
