# How to check if a command exists

```bash
if command -v CMD &> /dev/null; then echo "it exists"; fi
```

- command -v who &> /dev/null - checks if command ```CMD``` exists (silently). Use ```if ! commain...``` to check if command doesn not exist.
- echo "it exists" - the code that will run if the command exists