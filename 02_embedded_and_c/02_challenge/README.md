# Challenge 2

## Task 1

Create an enum class representing the different states of a traffic light (red, yellow, and green). Write a function that takes a traffic light state as an argument and returns the duration of that state in seconds.

## Task 2

Create two abstract classes called `TemperatureSensor` and `PressureSensor`, each with a pure virtual function read() that returns a `temperature::kelvin` and `pressure::psi`, respectively. Derive `CPUTemperature`, `CabinTemperature`, and `TirePressure` from the appropriate base types. Implement the `read()` function for each derived class, simulating reading temperature and pressure values. Bonus points for using unit types instead of bare `double`s or `float`s.

## Task 3

Implement a templated function clamp that takes a minimum value, a maximum value, and a value to clamp. If the value is less than the minimum, return the minimum. If the value is greater than the maximum, return the maximum. Otherwise, return the value. Test the function with different types like int, float, and double.
