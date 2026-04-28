# Quantity Measurement App

This is a small Java project that compares length values across different units. It currently supports feet, inches, yards, and centimeters, and treats two values as equal when they convert to the same base unit.

## What it does

- Compares length values across supported units.
- Converts each unit to feet internally before checking equality.
- Demonstrates the behavior in a simple `main` method.
- Includes JUnit 5 tests for the supported conversions and equality checks.

## Project Structure

- `src/main/QuantityMeasurementApp.java` - application code and demo entry point.
- `src/test/QuantityMeasurementAppTest.java` - unit tests.

## Supported Units

- Feet
- Inches
- Yards
- Centimeters

## Running the App

The project does not currently include Maven or Gradle files, so you can run it from your IDE or compile it manually.

To run the demo from the command line, compile the main class and execute it from the output directory.

## Running Tests

The tests use JUnit 5. If you want to run them from the command line, add your preferred Java build tool or configure JUnit in your IDE.

## Example Output

Running the demo prints whether these comparisons are equal:

- 1 foot == 12 inches
- 1 yard == 3 feet
- 30.48 cm == 1 foot

## Notes

- The current implementation compares lengths only.
- A null unit is not allowed when creating a length value.