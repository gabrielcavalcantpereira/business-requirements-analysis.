
# Business Requirements Analysis

## 1. Project Overview

This project presents a simulated business requirements analysis for a fictional retail company seeking to improve its operational processes through an Enterprise Resource Planning (ERP) system.

The analysis focuses on identifying business needs, documenting functional and non-functional requirements, mapping business processes and defining acceptance criteria.

The objective is to demonstrate how business requirements can be translated into structured system specifications.

## 2. Business Case

### Company Scenario

A fictional retail company manages its sales, purchases and inventory through spreadsheets and manual processes.

As the business grows, several operational challenges emerge:

- Lack of centralized information.
- Difficulty tracking inventory levels.
- Manual errors in product and order records.
- Delays in purchase management.
- Limited visibility into business operations.

The company needs an integrated ERP solution to improve efficiency, accuracy and information management.

## 3. Project Objectives

- Identify operational problems and business needs.
- Analyze and document business requirements.
- Define functional and non-functional requirements.
- Map essential business processes.
- Create user stories and acceptance criteria.
- Propose an ERP-based solution.

## 4. Scope of the Project

The proposed ERP solution covers three main business areas:

| Module | Main Functions |
|---|---|
| Sales | Customer registration and order management |
| Inventory | Product registration and stock control |
| Purchasing | Supplier registration and purchase orders |

## 5. Functional Requirements

| ID | Requirement | Description |
|---|---|---|
| FR-01 | Customer Management | The system must allow users to register and manage customers. |
| FR-02 | Product Management | The system must allow users to register and update products. |
| FR-03 | Sales Management | The system must allow users to create and track sales orders. |
| FR-04 | Inventory Control | The system must update stock quantities after confirmed transactions. |
| FR-05 | Purchase Management | The system must allow users to create and manage purchase orders. |
| FR-06 | Reporting | The system must generate basic sales and inventory reports. |

## 6. Non-Functional Requirements

| ID | Requirement | Description |
|---|---|---|
| NFR-01 | Usability | The system should provide an intuitive user interface. |
| NFR-02 | Security | Access to sensitive information must be restricted by user permissions. |
| NFR-03 | Reliability | The system should maintain data consistency. |
| NFR-04 | Performance | Common operations should be completed within an acceptable response time. |
| NFR-05 | Data Integrity | Business records must remain accurate and consistent. |

## 7. User Stories

**US-01: Customer Registration**

As a sales employee, I want to register customers so that I can manage customer information and create sales orders.

**US-02: Inventory Monitoring**

As an inventory manager, I want to monitor product quantities so that I can avoid stock shortages.

**US-03: Purchase Management**

As a purchasing employee, I want to create purchase orders so that I can replenish inventory when necessary.

**US-04: Business Reporting**

As a business manager, I want to access sales and inventory reports so that I can make informed business decisions.

## 8. Acceptance Criteria

### US-02: Inventory Monitoring

-US-01: Product Registration

Given that the inventory employee has access to the ERP system,

When they register a new product with all required information,

Then the system must save the product successfully.

The system must require essential product information, such as name, code, price, and category.

The system must prevent duplicate product codes.

The registered product must be visible to authorized users.

US-02: Sales Management

Given that a customer and the requested products are registered in the system,

When a sales employee creates a sales order,

Then the system must generate an order with a unique identification number.

The system must display the selected products, quantities, and total price.

The system must allow authorized employees to track the order status.

The system must not allow orders with unavailable product quantities.

US-03: Inventory Monitoring

Given that a product is registered in the system,

When a sales order is confirmed,

Then the system must update the available stock quantity according to the reservation rules.

The system must prevent unauthorized inventory modifications.

The updated quantity must be visible to authorized users.

Physical stock must only decrease when the products are dispatched.

US-04: Purchase Management

Given that a product needs to be restocked,

When an authorized employee creates a purchase order,

Then the system must record the order and its details.

The system must identify the supplier, products, and requested quantities.

The system must allow employees to track the purchase order status.

The physical stock must increase when the purchased products are received and registered.

US-05: Customer Management

Given that an employee has access to customer management,

When they register a new customer with the required information,

Then the system must save the customer record successfully.

The system must store customer information, including name, contact details, and identification.

The system must allow authorized employees to update customer information.

The system must prevent duplicate customer records when the same identification is used.

US-06: Business Reports

Given that sales and inventory transactions have been recorded,

When an authorized employee requests a report,

Then the system must generate a report using the available business data.

The sales report must display relevant information, such as sales quantities and total revenue.

The inventory report must display product quantities and current stock levels.

The system must allow users to filter reports by date and product.
## 9. Business Process Overview

The proposed operational workflow follows this sequence:

1. Customer places an order.
2. Sales employee registers the order.
3. System checks product availability.
4. Inventory is updated after order confirmation.
5. Purchasing process is initiated when replenishment is required.
6. Business reports are updated.

## 10. Tools & Skills

**Concepts and methodologies:**
- Business Analysis
- Requirements Engineering
- Functional Requirements
- Non-Functional Requirements
- User Stories
- Acceptance Criteria
- Business Process Analysis

**Technologies and tools:**
- Microsoft Excel
- SQL (planned application)
- Python (planned application)
- ERP Systems / Odoo (research and learning)

## 11. Project Status

This repository is an ongoing educational portfolio project based on a fictional business scenario.

The requirements and workflows are simulated for learning and demonstration purposes. No production ERP implementation or real client engagement is claimed.

## 12. Author

**Gabriel Cavalcante Pereira**
Technology professional | Systems Analysis and Development Student

Brazil

[LinkedIn](www.linkedin.com/in/gabriel-cavalcante-668128280) | [GitHub]([YOUR_GITHUB_URL](https://www.linkedin.com/safety/go/?url=https%3A%2F%2Fgithub.com%2Fgabrielcavalcantpereira&urlhash=gDSo&mt=BrQgiHw5hVDuvxaNJgz3gxVBiZed6Htt1i0N-AlXx2x2lNHq0fo7yLQQ8zylFhqrABLlU7n_U1c9U1zca4LJS9Li7MQ28eksHKA1bXRM-1ZOCpQ3UXHs22id6maWM0iiGu_xkslBTkaSWDLERunoxFzCg8efy3s3ebamXvHUJZmcYc59NRSaTnL-Ki7Ktw&isSdui=true&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B9QgLqH8%2FTdOhLdbOMfEWuA%3D%3D))
