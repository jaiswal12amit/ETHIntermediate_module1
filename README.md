# Attendance Management Smart Contract

This repository contains a Solidity smart contract for managing student attendance and awarding bonus marks based on attendance percentages.

## Features

- **Record Attendance**: Allows the owner to record the number of classes attended by each student.
- **Check Eligibility**: Determines if a student is eligible for exams based on their attendance percentage.
- **Award Bonus Marks**: Provides bonus marks to students who meet or exceed a specified attendance percentage threshold.
- **Owner Restricted Functions**: Critical functions are restricted to the contract owner to maintain control and security.

## Requirements

- **Solidity Compiler**: This contract is written in Solidity version ^0.8.0.
- **Ethereum Development Environment**: Use tools like Remix, Hardhat, Truffle, or similar to compile and deploy the contract.

## Setup

1. Clone the repository.

2. Navigate to the project directory.

3. Compile the smart contract using your preferred Solidity development environment.

## Usage

### Deploying the Contract

- Deploy the `AttendanceManagement` contract to an Ethereum blockchain of your choice.

### Interacting with the Contract

- **Record Attendance**: Call `recordAttendance(address student, uint256 classesAttended, uint256 total)` to record attendance for a student.
- **Check Eligibility**: Call `checkEligibility(address student)` to check if a student is eligible for exams based on their attendance.
- **Award Bonus Marks**: Call `awardBonusMarks(address student)` to award bonus marks to students who meet or exceed the attendance threshold.
- **Owner Functions**: Functions like `setBonusMarksThreshold(uint256 threshold)` and `setBonusMarks(uint256 marks)` allow the owner to configure bonus marks thresholds and amounts.

## Contributing

Contributions to improve and extend the functionality of this smart contract are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
