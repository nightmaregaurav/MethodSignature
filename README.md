# MethodSignature - Simplified Method Signature Retrieval

MethodSignature is a C# library that provides a simple and convenient way to extract the signature information of methods from a given class. It can be used to retrieve details about method visibility, static status, parameter types, and return type.

## Features
* Retrieve method signature information effortlessly.
* Supports methods with various access modifiers and parameters.
* Works with both static and instance methods.

## Use Cases
1. API Documentation Generation.
2. Code Analysis and Inspection Tools.

## Getting Started
To get started with MethodSignature, follow these simple steps:
1. Install the MethodSignature package from [NuGet](https://www.nuget.org/packages/MethodSignature).
2. Import the MethodSignature namespace in your C# file.
    ```csharp
    using MethodSignature;
    ```
3. Retrieve method signature information using the `SignatureOf` method.
    ```csharp
    Type classType = typeof(YourClass);
    string methodName = "YourMethodName";
    var methodSignature = MethodSignature.SignatureOf(classType, methodName);
    ```
4. Access the properties of the `MethodSignature` object to get the required details.
    ```csharp
    Console.WriteLine(methodSignature.ToString());
    ```

## Contributions and Issues
MethodSignature is free and open-source. Contributions are highly appreciated. If you find any issues or have suggestions to improve the library, feel free to submit a pull request or create an issue in the [GitHub repository](https://github.com/nightmaregaurav/MethodSignature).

## License
MethodSignature is released under the MIT License. You can find the full license details in the [LICENSE](https://github.com/nightmaregaurav/MethodSignature/blob/main/LICENSE) file.

This library was made with ❤️ by [NightmareGaurav](https://github.com/nightmaregaurav).
