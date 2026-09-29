# Run Guide: Library Loan Demo

## Prerequisites

- JDK 17 or later (both `java` and `javac` must be available in the terminal)
- Python 3.9 or later (the runner uses only Python's standard library)
- No IDE, Maven, Gradle, or third-party Java dependency is needed

## Run the demo

From the repository root:

    python3 run.py demo

On Windows, if Python is available as `py -3`, use `py -3 run.py demo` instead.

## What the demo does

The demo runs a small library loan scenario with a fixed date (2026-09-01):

- It prints the borrowing limits for students and faculty.
- It searches the catalog for a title.
- It lends the book "Git Essentials" to a member named Alex and shows the due date (14 days later).
- It returns the book, shows the return fee, and confirms that no loans remain active.