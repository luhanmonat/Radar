# Radar
The RCWL-0516 can be your personal RADAR unit.  All you need to do is make the analog signal available at the spare pin on the module.

First, cut the trace as shown to free up the unused light sensor pin from the internal ciruit.

![RCWL-CUT1g](https://user-images.githubusercontent.com/46026730/134348202-5f63811a-001e-4fd4-8f2f-c62767aedc71.jpg)


Now put this jumper wire as shown to connect the analog signal to the pin.  Instead of trying to solder to the actual pin on the IC, take the connection from the this capacitor over to where the photocel would go.

![rcwl-wire](https://user-images.githubusercontent.com/46026730/134348589-8e730ba4-b78c-4d09-a5af-54286767bf25.jpg)

You now have a module with both the original digital output, and an analog output.  The analog output has much more information about what this device as detected.
