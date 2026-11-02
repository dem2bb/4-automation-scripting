# Basic automation script

Prints the current system date and time.

## Files

- `show-date.sh` — Bash script that prints the date and time
- `README.md` — this file

## Run

```bash
./show-date.sh
```

## Expected result

The script prints a heading, the current system date and time, and a success message. The process exits with code 0.

## Checks

```bash
bash -n show-date.sh
./show-date.sh
./show-date.sh
echo "Exit code: $?"
```

## Evidence

### Outcome 1

A simple automation script performs the intended basic task.

Screenshot commands:

```bash
cat show-date.sh
./show-date.sh
```

### Outcome 2

Script execution completes successfully without errors.

Screenshot commands:

```bash
./show-date.sh
echo "Exit code: $?"
```

Expected exit code: 0.
