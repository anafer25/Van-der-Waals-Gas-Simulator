# Van-der-Waals-Gas-Simulator

This project demonstrates a Python implementation of the **Van der Waals equation of state** for gases.

The program calculates the **pressure of a gas as a function of volume** at a fixed temperature and number of moles, using Van der Waals constants. For example, it models **oxygen gas** with its specific constants and plots the resulting pressure-volume relationship.

## Features
- **Object-Oriented Design**: Implements a `Gas` class and separate utility classes for calculations and graphing.
- **Van der Waals Calculations**: Computes pressure from volume, temperature, and moles using the Van der Waals equation.
- **Flexible Plotting**: Plots pressure vs. volume using Matplotlib with customizable labels, colors, and titles.
- **Handles Edge Cases**: Volumes smaller than the gas’s `b` constant are skipped to avoid unphysical results.

## Classes
- **Gas**: Stores Van der Waals constants `a` and `b` as private variables and provides getter methods.
- **VanDerWaalsCalculator**: Provides a static method `calculate_pressure()` to compute pressures over a volume range for a given gas, temperature, and number of moles.
- **GraphRoutines**: Provides a static method `plot_pressure_volume()` to generate pressure vs. volume plots.
