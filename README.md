# Creating a project
File > new Java project

# Creating a package
New > Package > iezon.app.*

* - being your application name (include .'s for whitespace)

# Creating the main method
New > Other > JPanel > *.class

* - being your application name
Note: Be sure to download and install Window Builder

# Example

```java
Package iezon.app.example.app;

class ExampleApp() extends JPanel {
  public ExampleApp() {
    setLayout(null);
    // TODO: Your logic
  }
}
```

# Creating a security policy

Create a new, empty, .policy file and call it your application name.
Line by line, insert your permissions.

# Default Example

```java
setSecurityManager
getSecurityManager
createSecurityManager
usePolicy
```
