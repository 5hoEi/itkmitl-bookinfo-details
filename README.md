# How to run details service

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```
## How to run with Docker

```bash
# Build Docker Image for details service
docker build -t details .

# Run Ruby
docker run -d --name detail -p 8081:8081 detail

* Test with path `/details/1` and `/health`