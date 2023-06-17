# teaching_python
A plan for Python teaching

0. Git, GitHub
   0.1. GitHub Registration

1. 

   
3. IDE
   1.1. MS Visual Studio Code
   1.1.1. Installation
   1.1.2.
   
4. TODO LIST
   3.1.
   
5. TESTING
4.1. What is TDD
4.2. Pytest

   https://docs.pytest.org/en/7.1.x/index.html
   
   4.2.1. Installation
   4.2.2. Folders organization

Use a separate folder for tests. This will help to keep your test code separate from your application code, making it easier to maintain and run your tests.
Use a consistent naming convention for your test files and folders. This will make it easier to find and run your tests.
Organize your tests by feature or functionality. This will help to keep your tests organized and make it easier to run specific sets of tests.
Use pytest fixtures to share data and state between tests. This will help to make your tests more reusable and efficient.
Use pytest markers to identify different types of tests. This will help you to run specific sets of tests, such as unit tests or integration tests.
Use a test runner to run your tests. This will help you to run your tests in a consistent and repeatable way.

app
├── main
│   ├── __init__.py
│   └── views.py
├── static
│   ├── css
│   ├── js
│   └── images
└── tests
    ├── unit
    │   ├── __init__.py
    │   └── tests.py
    └── integration
        ├── __init__.py
        └── tests.py
        
   4.2.3. Simple tests
   4.2.4. Exception catching

4.3. Pytest-cov

pytest-cov for test coverage



===
Project folder structure
Git, Github
IDE (Visual Studio Code)
TODO-lists
Testing


# Links

https://docs.pylenium.io/ -- library for testing "Bring the best of Selenium, Cypress and Python into one package."

