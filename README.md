# Self Driving Car

Uses vanilla JavaScript (no libraries other than those built into vanilla JS)

Created self driving car that attempts to drive around a series of cars (called traffic). Car is able to move forwards, left, right, and reverse. Car may only turn left or right while moving, to simulate a real car. Similarly, car will not stop immediately when forwards or backwards are released, but slow to a stop.

Program shows the vehicle that has made it the furthest and switches when another car overtakes it.

When user finds a vehicle with a pattern they like, they can save it to localStorage with a save button. When the user refreshes the program, the saved vehicle will become the basis of all other vehicles, and it will slightly mutate the behavior of all other cars.

Should the user desire to start over, a discard button will delete the current data from the localStorage

Program displays the neural network of the current best car, showing current biases towards each movement option. Cars not the current best car are displayed with a transparency to them, and current best car has its sensor lines displayed.
