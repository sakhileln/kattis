# Kattis Practice Problems

A collection of practice solutions to problems from the [Kattis Problem Archive](https://open.kattis.com/), designed to help improve algorithmic and problem-solving skills.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project includes solutions to various algorithmic challenges and competitive programming problems sourced from Kattis, a popular platform for coding challenges. The problems cover a wide range of topics such as math, string manipulation, graphs, dynamic programming, and more.

The main goal of this repository is to track my progress and provide solutions to specific Kattis problems with a focus on clean, readable code and problem-solving techniques.

## Features
- A variety of problems categorized by difficulty and topic
- Well-commented code explaining the approach to solving each problem
- Use of efficient algorithms and data structures
- Solutions written in Python (or another language, depending on the problem)
- Readme-style explanations of the problem-solving approach for each challenge

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sakhileln/kattis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd kattis
   ```

3. (Optional) Set up a Python virtual environment to isolate dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install any required dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```

## Usage
After cloning the repository, each problem will have its own directory or Python script. To run a particular problem's solution, simply run the corresponding Python file:

```bash
python problem_name.py
```

You can also directly open the files and modify the code to test different inputs or try out alternative approaches.

### Example Usage
1. For example, for a problem like **"Time to Eat"**:
   ```bash
   python time_to_eat.py
   ```

2. For a problem like **"Taxicab Geometry"**:
   ```bash
   python taxicab_geometry.py
   ```

## Contributing

Contributions are welcome! If you'd like to add more solutions, improve existing code, or suggest new problems, feel free to fork the repository and submit a pull request.

Steps to contribute:
1. Fork the repository
2. Create a new branch for your changes:
   ```bash
   git checkout -b feature/add-solution
   ```
3. Commit your changes:
   ```bash
   git commit -m "Solve 'Taxicab Geometry' problem"
   ```
4. Push your changes:
   ```bash
   git push origin feature/add-solution
   ```
5. Open a pull request on GitHub.

---

## Example Problem Explanation Format

### Problem: Time to Eat

#### Problem Statement:
This problem involves calculating the time it takes for an individual to reach a certain point based on speed and distance. The input includes the individual's speed in meters per second and the distance to their destination in meters.

#### Approach:
1. Parse the input to retrieve speed and distance values.
2. Use the formula `time = distance / speed` to calculate the time required.
3. Output the result with appropriate formatting.

#### Solution Code:
```python
def time_to_eat(speed, distance):
    return distance / speed

if __name__ == "__main__":
    speed = float(input())  # Speed in meters per second
    distance = float(input())  # Distance in meters
    print(f"{time_to_eat(speed, distance):.2f}")
```

---

## Contact
- Sakhile III  
- [LinkedIn Profile](https://www.linkedin.com/in/sakhile-ndlazi)
- [GitHub Profile](https://github.com/sakhileln)
