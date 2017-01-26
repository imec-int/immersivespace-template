#IOSONO STARTUP SEQUENCE

Basic template for using the immersive space setup at de krook
##make sure all speakers are off
#SERIOUSLY


##network setup
connect to the wired rednet network
give yourself any non conflicting 192.168.1.XX IP
the IOSONO has 192.168.1.10, the rednets are in an other range,


##rednet

- boot rednet 2 and 6 and iosono
- isosono kriookimmersivespace

##speakers
- power on speakers 
- ...

##software

1. dante virtual sound card  (if needed) ==> 64x64
2. dante controller (load preset DanteSetupImmersiveSpace.xml) 

### to use midi positioning
install https://github.com/krooklab/midi2iosono and RTFM

when up and running start your DAW, ableton, puredata, ... and send midi and audio over 8 channels



#diagnosing a problem

use rednet control 2 to check for the whole connection chain

if rednet 6 gives output signal but no sound CHECK COAXIAL CABLE


