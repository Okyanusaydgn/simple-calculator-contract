# Simple Calculator Contract

## Project Idea
I want to build a Stacks blockchain project called **"Simple Calculator Contract"**.

## Project Description
This project is a minimal, beginner-friendly Clarity smart contract that allows users to perform basic arithmetic operations (addition, subtraction, multiplication, division) on-chain.  
The contract stores the **latest result per user** and exposes read functions so that users can retrieve their last calculation.  
Division is safe and handles division by zero errors gracefully.  

This project will help demonstrate my understanding of:  
- Clarity smart contract development  
- Read-only and public functions  
- Basic error handling  
- On-chain storage per user  

## Key Features
- Add, subtract, multiply, and divide two numbers  
- Store and retrieve the last result for each user  
- Safe division (division by zero returns an error)  
- Clear and simple documentation for each function  

## Tests (Planned)
- Unit tests for each arithmetic function  
- Edge cases (division by zero, negative numbers, large values)  
- Multiple users storing separate results  

## Security Considerations
- Prevent division by zero  
- Notes on integer bounds and gas usage  
