# Variable Naming

## Classes, Enums, & Constants

For classes and variable types, use PascalCase. When using PascalCase, you capitalize each word in the name of the object. For example, a class that represents a swerve module would be named `SwerveModule`.

```java
public class SwerveModule {
    // ...
}
```

Or for an enum that represents the state of a swerve module:

```java
public enum SwerveModuleState {
    // ...
}
```

Or for a constant that represents the CANID of a swerve module's motor:

```java
public static final int BackLeftTuringMotorCANID = 0;
```

Make sure to keep the name of the class, enum, or constant short and concise, while keeping the name representative of the data it holds or file it represents. If the name is too long, it will be hard to read and understand.

## Methods & Variables

For methods and variables, use camelCase. When using camelCase, you capitalize the first letter of each word in the name of the variable except for the first word. For example, a method that sets the state of a swerve module would be named `setState`.

```java
public void setState(SwerveModuleState state) {
    // ...
}
```

Or for a variable that represents the state of a swerve module:

```java
private SwerveModuleState state;
```



