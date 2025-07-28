# Reverse Engineering of Microsoft Calculator

## Project Overview
This documentation summarizes the core logic of Microsoft's open-source calculator, focusing on the `CalcManager` component.

## Key Files Analyzed
- **CalcManager.h**: Header file declaring the CalcManager class and calculation functions.
- **CalcManager.cpp**: Implements functions for managing calculations, memory, and state.

## Key Functions
- `void CalcManager::Initialize()`: Initializes the calculator engine.
- `void CalcManager::ProcessCommand(Command command)`: Processes a user command (e.g., number input, operator).
- `wstring CalcManager::GetDisplayString()`: Returns the current number/result for display.

## Understanding
- The calculator uses **C++ with COM interfaces**.
- Calculations are processed via a command pattern and state management.
- The code is modular and well-commented.

