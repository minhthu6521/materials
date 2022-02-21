# Dependency inversion principle
In OOP, the dependency inversion principle is a specific methodology for loosely coupling software module. 

When following this principle, the conventional dependency relationships established from high level, policy setting module to low level dependencies module are reversed, thus rendering high-level modules independent of the low-level module implementation details. The principle states:

- High-level modules should not import anything from low-level modules. Both should depend on abstractions (e.g., interfaces).
- Abstractions should not depend on details. Details (concrete implementations) should depend on abstractions.