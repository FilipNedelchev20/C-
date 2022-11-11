Note: you need a public StartUp class with the namespace CarManufacturer.
Create a class public Car with additional members (you can use the class from the previous task).
The class should have private fields for:
 make: string
 model: string
 year: int
 fuelQuantity: double
 fuelConsumption: double
The class should also have properties for:
 Make: string
 Model: string
 Year: int
 FuelQuantity: double
 FuelConsumption: double
The class should also have methods for:
 Drive(double distance): void – this method checks if the car fuel quantity minus the distance
multiplied by the car fuel consumption is bigger than zero. If it is remove from the fuel quantity the result of
the multiplication between the distance and the fuel consumption. Otherwise write on the console the
following message:
"Not enough fuel to perform this trip!"
 WhoAmI(): string – returns the following message:
"Make: {this.Make}\nModel: {this.Model}\nYear: {this.Year}\nFuel:
{this.FuelQuantity:F2}L"
You should be able to use the class like this:
