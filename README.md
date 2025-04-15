# Postman Newman API Test Automation

![GitHub Actions]((https://maximka47.github.io/PostmanNewman/))

This repository contains automated API tests for the Petstore API using Postman collections and Newman, with automated test reporting via GitHub Pages.

## Features

- Automated API testing using Postman collections
- CI/CD pipeline with GitHub Actions
- HTML test reports published to GitHub Pages
- Sample tests for the public Petstore API

## Test Report

View the latest test results report:  
[📊 Newman Test Report](https://maximka47.github.io/PostmanNewman/)

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Maximka47/PostmanNewman.git
2. **Run tests locally**:

  ```bash
  npm install -g newman newman-reporter-html
  newman run petstore.collection.json -r html,cli --reporter-html-export report.html
