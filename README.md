# 💻 Shop Management Application
The app’s main purpose is to connect the main store chains to their clients in a more efficient and time saving way. It serves as a digital portal between the buyers and the actual physical store, and the whole package of functionalities of an online store, such as a cart to place your products, descriptions and reviews, a home page, a contact page, and an order history page.
So, if it has all the features of an ordinary online shop, what is something new that it brings? Well first of all, the users begin their search in the app by creating a new list in which they introduce specific keywords related to the desired products. Then they can select their favorite stores from which they want to get these products from. Based on these selections, a list will be created with the best products, based on their quality and price. 
The application is hosted on 🌍[App](https://shopmanagement-af64b.web.app/).
Also for the mobile app the source code can be found on 📱[Mobile](https://github.com/Piciorus-Ovidiu-Mihai/ShopManagement/tree/main/shop-management-android).

## 🛠️ Architecture
* 🌍 Web Application
A modular architecture in Angular refers to structuring an Angular application into discrete, self-contained modules. Each module encapsulates specific functionalities and components, promoting code organization, reusability, and maintainability.
This modular architecture divides an application into smaller, manageable pieces. This enhances code organization by grouping related components and services within their respective modules. Modules allow for the encapsulation of components, services, and other resources. These can be reused across different parts of an application or in entirely different projects, reducing redundancy and promoting code reusability.
With modules, it becomes easier to locate and modify specific parts of the application without affecting other areas. This promotes maintainability, as changes and updates can be made with less risk of unintended side effects.
Applications structured with a modular architecture are inherently scalable. New features or components can be added as separate modules, ensuring that the core structure remains intact.

<p align="center">
 <img src="https://github.com/Piciorus-Ovidiu-Mihai/Photos/blob/master/diagrama-arhitectura-new-new.png">
</p>

Angular allows for lazy loading of modules, which optimizes the application's initial load time by loading only the required modules when needed.
In larger development teams, different teams or developers can work on separate modules concurrently, reducing conflicts and streamlining collaboration.
Modules facilitate unit testing of components and services in isolation, ensuring that each module functions correctly.

* 📱 Android Application
In this architecture, known as the Activity-Fragment UI Architecture, the user interface of the Android application is designed by combining Activities and Fragments, which are constructed using XML layouts.
Activities are fundamental components in Android applications. They represent individual screens or windows in your app. Each Activity typically corresponds to a single screen or user interface, and it manages the UI elements, user interactions, and navigation for that screen.
Activities are defined in the AndroidManifest.xml file and often contain layout files (XML) that define the visual structure of the user interface.

<p align="center">
 <img src="https://github.com/Piciorus-Ovidiu-Mihai/Photos/blob/master/diagram-android-new-new.png">
</p>

Fragments are a way to modularize and reuse parts of the user interface. They are like "sub-Activities" that can be embedded within Activities.
These can have their own layout files (XML) and logic. They're used to create reusable components of an interface that can be combined in different ways within various Activities.
Fragments are often used for tasks such as creating navigation drawers, swipe views, or multi-pane layouts for larger screens.
XML layout files are used to define the structure and appearance of user interface components within both Activities and Fragments.XML files can specify the arrangement of widgets (buttons, text fields, etc.) and the overall design of the screen. 
Layouts can be inflated and incorporated into Activities and Fragments, allowing you to create consistent and visually appealing user interfaces.

## 📷 Preview  
The dashboard is the central hub of the application, offering an at-a-glance view of key information, statistics, and functionalities. It serves as the first point of interaction for users and provides an overview of the application's capabilities. Users can quickly access important features and navigate to other sections of the application from the dashboard.

<p align="center">
 <img src="https://github.com/Piciorus-Ovidiu-Mihai/Shop-Mangement-Presentation/blob/main/sp-preview-1.png">
</p>

The products list page is a crucial component of the application, responsible for presenting a comprehensive catalog of products or items. It offers users a structured view of available products, enabling them to browse, search, and select items of interest.
<p align="center">
 <img src="https://github.com/Piciorus-Ovidiu-Mihai/Shop-Mangement-Presentation/blob/main/sp-preview-dashboard.png">
</p>

## 🛡️ Key Features
* Efficiency: Save time and valuable resources by eliminating the need to build everything from scratch, allowing developers to focus on the unique aspects of their application.
* Customization: Easily customize projects based on specific requirements, such as selecting desired navigation menus, integrating reusable components, and implementing authentication modules.
* Flexibility: Adapt to the ever-evolving industry requirements with the flexibility and ease of use offered by this solution.
* High-Quality Code: The project promotes robust coding standards and design patterns, fostering scalability and maintainability while adhering to industry best practices.
* Collaboration: Standardized coding styles, naming conventions, and architectural models enhance code readability and facilitate collaboration within development teams.
* Future-Ready: Create web applications that are not only visually appealing but also robust and adaptable to future needs.

## 💽 Prerequisites
* ⚙️ Install [Node.js](https://nodejs.org/en/download/)
* ⚙️ Install Angular using `npm install -g @angular/cli`

## 🚀 Getting Started
* ⭐ Clone the repository
* ⭐ Open a terminal in the project path
* ⭐ Run `npm install`
* ⭐ Run `ng serve`

## 🖥️ Technologies
* 💽 `Angular`
* 💽 `Typescript`
* 💻 `Firebase`
* 💽 `Java`
* 💽 `Android`
* 💻 `CSS & HTML`
