# python-activity-based-learing-7
Algorithm
1.Start.
2.Enter passenger demand and bus capacity for each route.
3.Calculate the number of buses required.
4.Calculate unserved passengers.
5.Display buses needed and unserved passengers.
6.Stop.
flowchart
Start
Enter demand and bus capacity
Calculate buses required
Find unserved passengers
Display results
Stop
demand = [100, 75, 130]
capacity = 50

for passengers in demand:
    buses = (passengers + capacity - 1) // capacity
    served = buses * capacity
    unserved = max(0, passengers - served)

    print("Passengers:", passengers)
    print("Buses needed:", buses)
    print("Unserved:", unserved)
Passengers: 100
Buses needed: 2
Unserved: 0
Passengers: 75
Buses needed: 2
Unserved: 0
Passengers: 130
Buses needed: 3
Unserved: 0


    





