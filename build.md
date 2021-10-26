# Build basics

## All requirements update

```bash
pip-compile --generate-hashes --allow-unsafe -o requirements.txt base_requirements.in full_requirements.in project_requirements.in
```

## Container requirements update

Note missing `full_requirements.in`

```bash
pip-compile --generate-hashes --allow-unsafe -o project_requirements.txt base_requirements.in project_requirements.in
```
