# What does the code do?

## Initial Menu

Lines 16 to 23 of the original source handle the main menu.

```vbnet
Console.WriteLine("Predator Prey Simulation Main Menu")
Console.WriteLine()
Console.WriteLine("1. Run simulation with default settings")
Console.WriteLine("2. Run simulation with custom settings")
Console.WriteLine("3. Exit")
Console.WriteLine()
Console.Write("Select option: ")
MenuOption = CInt(Console.ReadLine())
```
