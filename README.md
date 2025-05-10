# Python Testing with Pytest

This project demonstrates how to write and run tests using the [`pytest`](https://docs.pytest.org/) framework in Python.

## 📁 Project Structure

py_project/
│
├── docs/ # Source code directory
│ └── 
│
├── saucedemo-tests/ # Test cases
    │
    ├── config/ # necessary configurations
    │ └── config.yaml # web site configuration
    ├── pages/ # web pages to be imported in the tests 
    │ └── base_page.py # class to be used in other classes
    │ └── login_page.py # the login page
    │ └── products_page.py # the products page
    │ └── __init____.py # imports 
    │
    ├── tests/ # Test cases
    │    ├── cart/ # cart tests folder
    │    ├── checkout/ # checkout tests folder
    │    ├── edge/ # edge tests folder
    │    ├── login/ # login tests folder
    │    ├── products/ # cart tests folder
    │    ├── user_interface/ # cart tests folder
    │
    ├── requirements.txt # Project dependencies
    ├── README.md.txt # readme file
    └── README.md # Project documentation


## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. 🧪 Running Tests

To run all test cases:

```bash
pytest
```

To run tests with verbose output:

```bash
pytest -v
```

To run a specific test file:

```bash
pytest tests/login/test_login_valid_user.py
```


📊 Code Coverage (Optional):

```bash
pip install pytest-cov
pytest --cov=src
```

⚡ Parallel Test Execution (Optional):

```bash
pip install pytest-xdist
pytest -n auto
```