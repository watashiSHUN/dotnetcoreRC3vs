# dotnetcoreRC3vs
not backwards compactable with previous dotnet cli, for instance
running `dotnet publish` with dotnet_sdk_win_x86_1_0_0-preview4-004233:

```
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(14,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(15,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(16,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(17,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(18,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(19,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(20,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(21,12): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(14,55): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(15,61): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(16,59): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(17,59): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(18,68): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(19,55): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(20,53): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(21,55): error CS0518: Predefined type 'System.String' is not defined or imported [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(11,7): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
obj\Debug\netcoreapp1.0\dotnetcoreLib1.AssemblyInfo.cs(12,7): error CS0246: The type or namespace name 'System' could not be found (are you missing a using directive or an assembly reference?) [D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj]
C:\Program Files (x86)\dotnet\sdk\1.0.0-preview4-004233\Sdks\Microsoft.NET.Sdk\build\Microsoft.NET.Sdk.targets(82,5): error : Cannot find project info for 'D:\dotnetCoreRC3\dotnetcoreLib1\dotnetcoreLib1.csproj'. This can indicate a missing project reference. [D:\dotnetCoreRC3\dotnetCoreRC3\dotnetCoreRC3.csproj]
```
