# MechanicShop

The purpose of this model–view–controller design pattern is to build a large part of C++ object oriented program that emplyees will be able to add or remove customers and add or remove vehicles to Auto Mechanic management system Information   

- How to Run
1) make clean
  > Output
  - rm -f main.o ShopController.o View.o VehicleFactory.o Shop.o Customer.o Vehicle.o
Car.o Truck.o Motorcycle.o Mechanic.o Person.o mechanicshop

2) make
  > Output
  g++ -c main.cc
  g++ -c ShopController.cc
  g++ -c View.cc
  g++ -c VehicleFactory.cc
  g++ -c Shop.cc
  g++ -c Customer.cc
  g++ -c Vehicle.cc
  g++ -c Car.cc
  g++ -c Truck.cc
  g++ -c Motorcycle.cc
  g++ -c Mechanic.cc
  g++ -c Person.cc
  g++ -o mechanicshop main.o ShopController.o View.o VehicleFactory.o Shop.o Customer.o
  Vehicle.o Car.o Truck.o Motorcycle.o Mechanic.o Person.o

  3) ./mechanicshop
  > Output
  **** Toby's Auto Mechanic Information Management System ****
MAIN MENU
1. Print Customer Database
2. Add Customer
3. Add Vehicle
4. Remove Customer
5. Remove Vehicle
6. Print Mechanics
0. Exit
Enter your selection: 3
Customer ID: 1002
Vehicle Type (1: Car, 2: Truck, 3: Motorcycle): 3
Make: Suzuki
Model: Cruiser
Colour: Black
Year: 2000
Mileage: 50000
Has sidecar (y/n): y
Press enter to continue...
**** Toby's Auto Mechanic Information Management System ****
MAIN MENU
1. Print Customer Database
2. Add Customer
3. Add Vehicle
4. Remove Customer
5. Remove Vehicle
6. Print Mechanics
0. Exit
Enter your selection: 1
CUSTOMERS:
Customer ID 1001
