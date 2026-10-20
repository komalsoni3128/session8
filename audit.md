# Testing and Debugging Audit

## Objective
To identify and fix bugs in a Python utility script using unit testing and AI-assisted debugging.

## Testing Process
1. Created a buggy implementation.
2. Wrote 9 unit tests for average calculation, pass/fail checking, and grade assignment.
3. Ran the tests and observed failures and an error (**RED**).
4. Corrected the identified logic errors (**FIX**).
5. Ran the tests again.

## Final Result
All 9 tests passed successfully (**GREEN**).

## Verification
Command used:

`python -m unittest -v test_student_utils.py`

Output: `Ran 9 tests` — `OK`.

## Conclusion
The RED → FIX → GREEN cycle helped identify errors, apply targeted corrections, and verify the program's behavior.