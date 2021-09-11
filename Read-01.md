![react](photo/react.jpg)
# Component

## 1. What is a component?

A component is a modular, portable, replaceable, and reusable set of well-defined functions that summarize their implementation and export as a higher level interface. A software component can only be defined as a configuration unit with a defined contractual interface and explicit context dependencies. That is, the software component can be published independently and is subject to its configuration by third parties.

## 2. What are the charactistics of a component?

* **Reusability :** Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

* **Replaceable :** Components can be freely replaced with other similar components.

* **Not context specific :** Components are designed to operate in different environments and contexts.

* **Extensible :** A component can be extended from existing components to provide a new behavior.

* **Envelope :** An element that depicts interfaces that allow a caller to use its functions, and does not show details of internal processes or any internal variables or state.

* **Standalone :​​** Components are designed to have minimal dependence on other components.

## 3. What are the advantages of using component based architecture?

* **Easy Deployment :** As new compatible versions become available, it becomes easier to replace existing versions without any impact on other components or the system as a whole.

* **Reduced cost :** Using third-party components allows you to spread the cost of development and maintenance.

* **Ease of development :** components implement well-known interfaces to provide specific functionality, allowing development without affecting other parts of the system.

* **Reusable :** Using reusable components means that they can be used to spread the cost of development and maintenance across multiple applications or systems.

* **Modify technical complexity :** The component modifies the complexity through the use of the component container and its services.

* **Reliability :** The overall system reliability increases because the reliability of each individual component enhances the reliability of the entire system through reuse.

* **System maintenance and development :** Ease of change and updating in implementation without affecting the rest of the system.

* **Independent :** Autonomy and flexible connection of components. Independent development of components by a different group in parallel. Productivity for software development and future software development.

# props:

## 1.What is props short for?

**Props :** is a private keyword in React, which stands for properties and is used to pass data from one component to another.

## 2.How are props used in React?
Firstly, define an attribute and its value(data),then pass it to child component(s) by using Props and finally, render the Props Data
## 3.What is the flow of props?
uni-directional flow. (one way from parent to child)