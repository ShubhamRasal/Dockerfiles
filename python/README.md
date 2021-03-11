## PYTHON

```python
FROM python:3.7-alpine

# copy python progams to container
COPY . .

#define default excutable
ENTRYPOINT ["python3"]

# give default argument to excutable
CMD ["hello-world.py"]
```

## Build

`# docker build --tag <username>/python-script .`

## Usage

`# docker run <username>/python-script`

`# docker run <username>python-script system-details.py `