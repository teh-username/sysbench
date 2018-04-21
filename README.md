# Sysbench on Docker

A simple docker image for running the latest [Sysbench](https://github.com/akopytov/sysbench) software.

## Building

Option 1:

```
git clone https://github.com/teh-username/sysbench
cd sysbench
docker build -t tehusername/sysbench .
```

## Usage

```
docker run tehusername/sysbench sysbench --version
```
