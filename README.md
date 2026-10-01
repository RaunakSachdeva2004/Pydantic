# Pydantic Examples

A collection of Python scripts demonstrating the core features and concepts of the Pydantic library for data validation and settings management.

## Contents

This repository contains standalone scripts, each focusing on a specific Pydantic concept:

- **1-why.py**: Introduction to Pydantic and the problems it solves regarding data validation and typing.
- **2-field_validator.py**: Implementation of field-level validation using `@field_validator`.
- **3-model_validator.py**: Implementation of model-level validation using `@model_validator` to validate dependencies between different fields.
- **4_computed_fields.py**: Usage of `@computed_field` to generate properties dynamically based on model data.
- **5_nested_models.py**: Structuring complex data using nested Pydantic models.
- **6_serialization.py**: Techniques for serializing models into dictionaries or JSON, including handling unset or excluded fields.

## Prerequisites

To run these examples, ensure you have Python 3.8+ installed along with the `pydantic` package.

Install the required dependency using pip:

```bash
pip install pydantic
```

## Usage

Each script is designed to be executed directly from the command line:

```bash
python 1-why.py
```