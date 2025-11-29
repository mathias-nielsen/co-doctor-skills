---
name: Diagnosis.
description: An important skill, to help agents assist doctors with diagnosising patients.

---

# Diagnosis tasks

## Extrapolate symptoms
This action can extrapolate and gather symptoms from natural language input

```python
def extrapolate_symptoms(text):
  # Mock Code
  # ...
```

## Find potential diagnosis
This action will find potential diagnosis, based on common external resources

```python
def find_potential_diagnose(symptoms):
  """ This function will return 1 or more diagnosis, based on array of symptoms """
  # Mock Code
  # ...
```

## Suggest Next Steps
In case a diagnosis is inconclusive, but more tests is needed, this task will find the best next step to in the diagnosis 

```python
def find_next_steps(symptoms, diagnosis):
  # Mock Code
  # ...
```
