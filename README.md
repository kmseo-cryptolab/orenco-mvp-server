# Orenco-mvp-server

> server - Orenco Workflow: MVP Phase

Orenco is a Database with RESTful API built with Python 3.10 and FastAPI.

## Table of Contents

- [Pre-requisites](#pre-requisites)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)

## Pre-requisites

Ensure you have the following installed:

- [Anaconda](https://www.anaconda.com/products/distribution)
- Python 3.10

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kmseo-cryptolab/orenco-mvp-server.git
   cd orenco-mvp-server
   ```

2. Create a conda environment:

   ```bash
   conda create -n orenco python=3.10
   conda activate orenco
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt --no-deps # needs no deps option
   ```

## Usage

Run the server with:

```bash
./run_server.sh
```

The API will be accessible at `http://0.0.0.0:8000`.

## Testing

To run the tests, ensure your conda environment is activated and execute:

```bash
pytest
```
