# Студенческий проект CI / CD

![CI Pipeline](https://github.com/ozon4ik/ci-cd-student-project/actions/workflows/ci.yml/badge.svg?branch=main)

Простой проект для демонстрации CI/CD pipeline с автоматическим тестированием.

## Стек технологий

- Python 3.8 / 3.9 / 3.10
- pytest + pytest-cov
- flake8 (линтер)
- bandit (безопасность)

## Структура

- `src/calculator.py` — класс Calculator
- `tests/test_calculator.py` — тесты
- `.github/workflows/ci.yml` — CI pipeline