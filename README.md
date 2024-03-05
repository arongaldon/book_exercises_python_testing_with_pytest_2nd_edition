# book exercises python testing with pytest 2nd edition

My exercises from the book Python Testing with pytest (second edition).

## Setup

```sh
sudo apt install python3-venv unzip && \
git clone git@github.com:arongaldon/book_exercises_python_testing_with_pytest_2nd_edition.git && \
cd book_exercises_python_testing_with_pytest_2nd_edition && \
python3 -m venv venv && \
source venv/bin/activate && \
wget https://media.pragprog.com/titles/bopytest2/code/bopytest2-code.zip && \
unzip bopytest2-code.zip && \
rm bopytest2-code.zip && \
pip install -r requirements.txt
```

## Tests execution

```sh
pytest
```
