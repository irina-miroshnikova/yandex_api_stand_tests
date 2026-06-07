# API Tests for User Creation — Yandex.Prilavok

This repository contains automated API tests for checking the `firstName` parameter during user creation in the Yandex.Prilavok training API.

The project demonstrates basic API test automation skills using Python, pytest, and requests.

## What is tested

* User creation via API
* Validation of the `firstName` field
* Positive test scenarios
* Negative test scenarios
* API response status codes
* Response body validation

## Tools and Technologies

* Python
* pytest
* requests
* Git / GitHub

## Project Structure

```text
yandex_api_stand_tests/
├── configuration.py          # Base URL and API paths
├── data.py                   # Test data
├── sender_stand_request.py   # API request helper functions
├── create_user_test.py       # Automated API tests
├── requirements.txt          # Project dependencies
├── README.md                 # Project documentation
└── .gitignore                # Ignored local and generated files
```

## How to Run Tests

Install dependencies:

```bash
pip install -r requirements.txt
```

Run tests:

```bash
pytest
```

## QA Focus

The project focuses on checking how the API handles valid and invalid values in the `firstName` field.

The tests help verify that the API returns expected status codes and handles input validation correctly.

## Notes

This is a training QA project.

No real credentials, tokens, or confidential data are stored in this repository.
