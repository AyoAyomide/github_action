name: Say greeting to people

on: 
  # push:
  workflow_call:

jobs:
  Say-hello:
    runs-on: ubuntu-latest
    steps:
    - name: Say greeting
      run: |
        echo hello world 