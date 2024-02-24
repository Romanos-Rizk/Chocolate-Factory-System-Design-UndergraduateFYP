# System Design Project

## Table of Content

- [Project and Company Overview](#Project-and-Company-Overview)
- [System Functions](#System-Functions)
- [System Limitations](#System-Limitations)
- [System Functional Requirementss](#System-Functional-Requirements)
- [Non-Functional Requirements](#Non-Functional-Requirements)
- [Unified Modeling Language System Designs](#Unified-Modeling-Language-System-Design)

## Project and Company Overview:

This report provides an overall description of Le Chateau Du Chocolat Sarl's chocolate factory system. It includes system requirements, functions, characteristics of users, and constraints to keep in mind while developing the system. The report also discusses specific requirements of each department and function, including both functional and non-functional aspects.

Le Chateau Du Chocolat Sarl's chocolate production process involves importing high-quality cocoa beans and creating chocolate from scratch, from distilling the cocoa from the cocoa butter to creating the finished product. Part of the chocolate is made into blocks for other factories to melt and alter, while the rest is made into chocolate bars under specific client requests. The owner designs the flavors, creates the chocolate, lets the client test them, and after approval, produces batches of the chocolate and packages them without his brand name.

The company operates under a B2B and B2C model, producing its own recipes and chocolate bars, selling them directly to consumers with their logo on them. During the COVID-19 pandemic, business was slow, so the owner built a fully equipped kitchen in his factory and hired pastry chefs to make high-quality brownies, fondant, and sable, using the high-quality chocolate that the factory produces. These products can also be sold under a B2B or B2C model and are professionally packaged and freezer ready.

## System Functions:

-	Take orders from clients through the system: The company's system allows clients to place orders for chocolate products, either for B2B or B2C purposes. The orders can be received through the system, which ensures a streamlined and organized process.

-	Send approval/rejection to order: Once an order is received, the system is used to approve or reject it based on various factors such as availability of ingredients, production capacity, and delivery schedules.

-	Gather client information: The system allows for the collection and storage of client information such as contact details, delivery preferences, and order history for future reference and improved customer service.

-	Store invoices and receipts in a financial database: The system is used to store invoices and receipts, ensuring accurate financial records and facilitating financial management.

-	Track inventory to General Manager: The system is used to convey inventory information to the General Manager, providing an overview of the stock levels and facilitating inventory management.

-	Track list of available suppliers to General Manager to make raw material orders: The system allows for the conveyance of the list of available suppliers to the General Manager for efficient raw material sourcing.

-	Keep General Manager up to date on Cocoa (raw material) orders: The system is used to keep the General Manager informed on raw material orders and deliveries, ensuring smooth production processes.

-	Inform Secretary and Delivery Workers when product is ready for delivery/pickup: The system is used to inform the Secretary and Delivery Workers when the products are ready for delivery or pickup, ensuring efficient and timely delivery of the products to clients.

-	Inform Client on pickup details and/or delivery request details & status: The system is used to inform the client of the pickup and delivery details, keeping them up to date on the status of their orders.

## System Limitations:

The system had some limitations due to the lack of resources like money and time, as well as the poor economic situation in the country. One limitation was that it was designed only for local or domestic use and could not accommodate the needs of foreign clients and companies, such as dealing with currency exchange, international logistics and delivery, and unique products. Another limitation was that customers could not track their shipments.

Furthermore, there was no provision in the system to notify customers of new products and offers, despite their contact information being part of the client data structure.

## System Functional Requirements:

### Sales B2B Process:

1. The customer can order at any time.
2. The customer fills an order request and sends it to the manager.
3. The manager evaluates the order request; the order request can be approved/rejected based on the quantity and time of delivery.
4. The manager translates the order request into a manufacturing request for internal use.
5. Manufacturing department start production when they receive the manufacturing request from the manager.
6. When the manufacturing department completes the production, store the completion status.
7. The completion status is stored in the database, and the manager can access the database.
8. The order will be stored in the storage facility.
9. Delivery and pick-up dates are set by the client.
10. The administrator sends a reminder to the client for delivery.
11. When the client replies, the administrator sends delivery information to the delivery department.
12. The delivery department delivers the order to the client.

### Sales B2C Process:

1. The customer can order at any time through the website.
2. The order is transferred to the manufacturing department.
3. The manufacturing department fulfills the order.
4. When the manufacturing department completes the production, they store the completion status.
5. The completion status is stored in the database, and the administrator can access the database.
6. The order will be stored in the storage facility.
7. The administrator sends delivery information to the delivery department.
8. The delivery department delivers the order to the client.

### Supplier Raw Material Process:

1. The raw materials are ordered from the supplier only if inventory is missing for production.
2. The manager sends a supplier request form to suppliers.
3. The supplier sends offers to the manager.
4. The manager evaluates the offer.
5. The manager orders the desired offer.
6. The supplier sends the raw materials to the manufacturing department.

### Accounting Process:

1. The customer receives the order.
2. The accounting department generates the invoice.
3. The invoice is stored in the database.
4. The administrator sends the invoice to the customer.
5. The customer receives and pays the invoice.
6. The administrator validates the payment and stores it in the database.
7. The accounting department updates the ledger account according to the stored payments in the database.

## Non-Functional Requirements:

a. **Security:** The system should be designed to protect sensitive information from unauthorized access or manipulation.
b. **Performance:** The system should be able to handle a high volume of requests and provide quick response times to ensure a smooth user experience.
c. **Availability:** The system should be available for use 24/7 with minimal downtime for maintenance or upgrades.
d. **Scalability:** The system should be able to handle an increasing number of users and data without impacting performance or functionality.
e. **Usability:** The system should be easy to use, intuitive, and provide clear instructions for users with varying levels of technical expertise.
f. **Reliability:** The system should be reliable and operate without errors or unexpected downtime.
g. **Maintainability:** The system should be designed with ease of maintenance and updates in mind to minimize the need for significant downtime or development effort.
h. **Compatibility:** The system should be compatible with commonly used browsers and devices to ensure accessibility for a broad user base.
i. **Accessibility:** The system should be accessible for users with disabilities, conforming to relevant accessibility guidelines and standards.
j. **Compliance:** The system should comply with relevant laws, regulations, and industry standards.

## Unified Modeling Language System Design:

**Available in the project's report**

