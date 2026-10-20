# Fixing a Buggy Python Script Using AI

## Project Overview
This project demonstrates how to test and debug a Python script using unit tests and AI-assisted debugging. It follows the RED → FIX → GREEN cycle.

## Files
- `student_utils.py` — Functions for calculating average marks, checking passing status, and assigning grades.
- `test_student_utils.py` — Unit tests that verify the expected behavior of each function.
- `audit.md` — Summary of testing and debugging.
- `bug_notes.md` — Details of the identified bugs and their fixes.

## Bugs Fixed
1. Incorrect average calculation due to the wrong denominator.
2. Division by zero when calculating the average of a single mark.
3. Incorrect passing result for a mark equal to the pass mark.
4. Incorrect grade classification because grade conditions were checked in the wrong order.

## Testing
Run the tests using:

```bash
python -m unittest -v test_student_utils.py
```

**Result:** All 9 tests passed.

## RED → FIX → GREEN
- **RED:** The original buggy implementation failed tests.
- **FIX:** The identified logic errors were corrected.
- **GREEN:** All 9 tests passed after the fixes.