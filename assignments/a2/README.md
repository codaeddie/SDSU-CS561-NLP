# XCS224N Revisions
Repository contents for the previous cohort is in the following branches.
- `Rev_XCS224N_Sept2019-Mar2021` branch: cohort from Sept. 2019 to March 2021

# XCS Student Code Repository
This repository contains all code for your assignment!
The build tools in this repo can be used to run the autograder locally or
compile a LaTeX submission.

# What should I submit?
Take a look at the problem set PDF:

- If it contains any questions requiring written responses, a **written (or
typeset) PDF document** submission is required (typeset instructions below).

- If contains any questions requiring coding responses, **the `submission.py`
file** must be uploaded and submitted to the autograder (local autograder
instructions below).

- Many of our problem sets will require both written (or typeset) AND coding
(submission.py) submissions. Good luck!


## Running the autograder locally
All assignment code is in the `src/` subirectory.  Please only make changes
between the lines containing `### START CODE HERE ###` and
`### END CODE HERE ###`.  All your code will be typed into either
`src/submission.py` or the files within the `src/submission/` subdirectory.

The unit tests in `src/grader.py` will be used to autograde your submission.
Run the autograder locally using the following terminal command within the
`src/` subdirectory:
```
(XCS_ENV) $ python grader.py
```

There are two types of unit tests used by our autograders:
- `basic`:  These unit tests will verify only that your code runs without
  errors on obvious test cases.

- `hidden`: These unit tests will verify that your code produces correct
  results on complex inputs and tricky corner cases.  In the student version of
  `src/grader.py`, only the setup and inputs to these unit tests are provided.
  When you run the autograder locally, these test cases will run, but the
  results will not be verified by the autograder.

For debugging purposes, a single unit test can be run locally.  For example, you
can run the test case `3a-0-basic` using the following terminal command within
the `src/` subdirectory:
```
(XCS_ENV) $ python grader.py 3a-0-basic
```
