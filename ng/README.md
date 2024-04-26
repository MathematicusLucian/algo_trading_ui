# algo-trading-ui

***Angular:*** Front-End JavaScript framework.

``ng generate component components/list --style=scss --project=algo-ui``

## Env
- Create: ``python3 -m venv venv``
- Active: ``source venv/bin/activate``
- ***Requirements:***``pip freeze -r requirements.txt | sed '/freeze/,$ d'``

## Tests

### Running the Python Tests
- Flask (Python) unit tests are in the `server/tests` directory and managed by `manage .py` Python file.
- Run with: ``docker-compose -f docker-compose.yml run --rm crypto_tracker_flask python manage.py test``

### Running UI unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).