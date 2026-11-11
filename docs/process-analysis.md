# QuickService Delivery — Order Management Process Analysis

**Author:** Rodrigo Garza García  
**Project:** Business Process Mapping  
**Tool:** Lucidchart  
**Repository:** [business-process-mapping-quickservice-delivery](https://github.com/rogarzag/business-process-mapping-quickservice-delivery)

## 1. Project overview

This case study maps the order management process of QuickService Delivery, a customer service company specializing in food and grocery delivery. The objective is to visualize the workflow from order placement to final fulfillment, clarify responsibilities across departments, and identify decision points that influence process execution.

## 2. Process scope and objective

The process begins when a customer submits an order and provides the required details. It covers order validation, payment, preparation, and fulfillment through customer pickup or home delivery.

The model focuses on the handoffs between five participants:

- **Customer**
- **Customer Service**
- **Sales**
- **Production**
- **Warehouse**

**Process start:** Customer places an order.  
**Process end:** Order is collected or delivered to the customer.

## 3. Process stages and responsibilities

| Stage | Responsible area | Key activities | Decision / control |
|---|---|---|---|
| 1. Order placement | Customer Service | Receive and record customer details, requested items and quantities, special instructions, and fulfillment preference. | Is the order complete? |
| 2. Payment process | Sales | Provide payment options, verify payment receipt, update payment status, and notify the customer. | Has payment been received? |
| 3. Order preparation | Production | Prepare the order according to customer requirements and check accuracy, completeness, and readiness. | Is the order ready for fulfillment? |
| 4. Delivery | Warehouse | Prepare the order for pickup or schedule and dispatch home delivery; notify the customer and confirm handover. | Pickup or home delivery? |

## 4. Key process components

| Component | Description | Application in this process |
|---|---|---|
| Participants | People or departments responsible for activities. | Customer, Customer Service, Sales, Production, and Warehouse. |
| Activities | Tasks performed to move the order forward. | Record order, verify payment, prepare items, and arrange fulfillment. |
| Decision points | Conditions that determine which path the process follows. | Order completeness, payment receipt, order readiness, and fulfillment method. |
| Sequence flows | Connections showing the order and direction of activities. | The flow from order placement through final handover. |
| Outputs | The result produced by a process stage. | Validated order, confirmed payment, prepared order, and completed fulfillment. |

## 5. Decision logic and modeling assumptions

- **Incomplete order:** Customer Service requests missing information and validates the order again.
- **Payment not received:** Sales follows up with the customer; after payment is submitted or retried, payment is verified again.
- **Order not ready:** Production completes the remaining preparation or resolves the issue before checking readiness again.
- **Fulfillment method:** The customer's pickup or home-delivery preference is captured during order placement and followed by Warehouse.
- **Process completion:** The workflow ends when the customer collects the order or receipt of the home delivery is confirmed.

**Modeling note:** The exception paths are explicit modeling assumptions added to make the workflow analyzable. The course scenario does not specify a payment cancellation policy or detailed exception-handling rules. The diagram therefore models follow-up and rechecking without assuming an unsupported cancellation process.

## 6. Original process flowchart

The following is the original flowchart exported from Lucidchart. It shows the sequence of activities, responsible participants, decision points, and exception paths from order placement through final fulfillment.

![Original QuickService Delivery flowchart](diagrams/QuickService%20Delivery%20%E2%80%93%20Order%20Management%20Process%20Flowchart.png)

[Open the interactive diagram in Lucidchart](https://lucid.app/lucidchart/36c1ae40-1a47-4819-805f-63889a5205e3/edit?viewport_loc=-957%2C873%2C2289%2C1675%2C0_0&invitationId=inv_33bdba97-f296-4e62-a267-c171659295b9)

## 7. Project files

- [Business Process Analysis — PDF](QuickService_Business_Process_Analysis_Rodrigo_Garza.pdf)
- [Original flowchart — PNG](../diagrams/QuickService%20Delivery%20%E2%80%93%20Order%20Management%20Process%20Flowchart.png)
- [GitHub repository](https://github.com/rogarzag/business-process-mapping-quickservice-delivery)

## 8. Author

**Rodrigo Garza García**  
[GitHub profile](https://github.com/rogarzag)
