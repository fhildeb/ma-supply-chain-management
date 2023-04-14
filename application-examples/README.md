# Application Examples

This project contains several self-built examples to represent process chains of different situations. Some of these were further developed in independent projects of this repository.

### Machine Flow Basics

A production model classifies incoming goods into different parts using various random methods and sends them to separate machines if they are not already working to capacity. The goods are temporarily stored until they are checked for quality by a control authority and sent to the goods issue department.

![](/img/application-examples-1.png)

### Warehouse Coordination

This simulation is an extension of the basic machine flow model, which now does not automatically deliver products to the machines. Yet, it implements an information center that two operators can read. The operators have precise work paths which they can follow and transport the raw materials and finished products back and forth between the receiving area, the machine, the control station, and the warehouse. When transporting the goods from the final pickup point to the warehouse, another information center is used, which is read by forklift drivers. They efficiently transport a load of finished products to the warehouse.

![](/img/application-examples-2.1.png)
![](/img/application-examples-2.2.png)

### Registration Office

This simulation project recreates a registration office in which only a certain number of people are allowed to be in the waiting area and are then forwarded to different offices. There are three different office types in different quantities. Customers can either come through the office or are sent away again when the workload is high.

![](/img/application-examples-3.1.png)
![](/img/application-examples-3.2.png)

### Dining Hall Crowd Management

This program recreates a cafeteria. People are divided into different tastes at the entrance. They then pick a suitable food and dessert outlet and pay for their goods at the checkout before walking into the canteen. Afterward, they must hand in their dishes in the queue and leave the building.

![](/img/application-examples-4.1.png)
![](/img/application-examples-4.2.png)

### Item Push and Pull Flows

Another example of pull and push flows applies the same concept used in dining crowd management. Here, goods are checked out differently, have to be stored for a specific time, will be pulled out of the warehouse, and can be sent to the output with a queue.

![](/img/application-examples-5.1.png)
![](/img/application-examples-5.2.png)

### Doctors Office Dispatch

This simulation deals with waiting and treatment in a doctor's office. People have to register at the reception, are assigned to a group and the appropriate doctor according to their symptoms, and are then taken to the continuing waiting room until the doctor's room becomes free. After a varying treatment time, people arrive at a standard exit.

![](/img/application-examples-6.png)
