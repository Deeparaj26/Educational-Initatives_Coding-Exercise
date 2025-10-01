Exercise 1 – Design Pattern Examples
1️⃣ Behavioral: Observer

Classes: NewsPublisher, Subscriber, EmailSubscriber, SmsSubscriber

Demo: ObserverDemo

Use Case: When publisher posts news, all subscribers (email/sms) get notified.

2️⃣ Behavioral: Strategy

Classes: SortStrategy, BubbleSortStrategy, QuickSortStrategy, Sorter

Demo: StrategyDemo

Use Case: Sort numbers using interchangeable algorithms (bubble sort / quick sort).

3️⃣ Creational: Singleton

Class: ConfigurationManager

Demo: SingletonDemo

Use Case: Only one global config manager instance in the application.

4️⃣ Creational: Factory

Classes: Task, TaskFactory

Demo: FactoryDemo

Use Case: Centralizes creation of Task objects with default priority handling.

5️⃣ Structural: Adapter

Classes: LegacyPaymentSystem, PaymentGateway, PaymentAdapter

Demo: AdapterDemo

Use Case: Converts a legacy payment system (cents) to modern gateway (dollars).

6️⃣ Structural: Proxy

Classes: Image, RealImage, ImageProxy

Demo: ProxyDemo

Use Case: Controls access to images, loads only when needed (lazy loading).

🛰️ Exercise 2 – Astronaut Daily Schedule Organizer
📝 Features

Add a task with description, start time, end time, priority.

Remove a task by ID.

View all tasks (sorted by start time).

View by priority.

Mark tasks complete.

Conflict detection → prevents overlapping tasks.

Validation → invalid time formats rejected.

Observer notifications → console alerts on conflicts.

🛠️ Design Patterns Used

Singleton → ScheduleManager (only one instance manages tasks).

Factory → TaskFactory (central task creation + validation).

Observer → ConsoleAlertObserver (conflict / add / remove alerts).
