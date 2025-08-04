# AutoFactory

This project simulates a factory to explore the use of threads and heuristics. The goal is to build a core simulation logic and expand upon it with various features and optimizations.

---

### Current Features

* Production Machine: A machine generates items with a limited output capacity. Production pauses automatically when the output buffer is full.
* Workers: Workers retrieve items from the machine's buffer and transport them to a central stockpile.
* Inventory Management: I'm currently working on a system where workers will move items from the stockpile to a sales point or load them onto trucks for distribution.

---

### Future Features

* Worker Profiles: Implement unique characteristic for each worker to add more complexity to the simulation (e.g., personality, speed).
* Data Persistence: Explore different methods (e.g., database, JSON files) to save and load simulation data, including worker characteristics.
* Heuristic Optimization: Introduce different heuristic algorithms to optimize resource allocation and worker paths.
