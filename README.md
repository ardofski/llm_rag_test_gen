### RAG Powered LLM Approach for Automatic Unit Test Generation from Bug Reports Across Focal Levels

This repository contains the surce code for test generation based on bug reports.

Project uses defects4j as dataset and automation of executing generated test cases. You can find the docker file for evaluating the experiments in:


https://drive.google.com/file/d/1eFfKoK9YbIaG5Ye2M9XPAdYY8p1ZxqMu/view?usp=sharing

1 - Build the docker file in the given link

2 - Copy the buggy and fixed version of codes in docker file to local filesystem

3 - Using generate_test_cases_gemini.ipynb, create test case for each reported bug

4 - change directory to buggy and fixed version ```defects4j test``` to experiment updated tests.
