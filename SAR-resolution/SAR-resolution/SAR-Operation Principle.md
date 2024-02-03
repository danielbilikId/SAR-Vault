## Real aperture radar (RAR):

If a radar antenna, which amplifies the transmitted and received signal, is carried in an airplane or an orbiting satellite, a radar can be used to make an image of the ground below. Forward looking radar cannot create images.  Such a radar image is formed by transmitting pulses of radio frequency (RF) energy towards the ground and to the side of the aircraft, and measuring the strength of the return (sometimes called an “echo”) and the length of time it takes to make the round trip back to the antenna. In this manner, the ground is “scanned” in two dimensions. One dimension is the “range” dimension. Objects are placed along in this dimension according to their distance from the radar. The second dimension is the “along-track” (or “cross-range” or “azimuth”) dimension. In this dimension, the ground is scanned by the beam moving across the ground at a rate equal to the speed of the platform (aircraft or satellite), and objects are placed in this dimension according to the position of the aircraft along the track. An image is built up from the reflected signals in both dimensions.

![[figures and graphs/Figure 2. Imaging Radar Geometry.png]]

Spatial resolution, the ability to resolve objects on the ground, differs in the range direction (perpendicular to the flight direction) compared to the azimuth direction (parallel to the flight direction). In “real aperture radar,” the range resolution is defined by the width of the pulses transmitted from the antenna. The azimuth resolution is determined by the width of the beam’s footprint on the ground, and the width of the beam is inversely proportional to the antenna length. A short antenna length corresponds to a wide beamwidth (beam footprint on the ground). Because flying an antenna large enough to generate a reasonable azimuth resolution, in space, is prohibitive, this limits the spatial resolution in the azimuth direction. The development of advanced processing algorithms solved this problem, leading to a new generation of imaging radars called Synthetic Aperture Radar.

## Range Resolution for RAR: 

> Range is the direction perpendicular to flight path of the aircraft. The vertical beamwidth $θ_v$ is determined by the wavelength $λ$ and antenna height $W_a$  - its the same as antenna length in the direction that its pointing. for a dipole this would be $L_a$ that 
>> so that: $θ_v$ = $λ$/$W_a$ 
	the width on the ground ("Swath") is calculated: 
	


>A Synthetic Aperture Radar is an imaging radar mounted on a moving platform. Similar to a conventional radar, electromagnetic waves are sequentially transmitted and the backscattered echoes are collected by the radar antenna. In the case of SAR the consecutive time of transmission/reception translates into different positions due to the platform movement.

