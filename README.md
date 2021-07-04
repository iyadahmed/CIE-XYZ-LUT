# Note: Wavelength for Eevee has been merged in Blender 3.0+
https://developer.blender.org/D11326

# CIE-XYZ-colormatching

**dependencies**: imagio,numpy

**blend file already has the LUT packed (make sure you set the image texture color space to XYZ), as well as two node groups, "Wavelength stepped" and "Wavelength smooth", stepped doesn't do interpolation at all, changes every 5nm (just like Cycles), smooth does interpolation as close as possible to Cycles, the difference is not visually appearent, and doesn't exist at boundries**
