# Notification Management System

## Description
This project is a simple notification management system implemented in Java.
It supports sending notifications through different channels such as Email, SMS and Push.
The system uses the Factory Method design pattern to create notification objects dynamically.

## Goal
The goal of this project is to build a flexible and extensible system for sending notifications
without changing the core application logic.

## Tasks
- Create a common notification interface
- Implement notification classes for different channels
- Use a factory method to create notifications
- Make it easy to add new notification types

## Design Pattern
Factory Method

The Factory Method pattern is used to encapsulate the creation logic of notification objects.
The client works with the INotification interface, while the factory decides which concrete
notification class to instantiate.

## Technologies
- Java
- OOP
- Factory Method Design Pattern
