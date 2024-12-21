# textx-lionweb

## Overview

textx-lionweb is a project that aims to integrate the LionWeb standard into the TextX framework. This integration will enable TextX to export and import models in a LionWeb-compliant format, enhancing interoperability with other model-driven engineering (MDE) tools.

The project is a part of a master thesis titled **"Support for LionWeb standard in TextX"** and explores how LionWeb's metamodeling language and model serialization standards can be supported within TextX.

## Objectives

**1. Export TextX Models in LionWeb Format:**
Implement functionality to serialize TextX models into LionWeb-compliant JSON.

**2. Support for Metamodels:**
Provide a way to export TextX grammars (metamodels) in LionWeb's metamodeling language (MML).

**3. Import LionWeb Models:**
Enable TextX to parse LionWeb-compliant JSON models into TextX's internal representation.

**4. Interoperability:**
Ensure seamless exchange of models and metamodels between TextX and other LionWeb-compliant tools.

## Features

- **Model Serialization:** Export TextX models to LionWeb JSON format.
- **Metamodel Integration:** Convert TextX grammars into LionWeb-compliant metamodels.
- **Model Import:** Read LionWeb-compliant JSON models and parse them using TextX.

## Implementation Plan

### Phase 1: Research and Analysis

- Study LionWeb's metamodeling language and JSON serialization format.
- Analyze TextX’s architecture for extensibility points.

### Phase 2: Mapping LionWeb and TextX Concepts

- Map LionWeb’s metamodeling constructs to TextX grammar rules.
- Define a correspondence between TextX’s abstract syntax tree (AST) and LionWeb JSON models.

### Phase 3: Export Functionality

- Implement a function to serialize TextX models into LionWeb-compliant JSON.
- Write unit tests to validate the output against LionWeb specifications.

### Phase 4: Import Functionality

- Implement a parser to read LionWeb JSON models and transform them into TextX’s internal representation.
- Write unit tests to ensure correct parsing and validation.

### Phase 5: Metamodel Export

- Extend the functionality to convert TextX grammars into LionWeb's metamodeling language.
- Validate compatibility with other LionWeb-compliant tools.

### Phase 6: Documentation and Finalization

- Write detailed documentation on usage, architecture, and implementation details.
- Create example DSLs and models to demonstrate interoperability.
