 🧪 SauceDemo Automation Framework

This project is a UI test automation framework using **Python**, **Playwright**, and **Pytest** to automate the [SauceDemo](https://www.saucedemo.com) e-commerce site.

## ✅ Features

- Page Object Model (POM) structure
- Covers login, sorting, cart, checkout, and logout flows
- HTML test reports
- Parallel test execution
- Easy to maintain and extend

---

## 🚀 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/saucedemo-tests.git
cd saucedemo-tests
Create and activate virtual environment

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate   # or source venv/bin/activate on macOS/Linux
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
playwright install
🧪 Run Tests
Run all tests
bash
Copy
Edit
pytest
Run specific test
bash
Copy
Edit
pytest tests/test_checkout.py::test_successful_checkout
Run with HTML report
bash
Copy
Edit
pytest --html=report.html
⚡ Run Tests in Parallel
bash
Copy
Edit
pytest -n 4
Use -n auto to auto-detect CPU cores.

📁 Folder Structure
bash
Copy
Edit
pages/         # Page Object files
tests/         # Test cases
conftest.py    # Fixtures and setup
pytest.ini     # Pytest config
README.md
👤 Author
Suraj Kukkipady