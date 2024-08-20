# build & test automation
APP_NAME=uiEvents
SHELL := /bin/bash

all:
	python ./${APP_NAME}.py

deps:
	pip install moderngl numpy objloader pillow pygame-ce pyglm

virtualenv:
	virtualenv .venv

clean:
	rm -rf *.o ${APP_NAME}
