# Process Flow Models

This project focuses on developing a simulation model of a customer service center, aiming to optimize its efficiency. The model features a process flow with interconnected activities that represent different stages of the customer service process.

## Process Flow Model

> File: `process-flow-model.fsm`

The model provides a 3D representation of the customer service center. The simulation includes customers arriving at the center, lining up at the service desk, and being helped by customer service representatives, while taking into account customer waiting lists.

Objects are added to the 3D model to represent various elements, such as flow items for customers, fixed resources for the service desk and waiting line, and a global list to track waiting customers. A global list then tracks the wait time of each customer in the line. The service desk prioritizes customers who have been waiting the longest, while customers waiting for more than 200 seconds leave through the Unhappy Customers sink.

The model features a dashboard that displays real-time data through various charts, enabling users to analyze and address key performance indicators. The dashboard consists of charts that answer essential questions, such as the length of the waiting line, the average wait time for customers, the number of satisfied and unsatisfied customers, and the service desk's utilization rate.

It also visualizes staytime data, charts of the total number of customers leaving the system, and a state chart displaying service desk utilization. Through real-time updates and the ability to analyze collected data, users can identify potential issues in the customer service center and experiment with solutions, such as adding more service desks to balance customer satisfaction and idle time.

### Process Flow Activities

The project also features a process flow tool running independently of the 3D model, offering a more abstract and theoretical approach to simulation. The model contains a resource activity representing the service desk employee, a source activity for customer arrivals, acquire and release activities to simulate waiting times and service completion, and sink activities to track happy and unhappy customers. By adjusting the number of service desks and employees, the optimal configuration to meet customer demand and improve the system's overall performance can be explored.

## Model Linking

> File: `model-linking.fsm`

By linking the process flow tool with the 3D model, the simulation's capabilities are enhanced by combining the strengths of both tools. Labels are created to connect tokens in the process flow to objects in the 3D model, allowing the process flow to control the overall logic.

Within the model linking, the old 3D model logic is removed, ensuring seamless integration with the process flow tool. In Addition of new objects, such as service desks, workers, and visual elements, to improve the model's realism and functionality. Containers are used to organize the process flow for clarity. The updated version also includes the implementation of coordination activities, such as Split and Synchronize, to manage concurrent processes and synchronize tasks. Customer arrival, service, and exit logics are also modified to accurately reflect real-life scenarios and behaviors.
