# -Gym-member-ship-
Title: Gym Membership Management System

Purpose: A Java desktop application built to demonstrate core Object-Oriented Programming (OOP) principles — abstraction, inheritance, polymorphism, and encapsulation — through a practical, real-world scenario: managing gym members.

Problem it solves: Gyms need to track different categories of members with different rules (pricing, attendance limits, payment plans, benefits). Rather than one bloated class handling every case, the project models this with a class hierarchy so shared behavior lives in one place and specialized behavior lives in subclasses.

Structure:

GymMember (abstract superclass) — common member data (ID, name, contact details, DOB, attendance, loyalty points, active status) and shared logic (activate/deactivate, display, save/load).
RegularMember (subclass) — members on tiered plans (Basic/Standard/Deluxe), each with different pricing, a referral source, and an attendance-based discount.
PremiumMember (subclass) — members with a fixed high-tier charge, an assigned personal trainer, and an installment payment system with a loyalty discount once fully paid.
GymGUI — a Swing-based graphical interface that ties everything together: forms to add regular/premium members, buttons to activate/deactivate, mark attendance, calculate discounts, update plans, display all members, and save/load member data to a text file.

Tools used (per the report):

BlueJ — the IDE used to write and run the code (chosen for its beginner-friendly interface, live object interaction, and built-in debugger).
Microsoft Word — for writing the accompanying report.
draw.io — for creating the class diagrams and flowcharts documenting the design.
Notepad — for the plain-text .txt files used as the data storage format.
