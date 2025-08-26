# RikaDotNet Obfuscator

[Visit RikaDotNet](https://rikadotnet.com)  

**Powerful .NET obfuscator with string encryption, virtualization, anti-tamper and more!**

---

## Features

### String Encryption
Protect all strings in your application with advanced algorithms. Safeguard sensitive data like keys, passwords, and API tokens from reverse engineering and unauthorized access.

### Code Virtualization
Transform your code into a highly obfuscated virtual machine (VM) format. This adds an extra runtime layer, making it extremely difficult for attackers to understand or reverse your logic.

### Anti-Tamper
Prevent your code from being read or modified in static decompilers. The assembly does not store code in its pure form, thwarting reverse engineers.

### Renaming
Automatically rename classes, methods, variables, and other identifiers to meaningless names. This obscures functionality and logic, making reverse engineering more difficult.

### Control Flow Obfuscation
Alter the execution flow of your software without changing its behavior. This complicates reverse engineering by hiding the underlying structure.

### Resource Encryption
Encrypt and protect all vulnerable resources embedded in the assembly.

### Reference Proxy
Replace direct references to methods with indirect "proxy" calls, adding another layer of protection.

### Anti-VM
Detect if your application is running in a virtual machine or sandbox environment and terminate execution immediately if detected.

### Library Mode
When protecting a dynamic link library (.dll), renaming skips 'public' members to maintain external compatibility.

---

## Limitations

- **Limited Anti-Tamper Support:** Anti-Tamper cannot be used with C++/CLI, signed assemblies, or assemblies that require post-obfuscation modification. Not supported on Linux.  
- **Code Virtualization Restrictions:** Does not support methods with generic parameters, generic return types, or the use of `System.Diagnostics.StackTrace`.

---

## Compatibility

### Supported Platforms
- Windows  
- Linux  

### Supported Frameworks
- **.NET Framework:** 2.0 – 4.8.1  
- **.NET (Core):** 1.0 – 10.0  
- **.NET Standard:** 1.0 – 2.1  

### Supported Application Types
- Console Applications  
- WinForms  
- WPF  
- ASP.NET apps and libraries  
- Class Libraries, Control Libraries, Windows Service Libraries  

---

**Protect your .NET applications today with RikaDotNet:** [https://rikadotnet.com](https://rikadotnet.com)
