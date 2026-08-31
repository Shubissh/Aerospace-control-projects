Title: Transition Flight Control System Design for Tilt-Rotor eVTOL Aircraft

Objective: To create a flight control system where seamless transition is made vertical take off and forward flight. Necessary controllers must be developed to control hover and forward flight transition.



METHODOLOGY:

Physics of the model was first built:

Thrust and velocity were decomposed into vertical and horizontal components, namely Tx and Tz.

The angle that dictates seamless transition from vertical takeoff to forward flight is beta.

If beta = 0 degrees, it is hover mode.

If beta = 90 degrees, it is forward flight.

CONTROLLERS:

Altitude controller was built by manipulating force equilibrium balance in the vertical componenets, thrust, weight and lift.

Speed controller was added at the very end to ensure this "what speed or thrust can the pilot choose to provide the needed beta angle for forward flight?"
Initially it was built for a constant beta angle, however this is not real physics and does nto mimic real flight. Hence speed controller dictates what beta angle is needed for hover or forward flight.
