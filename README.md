# dotnet-format-IDE0005-reproduction

This repository exists to demonstrate an issue with `dotnet format style` and `dotnet_diagnostic.IDE0005`. Run `dotnet format style` in this repository, and you will see the unnecessary statement `using System.Buffers;` in `Program.cs` be removed, but the formatter will also log out `Unable to fix IDE0005`.
