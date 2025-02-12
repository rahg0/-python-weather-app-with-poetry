# python-weather-app-with-poetry

## Installation
- Clone the repo:
```sh
$ git clone https://github.com/rahg0/python-weather-app-with-poetry.git
$ cd python-weather-app-with-poetry
```

- Install `[Pipx](https://pipx.pypa.io/stable/installation/)` tool (if not present already):
```sh
/python-weather-app-with-poetry$ python3 -m pip install --user pipx
```

- Add `Pipx` installation path to `PATH` env variable (either via manual updating `PATH` variable or with `pipx ensurepath`).
```sh
/python-weather-app-with-poetry$ pipx ensurepath

OR

/python-weather-app-with-poetry$ export PATH=$PATH:/<user>/.local/bin
```

- Install `[Poetry](https://python-poetry.org/docs#installation)` tool (if not present already):
```sh
/python-weather-app-with-poetry$ pipx install poetry
```



- Install all the dependency packages locked in `poetry.lock` file:
```sh
/python-weather-app-with-poetry$ poetry install --no-root
```

- Fetch the project's virtualenv:
```sh
/python-weather-app-with-poetry$ poetry env info --path
```

- Activate the virtualenv manually:
```sh
/python-weather-app-with-poetry$ source <venv-path>/bin/activate
```

- Create an [OpenWeather](https://openweathermap.org/) account and generate an API Key.

- Assign the API Key for **api_key** in `app.py` file. 

- Run the application:
```sh
(python-weather-app-with-poetry-py3.13) /python-weather-app-with-poetry$ python app.py
Enter the city name: delhi
Weather in Delhi:
Temperature: 25.05°C
Condition: Haze
```
