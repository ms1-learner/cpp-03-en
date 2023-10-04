# Challenge 3

## Task 1

Create a class DataProcessor that takes a pointer to a Sensor as its constructor argument. Implement a method processData() in DataProcessor that reads data from the sensor, processes it (e.g., by multiplying it by a constant), and returns the result. Use a smart pointer (std::unique_ptr) to manage the lifetime of the Sensor objects.

## Task 2

Write a constant representing the number pi using constexpr. Then write a consteval function that computes the circumference of a circle of a given radius that uses this pi constant. Use a tool like [godbolt.org](https://godbolt.org/) to observe what the compiled code looks like.
