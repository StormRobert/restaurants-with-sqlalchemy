# restaurants-with-sqlalchemy
Python_assignment
Embark on a culinary journey with the Restaurants Project! This endeavor explores the dynamic interplay of `Restaurant`, `Review`, and `Customer` models, unleashing the power of SQLAlchemy for an enriching experience.

## Project Overview

The Restaurants Project revolves around three pivotal models: `Restaurant`, `Review`, and `Customer`. The essence lies in establishing meaningful relationships between these entities.

### Key Components

- **Migrations & Models:** Lay a robust foundation by crafting meticulous migrations and seeding essential data for comprehensive testing. This ensures a seamless integration of your database schema.

## Object Relationship Methods

Delve into intuitive methods that seamlessly connect reviews, customers, and restaurants. These methods are carefully crafted to ensure easy navigation and retrieval of related data.

### Example Methods

- `Review.customer()`: Retrieve the associated `Customer` instance for a review.
- `Restaurant.reviews()`: Obtain a collection of all reviews for a specific restaurant.

## Aggregate & Relationship Magic

Unlock advanced functionalities that add depth to your project. From assembling customer full names to discovering the fanciest restaurants, these methods elevate the user experience.

### Advanced Features

- `Customer.full_name()`: Generate a full name by concatenating first and last names in Western style.
- `Restaurant.fanciest()`: A class method returning the restaurant with the highest price.

