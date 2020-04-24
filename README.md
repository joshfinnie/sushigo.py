# sushigo.py
A Pythonic Sushi Go Scorer.

## Development

Make sure you have `poetry` installed globally.

To install the required packages, run `poetry install`.

To run the development server, run `make run` or `poetry run gunicorn -b 127.0.0.1:4000 src:app`.

Your server should be viewable at http://localhost:4000!
