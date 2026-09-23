# Customer Management with Local Storage - SAP Build Apps

## Scenario

You want to build a simple customer management app without connecting to an external database. The app keeps customer information directly on the device so it can be added, viewed, updated, and deleted while practicing how local data is handled in **SAP Build Apps**.

## Solution

This mini project uses **Local Storage** to save a list of customer objects on the device. Users can enter customer details through a form, view the saved customers in a list, select a customer to edit or delete, and see the updated data immediately in the app.

The project is designed as a hands-on exercise for understanding how app variables, data binding, page logic, and local persistence work together in SAP Build Apps.

## ✨ Features

- Adds new customers through a form
- Stores customer data locally on the device
- Displays saved customers in a repeatable list
- Updates existing customer details
- Deletes selected customers
- Keeps data available after closing and reopening the app
- Demonstrates empty-list and form interaction states

## 💾 Local Storage Concepts

This project demonstrates how to:

- Create and initialize a local storage value
- Read locally saved data when the app loads
- Add a new object to a stored list
- Update or remove an object from the list
- Save changes back to Local Storage
- Bind stored data to UI components

Local Storage is useful for lightweight offline prototypes and learning projects. It is not a replacement for a shared backend database when data must be synchronized across users or devices.

## 🛠️ Built With

- SAP Build Apps
- Local Storage
- App Variables / Data Variables
- Repeat Component
- Data Binding
- Page Logic
- Form Components

## 📌 Purpose

This project was created as a hands-on learning exercise to understand how **Local Storage** works in SAP Build Apps. The customer management scenario provides a practical way to practice CRUD operations, persistent local data, and data-driven UI behavior without requiring an external service.
