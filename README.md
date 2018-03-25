# MI theme

Udata theme for lecatalogue (part of latelier) 

## Usage

Install the theme package in you udata environement:

```bash
pip install lecatalogue
```

Then, define the installed theme as current in you `udata.cfg`:

```python
THEME = 'lecatalogue'
```

## Development

There is a `docker-compose` configuration to get started fast.
Just run:

```bash
docker-compose up
```

Then go to <http://localhost:7000> to connect to the development server
with live reload.
