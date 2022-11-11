You are the owner of a courier company and want to make a system for tracking your cars and their cargo. Define a
class Car that holds an information about model, engine, cargo and a collection of exactly 4 tires. The engine, cargo
and tire should be separate classes. Create a constructor that receives all of the information about the Car and
creates and initializes its inner components (engine, cargo and tires).
On the first line of input you will receive a number N ‐ the amount of cars you have. On each of the next N lines you
will receive an information about a car in the format “<Model> <EngineSpeed> <EnginePower> <CargoWeight>
<CargoType> <Tire1Pressure> <Tire1Age> <Tire2Pressure> <Tire2Age> <Tire3Pressure> <Tire3Age>
<Tire4Pressure> <Tire4Age>” where the speed, power, weight and tire age are integers, tire preassure is a double.
After the N lines you will receive a single line with one of 2 commands: “fragile” or “flamable”. If the command is
“fragile” print all cars whose Cargo Type is “fragile” with a tire whose pressure is < 1. If the command is “flamable”
print all of the cars whose Cargo Type is “flamable” and have Engine Power > 250. The cars should be printed in
order of appearing in the input.
