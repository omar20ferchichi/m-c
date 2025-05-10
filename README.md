# Python Testing with Pytest

This project demonstrates how to write and run tests using the [`pytest`](https://docs.pytest.org/) framework in Python.

## 📁 Project Structure
![Alt text](image.png)

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

![Alt text](image-1.png)

### Main test scenario 

![Alt text](image-2.png)


# Other test scenarios

## Chapter 1: Introduction

![Chapter 1 - Introduction](image-1.png)

## Chapter 2: Setting Up

![Chapter 2 - Setup](image-1.png)

## Chapter 3: How to Use

![Chapter 3 - Usage](image-1.png)

## Chapter 4: Troubleshooting

![Chapter 4 - Troubleshooting](image-1.png)

## Chapter 5: Conclusion

![Chapter 5 - Conclusion](https://link-to-your-image5.jpg)
