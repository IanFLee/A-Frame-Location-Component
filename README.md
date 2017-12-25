# A-Frame-Location-Component
A-Frame: Location Component that takes in the Cameras/Users Location

LOCATION CONCEPT 0.1

In theory, would you be able to allow the Component to take in the data from the camera or user position, so that it could use the camera's distance from an object as an _event that could be triggered. Allowing for a more immersive and interactive user experience.

--------------------------------------------------------------------------------------

LOCATION CONCEPT 0.2 

  // UPDATE: updated to calling the pinned area of wherever the user/object is, as the LOCATION. This should be able to be extended to other objects as well, so that a moving objects LOCATION would be able to trigger an _event as well.

	// This first example could even apply to making objects "jump" locations; from one area to another.
	
	event-set__1="_event: movingObject_location(5 2.5 0); _target: #movingObjectLocation; position: 2 2 2"

	event-set__2="_event: location(-5 2.5 1); _target: #responsiveObject; visible: true; scale: 5 6 4"

	event-set__3="_event: location(-10 1 1); _target: #boxLocation; visible: true; color: red"
	
	// An Example of Teleporting an item through location tracking.
	event-set__4="_event: location(-10 1 1); _target: #boxLocation; from: location(-20 1 1); to: location(1 1 1)"


My knowledge of Javascript is at an intermediate level, so anyone wants to jump in to help complete this component then by all means jump right on in :D!
