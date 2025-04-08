# insights-pyodbc

`insights-pyodbc` is a pyodbc layer designed for use with AWS Lambda functions.

## Overview

This repository provides a pre-built pyodbc layer for AWS Lambda, enabling seamless integration with SQL Server databases. The layer is based on the following:

- **Source**: [AWS Lambda pyodbc layer v1.0.0](https://github.com/vickyboston20/aws-lambda-pyodbc-layer/releases/tag/v1.0.0)
- **Python Version**: 3.12
- **ODBC Driver**: ODBC Driver 18 for SQL Server

## Usage

The files in this repository are zipped in the required structure and can be uploaded directly to AWS Lambda as a custom layer.

## License

Refer to the source repository for licensing details.

## To Do (Future Task)

The pyodbc layer can also be created using the `publish_pyodbc_dependencies_layer.txt` file located in the `insights` repository at the following path. If we achieve that, we may not require this repo at all...

`~\insights\app\build\publish_pyodbc_dependencies_layer.txt`