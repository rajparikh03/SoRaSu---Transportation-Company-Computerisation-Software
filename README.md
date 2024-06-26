
# SoRaSu-TCCS

SoRaSu is a Transportation Company Computerization Software (TCCS) designed as a web-based application. The frontend is built with HTML, CSS, and JavaScript, while the backend utilizes Flask, SQLite, the Here Routing API, and SmtpJS.

The TCCS aims to assist transportation companies in digitizing various bookkeeping activities related to their operations. These companies handle consignments of varying sizes (measured in cubic meters) at their offices, which are then forwarded to different branches across the country.

System Overview
When a consignment arrives at a transport company's office, its details (volume, destination address, sender address, etc.) are entered into the system. The system calculates the transport charge based on the consignment's volume and destination, and then generates a bill.

Once the total volume of consignments for a specific destination reaches 500 cubic meters, the system automatically assigns the next available truck. Trucks remain at the branch office until there is enough cargo to fully load them.

Managers can monitor the status of different trucks at any time and view truck usage statistics over a specified period.

When a truck is ready and the required consignment volume is available for dispatch, the system prints details such as consignment number, volume, sender's name and address, and receiver’s name and address, which accompany the truck.

Managers can query the status of any consignment, check the volume of consignments handled for any destination, and view the corresponding revenue generated. They can also track truck availability, waiting periods, and idle times.

Product Functions:
Manager :
The manager will be responsible for the following use cases :-
1. Buying new trucks
2. Viewing Consignment Status
3. Viewing Truck Status
4. Viewing Average Waiting Time of Consignment
5. Viewing Average Truck Idle Time
6. Viewing Truck Usage
7. Viewing Branch Consignment Handling
8. Viewing live location status of the trucks

Employees :
The employees will be associated with the following use cases :-
1. Dispatching Truck
2. Validating consignment
3. Receiving Truck
4. Viewing live location of the trucks and route to destination 

Customer :
The customer will be associated with the following use cases :-
1. View truck and route details
2. Place order
3. Viewing order history
4. Viewing auto generated invoice




## Installation
- Clone this repository-Move to your workspace directory and clone this repository
```bash
git clone https://github.com/SoRaSu-SWE23/SoRaSu.git
```
- Install dependencies-
Move to the cloned repository directory and run
```bash
pip install -r requirements.txt
```

    
## Getting Started

```bash
python3 run.py
```

## Authors

- Raj Parikh
- Soukhin Nayek 
- Sukhomay Patra

