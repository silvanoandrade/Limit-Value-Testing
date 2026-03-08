QA Project – Limit Value Testing

Project Description

This project documents the Quality Assurance (QA) testing process carried out during the third sprint. The focus of this project was to validate system input fields by applying a limit value testing approach, focusing on how the system behaves when input values are at or near the allowed limits.
Testing around limits is important because many defects occur when the system processes values that are very close to the minimum or maximum allowed values. The goal of this project was to ensure that the application correctly handles minimum limits, maximum limits, and values outside the valid range.

Testing Objectives

Verify that the system correctly validates input limits.
Ensure minimum and maximum constraints are properly enforced.
Identify potential defects that occur when values approach system limits.
Confirm that the system rejects values outside the allowed range.

Testing Scope

The tests focused on input fields that include defined limits or restrictions, such as:
Minimum allowed value
Maximum allowed value
Values slightly below the minimum limit
Values slightly above the maximum limit
These tests help confirm that the system handles edge situations around limits correctly and prevents invalid data from being accepted.

Testing Approach

Limit Value Testing
Limit value testing is a black-box testing approach used to verify how a system behaves when values are close to the defined limits of an input field.
Instead of testing every possible input value, the testing focuses on critical points around the limits, such as:
The minimum allowed value
The maximum allowed value
A value just below the minimum limit
A value just above the maximum limit
A valid value within the range
This method helps detect issues that commonly occur when systems process values near their limits.

Test Case Design

The test cases were created based on the defined limits and include the following elements:

Test Case ID
Test Scenario
Input Value
Limit Condition
Steps to Execute
Expected Result
Test Status

Each test verifies how the system behaves when values are within the allowed limits or outside the valid range.

Example Test Scenarios

Some of the scenarios tested include:

Entering the minimum allowed value.
Entering the maximum allowed value.
Entering a value just below the minimum limit.
Entering a value just above the maximum limit.
Entering a valid value within the accepted range.

These scenarios help verify that the system properly validates user input and enforces the defined limits.
  

QA Process Applied

Analysis of system requirements and input constraints.
Identification of minimum and maximum limits.
Definition of values around those limits.
Design of test cases based on limit conditions.
Documentation of test scenarios and results.

Results

Testing around system limits helped identify potential issues related to input validation and range restrictions.

This approach improves system reliability by ensuring that the application correctly processes values at the limits and rejects values outside the allowed range.
