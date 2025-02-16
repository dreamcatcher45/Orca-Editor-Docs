# Orca Editor

Orca Editor is a cutting-edge, browser-based code editor and execution environment that brings a full Node.js and Python development experience directly to your browser. No local installations or complex setups are required—just open your browser and start coding!

## Overview

Orca Editor leverages the powerful WebContainer API to create a secure, isolated, and fully functional development environment right inside your browser. Whether you're prototyping new ideas, experimenting with code, or teaching programming, Orca Editor offers an all-in-one platform designed to streamline your workflow for both JavaScript/TypeScript and Python projects.

## Key Features

- **In-Browser Code Execution**  
  Run Node.js and Python applications directly in your browser with built-in, sandboxed runtime environments.

- **File Upload & Import**  
  Easily upload local files or entire project directories into the editor. Supports drag-and-drop functionality and maintains folder structure during imports.

- **Real-Time Code Editing**  
  Enjoy a seamless coding experience with the Monaco Editor, which provides intelligent code completion, syntax highlighting, and error detection.

- **Integrated Terminal**  
  Interact with your environment using an in-browser terminal powered by Xterm.js, enabling you to execute commands and view logs in real time.

- **Virtual File System**  
  Manage and navigate your project files with ease using a fully integrated file explorer.

- **Instant Preview & Hot Reload**  
  See live updates of your application as you code, with hot reload capabilities that instantly reflect changes without needing a manual refresh.

- **NPM Package Support & Python Module Integration**  
  Expand the functionality of your projects by installing and managing npm packages, while also leveraging popular Python libraries within the browser.

- **Responsive and Modular Layout**  
  Customize your workspace with adjustable panels for the editor, output, and terminal, ensuring an optimal setup for your coding style.

## How It Works

Orca Editor creates a virtual development environment using the WebContainer API, which simulates full Node.js and Python ecosystems directly in your browser. The application is built with modern technologies to ensure a robust and responsive user experience:

- **Editor**:  
  Powered by the Monaco Editor, it offers a rich interface for writing and editing code with features like syntax highlighting and auto-completion.

- **Terminal**:  
  An embedded terminal powered by Xterm.js that allows you to run commands, manage processes, and interact with your project.

- **File Explorer**:  
  A dynamic sidebar that lets you browse, create, and manage files within your virtual file system.

- **File Management**:  
  Support for file uploads through drag-and-drop or file picker dialog, maintaining directory structures and automatically detecting file types. The virtual file system seamlessly integrates uploaded files into your workspace.

- **Output Panel**:  
  A dedicated area that displays the results of your code execution, logs, and other runtime outputs.

When you write and save your code, Orca Editor dynamically compiles and executes it within the browser’s sandboxed environments for both Node.js and Python. This instant feedback loop—from coding to execution—empowers you to iterate rapidly and efficiently.

## Technologies Used

- **WebContainer API**:  
  Creates isolated, in-browser environments for Node.js and Python.

- **React.js**:  
  Delivers a dynamic, component-based user interface.

- **TypeScript**:  
  Enhances code reliability and developer productivity with static typing.

- **Monaco Editor**:  
  Provides a robust, feature-rich code editing experience.

- **Xterm.js**:  
  Enables a fully functional terminal interface within the browser.

- **Express.js & Node.js**:  
  Underpin the server-side execution environment for JavaScript/TypeScript projects.

- **Python Runtime**:  
  Supports executing Python code, allowing developers to leverage Python's extensive ecosystem directly in the browser.

- **Web Workers**:  
  Optimize performance by offloading resource-intensive tasks.

## Benefits

- **Zero Setup Required**:  
  Start coding immediately without the hassle of installing software or configuring environments.

- **Secure & Isolated Environment**:  
  Experiment confidently within sandboxes that protect your system while running Node.js or Python.

- **Enhanced Productivity**:  
  Real-time feedback, hot reloading, and an integrated terminal streamline your development process.

- **Streamlined File Management**:  
  Import existing projects or individual files with ease, maintaining your local directory structure and file organization.

- **Accessible Anywhere**:  
  Run your projects from any modern browser that supports WebAssembly, making your workspace truly portable.

- **Ideal for Learning & Experimentation**:  
  Perfect for educators, students, and developers looking to prototype and test ideas quickly in multiple programming languages.

Experience a new era of in-browser development with Orca Editor—where powerful Node.js and Python capabilities and a seamless coding experience meet right at your fingertips!
