
# Use Case Diagram Documentation

This directory contains the Use Case Diagram that visually maps the interactions between the primary system actors (Guest, Host, Admin) and the core backend functionalities.

## Actors Defined

1. **Guest:** Users performing searches, bookings, and reviews.
2. **Host:** Users managing properties, availability, and guest communication.
3. **Admin:** Users with global system oversight and management permissions.

## Key Interactions Visualized

The diagram illustrates the flow for core features:

* **Authentication:** All actors must register and log in.
* **Booking Flow:** The Guest searches, views, and initiates the "Book Property" use case. This directly **Includes** the mandatory "Process Payment" use case.
* **Listing Management:** The Host is the sole actor responsible for creating, editing, and deleting property listings.
* **System Oversight:** The Admin is shown interacting with management use cases (e.g., managing users and monitoring listings).