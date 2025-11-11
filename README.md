# README for Username Validation Script

## Author Information
- **Name:** [Thien Scofield]
- **Course:** [CPSC298]
- **Assignment:** Maxscore Assignment
- **Date:** [11-10-2025]

## Program Description
[Write 2-3 sentences in your own words describing what this script does and its purpose. Explain the problem it solves and how it works at a high level.]

The script reads 5 positive integer values from the user. It then identifies the largest integer in the array and compares the difference between it and the other integers.


## Usage
To run the script interactively:
```bash
./maxscore.sh
```

To test with the provided input file:
```bash
./maxscore.sh < maxscore-input
```

## How the Script Works
[Explain in 3-5 sentences how your script works. Include information about:]
- How you read and store numbers in an array
- How you loop through the array to find the maximum value
- How you calculate and display the difference between each score and the highest

The first for loop reads the user's input 5 different times and stores them in the "score" array. Then the next for loop sets the variable max to the largest number in the array by comparing each of the numbers. The echo statement prints the largest variable, and the next for loop subtracts each of the values from the max value and prints the difference.

## Testing Results
[Describe your testing process and results. Include:]
- Example successful inputs and results
- How you used the maxscore-input file to test

The results went as expected, with the order of integers not mattering. The maxscore-input values worked as well.

## Challenges and Solutions
[Optional: Describe any challenges you encountered while creating this script and how you solved them. This could include debugging issues, arrays, or Git workflow problems.]

## Resources
[List any resources you used (class slides, ChatGPT, etc.). Please refer to the course syllabus for more details on citations.]
Tony & Moises

## License
This project is part of coursework for Chapman University and is intended for educational purposes.
