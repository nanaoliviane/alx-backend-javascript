# 0x02. ES6 Classes

## Description
This project is focused on learning and implementing object-oriented programming in JavaScript using ES6 classes. The tasks cover creating classes, adding methods, using static methods, inheritance, and metaprogramming with symbols.

## Learning Objectives
- Understand and use ES6 classes.
- Implement instance and static methods.
- Use inheritance to extend classes.
- Utilize getter and setter methods.
- Overload methods for type conversion.
- Work with classes and objects in a structured manner.

## Project Tasks

### 0. **ClassRoom**
- **File:** `0-classroom.js`
- **Description:** Create a `ClassRoom` class that takes `maxStudentsSize` as a constructor argument.

### 1. **Initialize Classrooms**
- **File:** `1-make_classrooms.js`
- **Description:** Create a function `initializeRooms` that returns an array of 3 `ClassRoom` objects with sizes 19, 20, and 34.

### 2. **HolbertonCourse**
- **File:** `2-hbtn_course.js`
- **Description:** Create a `HolbertonCourse` class with properties `name`, `length`, and `students`. Add getters and setters with validation for each property.

### 3. **Currency**
- **File:** `3-currency.js`
- **Description:** Create a `Currency` class that has properties `code` and `name`. Include a method `displayFullCurrency` that returns the currency name and code.

### 4. **Pricing**
- **File:** `4-pricing.js`
- **Description:** Create a `Pricing` class with `amount` and `currency` properties. Add a method `displayFullPrice` and a static method `convertPrice`.

### 5. **Building**
- **File:** `5-building.js`
- **Description:** Create a `Building` class with a `sqft` property. Include an abstract method `evacuationWarningMessage` that must be implemented by any subclass.

### 6. **SkyHighBuilding**
- **File:** `6-sky_high.js`
- **Description:** Create a `SkyHighBuilding` class that extends `Building`. Add a `floors` property and implement the `evacuationWarningMessage` method.

### 7. **Airport**
- **File:** `7-airport.js`
- **Description:** Create an `Airport` class with properties `name` and `code`. Override the `toString` method to return `[object code]`.

### 8. **HolbertonClass**
- **File:** `8-hbtn_class.js`
- **Description:** Create a `HolbertonClass` class with `size` and `location` properties. Override the `valueOf` and `toString` methods.

### 9. **Hoisting**
- **File:** `9-hoisting.js`
- **Description:** Create two classes, `HolbertonClass` and `StudentHolberton`. Ensure that `StudentHolberton` references an instance of `HolbertonClass`.

### 10. **Car**
- **File:** `10-car.js`
- **Description:** Create a `Car` class with `brand`, `motor`, and `color` properties. Add a method `cloneCar` that returns a new object of the same class.

## Setup Instructions

### Prerequisites
- **Node.js 12.11.x** or later
- **npm** or **yarn**

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/0x02-ES6-classes.git
    cd 0x02-ES6-classes
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

### Running Tests
To run the tests using Jest, execute the following command:
```bash
npm test

