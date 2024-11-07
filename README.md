# Traffic lights Gishushu- 
Red :

Purpose: To stop all vehicles, ensuring safety for crossing traffic or pedestrians.
Duration: Fixed: 30 seconds.
Conditions for Transition:
After the Red state duration expires, it transitions to Green, allowing vehicles to move.
Before switching to Green, it may enter a brief pedestrian crossing state, allowing pedestrians to cross.


Green:

Purpose: To let cars to pass through the intersection.
Duration: Fixed: 30 seconds.
Conditions for Transition:
After the Green state duration expires, the light turns Yellow, signaling that it will turn Red soon.


Yellow:

Purpose: To warn vehicles that the light is about to turn Red, requiring them to prepare to stop.
Duration: Short: 8 seconds.
Conditions for Transition:
After the Yellow state duration, the system moves back to Red.

Pedestrian:

Purpose: To allow pedestrians to cross safely.
Duration: Short: 15 seconds.
Conditions for Transition:
After the pedestrian duration, the light returns to Red, prohibiting further pedestrian crossing.
