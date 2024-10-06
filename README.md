# Component Library

This project is a UI Component Library built using React and Storybook, designed to provide reusable components for web applications. The library includes buttons, labels, tables, and more, with a focus on responsive design and accessibility.

## Table of Contents
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
  - [npm start](#npm-start)
  - [npm test](#npm-test)
  - [npm run build](#npm-run-build)
  - [npm run eject](#npm-run-eject)
- [Docker Setup](#docker-setup)
- [Using Components](#using-components)
- [Storybook](#storybook)
- [Contributing](#contributing)
- [License](#license)
- [Learn More](#learn-more)

## Getting Started

### Prerequisites
Ensure you have Docker installed on your machine.

### Docker Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/hkaur213/harleen-kaur-component-library.git
   cd kaur_harleen_coding_assignment12

2. **Build the Docker image**

    docker build -t kaur_harleen_coding_assignment12 .

3. **Run the Container**
    docker run -p 8083:80 --name kaur_harleen_coding_assignment12 kaur_harleen_coding_assignment12

4. **Access the Application**
    Open your browser and navigate to http://localhost:8083



# Storybook Setup

1. **Start Storybook**
    npm run storybook

2. **Access the Application**
    Open your browser and navigate to http://localhost:6006


# Testing
    To run the tests for the components:

1. **Run Tests**
     npm test

2. **Test Coverage**

You can check the coverage of your tests, which verifies the visibility and background color changes of your components when in a disabled state.


# Styling
    All components utilize StyledComponents for styling, ensuring they are responsive across different screen sizes. Each component is styled with default and disabled states to provide visual feedback.





