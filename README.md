#!/bin/bash
name="feel2code"
langs="English, Russian"
skills="Python, Shell, ClickHouse, DBT"
tools="vim"

for key in name langs skills os tools; do eval "echo \"$key: \$$key\""; done
