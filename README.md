This is REST API Testing automation code using Python

Application used for testing:

App: https://berpress.github.io/react-shop/

Install Allure Framework
Install Java

### How to run tests

- **Without Allure Test report**

All tests:
```
pytest
```
Positive tests:
```
pytest -m positive
```
Negative tests:
```
pytest -m negative
```
- **With Allure Test report**
```
pytest --alluredir=allure_reports
```
Show generated report in browser:
```
allure serve allure_reports
```