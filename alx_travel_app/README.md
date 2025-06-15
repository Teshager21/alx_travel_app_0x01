# 🛠️ Database Modeling and Data Seeding in Django

## 📌 Objective

This project focuses on modeling data and seeding the database in a Django application. You'll define core models, create serializers for clean API output, and implement a custom management command to seed your database with sample data—laying the foundation for future development and testing.

---

## 🚀 Project Scope

Django project - modeling the data structure for a simplified travel booking platform.

---

## 🧱 TASKS

### ✅ 1. **Model Creation**
Located in: `listings/models.py`

You will define the following models:

- `Listing`: Represents a travel property.
- `Booking`: Represents a booking made by a user.
- `Review`: Captures feedback and ratings from users.

Each model includes:
- Proper field types and constraints
- Foreign key relationships
- Meaningful string representations
- Auto-managed timestamps

---

### ✅ 2. **Serializers Setup**
Located in: `listings/serializers.py`

You will implement serializers for:
- `Listing`
- `Booking`

These serializers will:
- Convert model instances to JSON
- Enable clean API responses
- Facilitate frontend/backend integration

---

### ✅ 3. **Data Seeding Command**
Located in: `listings/management/commands/seed.py`

This custom management command allows you to:
- Populate the database with sample listings, bookings, and reviews.
- Quickly test and demo the API with real-looking dummy data.

Usage:

```bash
python manage.py seed
