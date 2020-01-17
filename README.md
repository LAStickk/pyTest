# Known issues
Если возникло "ImportError: cannot import name 'MarkInfo'"
	То удалить pytest-selenium

Если "TypeError: __init__() missing 3 required positional arguments: 'excinfo', 'start', and 'stop'"
	То обновить flaky в pip до последней версии

# To run tests
* clone the project 
```git clone```
* open the project in PyCharm
* [configure PyCharm to use pytest as default test runner](https://stackoverflow.com/a/6397315/1562282)
* click on green triangle near test that you want to run

# HTML Report
![Alt text](doc/html.png?raw=true "HTML Report")
# Allure Report
![Alt text](doc/allure.png?raw=true "Allure Report")
# Re-run failed tests
![Alt text](doc/re-run.png?raw=true "Re-run Failed")
