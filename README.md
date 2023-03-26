# python-web-api-flask-postgres-basic-auth-pop

## Description
Creates an api of pop for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses basic authentication.

| username | password |
-----------------------
| user | pass |

## Tech stack
- python
- flask
- postgres

## Docker stack
- python:latest
- postgresql

## To run
`sudo ./install.sh -u`
- Endpoint
  - `curl -i localhost/pop -u user:pass`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
