# Vehicle Rental Management System – README

## Project Title
Vehicle Rental Management System using C

## Description
This is a simple C program developed to manage vehicle rentals.
The program allows users to:

- Select vehicle type (Bike or Car)
- Choose a vehicle model
- Rent based on hours or days
- Calculate total rental amount
- Add damage fine if the vehicle is damaged

The program uses:
- Structures (struct)
- Arrays
- Conditional statements
- Loops
- User input/output functions

## Features
- Bike and Car rental system
- Multiple vehicle models
- Hourly and daily rental calculation
- Damage fine calculation
- Simple console-based interface

## Technologies Used
Programming Language: C
Compiler: GCC / Turbo C / CodeBlocks / VS Code

## Vehicle Details

Bikes:
1. Honda Shine
   Per Hour: 50
   Per Day: 300
   Damage Fine: 500

2. TVS Apache
   Per Hour: 80
   Per Day: 500
   Damage Fine: 700

3. Royal Enfield
   Per Hour: 120
   Per Day: 700
   Damage Fine: 1000

Cars:
1. Maruti Alto
   Per Hour: 150
   Per Day: 1000
   Damage Fine: 2000

2. Hyundai i20
   Per Hour: 200
   Per Day: 1500
   Damage Fine: 2500

3. Mahindra Thar
   Per Hour: 400
   Per Day: 2500
   Damage Fine: 4000

## How the Program Works
1. User selects vehicle type.
2. Program displays available vehicles.
3. User selects a vehicle model.
4. User chooses rent type:
   - Per Hour
   - Per Day
5. User enters rental duration.
6. Program calculates rental amount.
7. Damage fine is added if applicable.
8. Final rental amount is displayed.

## Sample Output

----- VEHICLE RENTAL MANAGEMENT SYSTEM -----

1. Bike
2. Car
Choose Vehicle Type: 1

--- Available Bikes ---
1. Honda Shine
2. TVS Apache
3. Royal Enfield

Choose Bike Model: 2

1. Rent Per Hour
2. Rent Per Day
Choose Rent Type: 1

Enter Hours/Days: 5

Is the vehicle damaged? (1-Yes / 0-No): 0

------------------------------
TOTAL RENTAL AMOUNT = 400
------------------------------

## Concepts Used in This Program
- Structures in C
- Arrays of Structures
- Conditional Statements (if-else)
- Loops (for)
- printf() and scanf() functions

## Conclusion
This project helps in understanding basic concepts of C programming and demonstrates how a vehicle rental system can be implemented using structures and conditional logic.
