# Data model

## Proposed fields

Cases need a task, model label, output, reviewer notes, and optional score with rubric.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.