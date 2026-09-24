# Customer Management with Native Cloud Storage - SAP Build Apps

## Scenario

You want to build a customer management app that stores data in the cloud instead of only on the device. This project demonstrates how to use **Native Cloud Storage** in **SAP Build Apps** so customer records can be created, updated, and deleted in a persistent backend data store.

## Solution

This app uses a **backend data entity** together with SAP Build Apps UI logic to manage a list of customers. The user can enter a customer name and phone number, save the record, update an existing number, delete a customer, and see the latest data immediately in the application.

The exercise focuses on understanding how app screens, backend data entities, and cloud storage work together in a low-code environment.

## ✨ Features

- Create new customer records
- Store customer data in native cloud storage
- Display all saved customers in a list
- Update an existing customer phone number
- Delete selected customer records
- Use real backend data instead of local-only storage
- Demonstrate a practical CRUD flow in SAP Build Apps

## ☁️ Native Cloud Storage Concepts

This project demonstrates how to:

- Create a data entity for customer records
- Bind UI fields to cloud-backed data
- Save customer data to the backend
- Read records from the cloud data source
- Update and remove records from the data entity
- Use app logic and page actions with persistent data

Native cloud storage is useful when data needs to be shared, persisted, and accessed beyond a single device. It is a better fit than local storage for real-world business apps where data is managed centrally.

## 🛠️ Built With

- SAP Build Apps
- Native Cloud Storage
- Backend Data Entity
- App Variables
- Form Inputs
- Logic / UI Actions
- Data Binding

## 📌 Purpose

This project was created as a hands-on learning exercise to understand how **native cloud storage** works in SAP Build Apps. It gives a practical example of managing persistent customer data using backend storage while keeping the app implementation simple and beginner-friendly.

## Notes

This project is intended for learning and experimentation. The data used here is sample data for demonstration purposes only.
