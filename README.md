# COMP-273-Sequential-Circuits-Multiplication-and-Division-solution

Download Here: [COMP 273 Sequential Circuits, Multiplication, and Division solution](https://jarviscodinghub.com/assignment/sequential-circuits-multiplication-and-division-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1 Warm-Up Question (4 marks)

Micheal Knight is a young loner on a crusade to champion the cause of the innocent, the helpless,
the powerless, in a world of criminals who operate above the law. Micheal Knight’s talking car,
a 1982 Pontiac Trans Am called KITT, has a scanner that consists of 8 red lights which turn on in
sequence and scan left to right and back continuously.

You are working in the props department of a production company in charge of remaking the
1980s TV series. Your task is to design a sequential circuit in Logisim that replicates KITT’s
scanner behaviour using any of the circuits in the default Logisim library. Use a row of red LEDs
from the Input/Output section of the library to display the scanner, and label your clock with the
frequency necessary for your scanner to approximately match the behaviour seen in the youtube
video above. Extend the provided KITT.circ file to implement your answer.

2 Sequential Multiplication (12 marks)
Create a sequential circuit that implements a 4 bit unsigned multiplier following the design of
the simple sequential multiplier seen in class (either the simple version or the improved version). Your circuit will have a RESET input. On a rising clock edge, when RESET is high, your
circuit should initialize its internal registers with the 4 bit inputs A and B, and then start the
multiplication on subsequent clock cycles when RESET is low. Your circuit should also provide
a DONE signal that goes high when the 8 bit result is ready. You may use anything you like from
the default Logisim library (e.g., wiring, gates, plexers, memory), but you should only use one
Adder circuit from the Arithmetic part of the library. Use the provided file to create your circuit,
as it already defines the inputs and outputs.

3 Sequential Division (4 marks)
Create a sequential circuit that implements 4 bit unsigned division. While this is trickier than
multiplication, the marks are few (diminishing returns for more effort). Again, you may use
any circuits you like from the default library, except that you should only use one addition or
subtraction circuit from the Arithmetic part of the library. Implement RESET and DONE as per
the previous question, and design your solution in the provided circuit file.

