# Calendar-Application
This is a simple yet functional Calendar Event Management Application built using Java Swing. It allows users to add, edit, and delete events with a date and event name. The project demonstrates core Java concepts such as GUI development, event handling, OOP, and date parsing.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 Features

➕ Add Events — Users can create new events with a name and date.

✏️ Edit Events — Users can modify existing event details.

❌ Delete Events — Remove unwanted events from the list.

📋 Event List View — Events are displayed in an interactive JList.

📅 Date Handling using SimpleDateFormat.

🖼️ User-Friendly UI created with Java Swing components.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Concepts & Technologies Used
1. Java Swing (GUI Framework)

    JFrame, JPanel, JButton, JList, JScrollPane

    Layout Managers: BorderLayout, FlowLayout

    JOptionPane for dialog input

2. Event Handling

    Implemented using ActionListener

    Buttons trigger add/edit/delete operations

3. Object-Oriented Programming

    Encapsulation through the Event class (name + date)

    Custom methods for creating, editing, updating events

4. Collections Framework

    List<Event> used internally to store events

    DefaultListModel<Event> to update UI dynamically

5. Date & Time Handling

    Parsing and formatting dates using SimpleDateFormat

    Validation for incorrect user input

6. MVC-like Structure

    While not a strict MVC, the project loosely follows it:

    Model: Event class

    View: Swing UI components

    Controller: Logic inside button action listeners

📂 Project Structure
CalendarApplication.java
 ├── main UI window
 ├── event list handling
 ├── add/edit/delete operations

Event.java
 ├── stores event details (name + date)
 ├── date formatter methods
 └── toString override for display

----------------------------------------------------------------------------------------------------------------------------------------------------------------
▶️ How to Run

    Ensure you have Java 8+ (works with Java 21 as well).

    Compile the project:

        javac CalendarApplication.java


Run:

java CalendarApplication

📸 UI Overview

Main window displays a list of events.

Buttons at the bottom for Add, Edit, Delete.

Dialog boxes are used to collect user input.

💡 Possible Future Enhancements

Add calendar view with JCalendar or JavaFX

Save events to a database or file

Add reminders and notifications

Improve UI with custom styling
