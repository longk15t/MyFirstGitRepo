- Run whole test folder `pytest tests`
- Run specific test suite `pytest tests\test_suite1.py`
- Run specific test scenario (class) `pytest tests\test_suite1.py::TestExplorer`
- Run specific test case `pytest tests\test_suite1.py::TestExplorer::test_case1`
- Run test with generated html report `pytest tests --html=report.html`
- Run test with mark `pytest tests -m=plus`
