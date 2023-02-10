This is a fork of Keith Miles' project "SDR_RA8876_1280_X_400_Pixels"
which is a "Teensy 4.0/4.1 based SDR using external A/D and D/A converters . Large 1280 X 400 Widescreen display with GT911 Touch Screen"

The display is a wide "candy bar" lcd from BuyDisplay using an RA8876 controller and a GT911 capacitive touch. This lcd panel is a MIPI interface and so there
is another intermediate chip between the 8876 and the display which translates to MIPI. This chip needs to be configured before the display will work.

My intent with this fork is to play around with the display, (probably) convert it back to using the SGTL5000 based Teensy Audio board for at least some  of the
audio processing.
