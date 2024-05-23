**CIRSA Affiliate Website**

**Project Overview**

This project aims to develop an affiliate website for CIRSA, providing an engaging and efficient user experience through the design and development of multiple views that offer an intuitive and accessible interface for both affiliates and customers.

**Context**

- This project was conceived and developed within the framework of an intensive development event with time constraints.
- The focus was on code quality and design, with an emphasis on achieving maximum efficiency and functionality within the available time.

**Objectives**

- Design an attractive and functional homepage for the application.
- Develop affiliate login and registration interfaces.
- Implement a customizable dashboard for affiliates.
- Create a customer registration view that links to each affiliate's personalized URL.
- Foster a creative and unique design using resources such as color palettes, icons, and fonts.
- Deploy the site on Github Pages or similar platforms for easy access.

**Usage**

### General Navigation

- Users can easily navigate through the application's different views, with clearly outlined options for affiliate registration and login, and customer registration.

### Dashboard Customization

- Affiliates have the ability to personalize their dashboard, including generating a unique URL to share with potential customers.

**Installation**

As an online hosted project, it does not require installation steps for end users. Users can access the site through a web browser, facilitating universal access without the need for additional configurations.

**Tech Stack**

### Core Technologies

- **Programming Languages**: JavaScript, HTML, CSS, C# (used in Blazor).
- **Frameworks and Libraries**: Blazor for server-side interaction and Bootstrap for responsive design.
- **Tools and Services**: GitHub for version control and Github Pages for hosting.

**Decision Making**

### Development Strategy

- We opted for a modular approach to design to maximize customization and enhance user experience.
- The choice of Blazor was based on its ability to integrate C# into web development, allowing us greater synergy with existing backend systems.

### Technology Selection

- Established technologies with a large support community were selected to ensure smooth and efficient development.
- The choice of Blazor was motivated by its ability to run C# code in the browser, enriching the user experience.

### Challenges and Solutions

- We faced the challenge of balancing creativity with functionality within a limited timeframe. This was addressed by prioritizing essential features and maintaining a high standard in design.
- We implemented creative solutions for customer registration through personalized URLs and developed a functional and attractive design for the homepage.

**Team Contributions**

- **[Alfred Pérez Herranz]**: Responsible for frontend development, including the homepage and styling with Bootstrap.
- **[Alfred Pérez Herranz/Soufian Ahlal Aggadi]**: Backend and Blazor logic, including the implementation of the affiliate dashboard.
- **[Alfred Pérez Herranz]**: Focused on redirect logic integration.
- **[Soufian Ahlal Aggadi]**: Responsible for personalized URL processing.
- **[Sofian Ahlal Aggadi and Alfred Pérez Herranz]**: Responsible for CSS for custom styles of all views.
- **[Soufain Ahlal Aggadi]**: Deployment Guide-> 
    First step: write command "dotnet publish -c Release" in terminal.
    Second step: then write this other command "docker build -t blazorapp ." It will probably fail and suggest you install an extension called Docker. Do it and put the command again.
    Third step: write this last command "docker run -p 8080:80 blazorapp"
    (Do not put the "" when entering the commands in the terminal ;)

**Conclusion**

This documentation serves as a comprehensive project report, highlighting the key decisions made during development and the individual contributions of team members, within a context of limited time.
