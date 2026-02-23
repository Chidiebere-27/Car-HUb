# Car-HUb
******Workshop Management Database (PostgreSQL)******
**Overview**

A PostgreSQL relational database built for a multi-branch car workshop to manage customers, vehicles, bookings, services, payments, parts inventory, staff scheduling, safety inspections, and feedback.

What I Built

Normalised schema with constraints (PK/FK, checks for dates/times)

Performance indexes on high-usage fields (dates, postcodes, stock, names, amounts)

Reporting views (availability, service costs/parts used, booking details, inspection results, inventory usage)

Example queries for refunds, unresolved feedback, staff schedules, and stock monitoring

**Role-based access control (RBAC)** with custom roles and granular GRANT permissions (least privilege)

****Database Entities****
**Main tables include:**

Branch, Workshop, Shift, Staff, Role, Staff_role

Customer, Vehicle, Membership, Payment, Booking

Service, Service_Task, Part, Service_part

safety_inspection, Compliance_Record, Customer_Feedback, Communication

Reporting Views
**Tech**

PostgreSQL (psql) • SQL • Indexing • Views • Data integrity • Security/Permissions

**Skills Demonstrated**

Database design • Query optimisation • Reporting-ready views • Documentation discipline • Secure access management
