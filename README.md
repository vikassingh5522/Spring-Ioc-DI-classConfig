Inversion of Control (IoC)
Definition: IoC is a design principle where the control of object creation, lifecycle management, and dependency resolution is inverted from the application code to an external framework or container. Instead of a class creating and managing its dependencies directly, the framework (e.g., Spring’s IoC container) takes responsibility for instantiating objects (beans) and wiring them together.
Key Idea: The application code doesn’t control the flow; the framework does. This reduces tight coupling and makes the code more modular and testable.
How It Works in Spring:
•
The Spring IoC container (e.g., ApplicationContext) manages beans (objects) defined in a configuration (XML, Java, or annotations).
•
The container creates instances, injects dependencies, and manages their lifecycle.
•
Developers specify what dependencies are needed, not how to create them.
