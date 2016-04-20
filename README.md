# Hue Lights control in Python

This repository contains basic scripts for testing the Philips Hue APIs from Python. The available files include:

* `rest.py` a rest helper for easily sending request to a given API endpoint with a given payload, using a given HTTP verb
* `hue.py` a simple tester for the Philips Hue API turning all available lamps on, in color-loop mode
* `hue_api.py` a basic Philips Hue library to be extended at will
* `hue_api_test.py` a simple test script using the `hue_api.py` module.