### Idealogy behind this approach
**Mono-repo** greatly elevates the easability for developers. Why duplicating code? While we can share!  

### Setting up and Getting started

The application uses **yarn** package manager at it's core. Though npm can be used, yarn is used as a baseline.

**Step 1:** Setting up Development environment
- Install the dependencies using the command ```yarn``` 
- Install the recommended extensions from extension panel from _left pane_

**Step 2:** Understanding the project structure
- **apps:** folder contains all the application.
- **libs:** folder basically contains the re-usable code which used throughout the application.
- **libs/core:** The integral part of the application above which the applications are generally built.
    - **server:** Wrapper arround express middleware, utilized by almost all the application.
    - **logger:** Wrapper arround a logger utility (Winston) 

### Basic principles