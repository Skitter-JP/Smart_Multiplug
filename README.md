# Smart Multiplug

In this project I have built a basic multiplug with 8 outputs, each output has a on/off switch, the input power also have a power switch.


This project started because I was looking for some decent multiplugs with individual switches that was also mountable to a table or wall, but I found nothing decent and decided to make my own.

The first version was done in a rush and did not look very professional but, it worked.

Below are the completed units of version 1 which were mounted below my desk.

<img src="/Images/V1/Boxes_mounted_V1.JPG" width=55%>

The second version had a lot more planning put into it, most notably a Sonoff POW 2 was used, this gives the ability to control the power to the device remotely, but more importantly it gives the ability to measure voltage, current and power factor.

<img src="/Images/V2/Smart_multi_plug_and_Dimmer.JPG" width=55%>

# Stencil Guides

On both versions the holes were cut manually with a Dremel, a stencil was made in Google Sketchup and then a 1-1 drawing was printed.

This printed stencil was this cut and taped onto the enclosures, this was then used as my guide when cutting the boxes, this technique works really well but, cutting plastic manually is horrible and time consuming.

Below we can see the stencil that was used to cutout two LED holders, A Power Button and Input Power Connector

<img src="/Images/V2/Cutting_Side_stencil.JPG" width=55%>

In this image we can see the stencil that was used in version 2, the holes for the plugs and switched have been cut, you can see that I have used masking tape to hold the stencil to the lid.

<img src="/Images/V2/Cutting_Side_stencil_top.JPG" width=55%>

Here is a photo of me cutting the lid for version 1, this clearly shows how much plastic dust is apparent when cutting these plastic enclosures.

<img src="/Images/V1/Cutting_Stencil_Top_Lid.JPG" width=55%>

Here is a screenshot of the stencil in Sketchup.

<img src="/Images/V2/Stencil_Top_Lid_Sketchup.JPG" width=55%>


## Version 1

Here are construction images from Version 1.

The stencil for the lid has been secured and is ready for cutting.

<img src="/Images/V1/Stencil_Top_Lid.JPG" width=55%>

The holes have been cut and the swtiches/plugs have been test fitted

<img src="/Images/V1/Top_Lid.JPG" width=55%>

The plugs/switches have been mounted to the lid and the connections have been made.
A din rail was mounted to the bottom of the enclosure, and all connections are screwed to 3 separate terminal blocks for Earth, Neutral and Live.

In hindsight, I should of twisted the cables from each plug to the connector blocks, this could of helped with the mess and maybe reduce some EMI noise.

Some ferrels should of been crimped to the wire as well.

<img src="/Images/V1/Internal_Box_V1.JPG" width=55%>


## Version 2

Here are construction images from Version 2.

The holes have been cut and the plugs and switches are being mounted

<img src="/Images/V2/Lid_Plug_Installation.JPG" width=55%>

A din rail was cut and installed to the bottom area of the enclosure
3 Connector blocks were mounted with a Sonoff POW2.

<img src="/Images/V2/Internals_No_wires.JPG" width=55%>

The internal button, and LEDs were routed to the outside of the case, the mounting brackets and LED holders are plastic, was done because the circuit in the Sonoff POW2 are not isolated from mains.

<img src="/Images/V2/LED_Button_SONOFF.JPG" width=55%>

The wire lengths for each plug were measured, cut and installed to the top lid.

<img src="/Images/V2/Top_Lid_Complete.JPG" width=55%>

The wires from the top lids have been connected to the copper terminals.

I ensured that the wires were long enough such that the lid can lie next to the bottom part of the enclosure with no restrictions.

This could help in the future if any maintenance needs to be done.

<img src="/Images/V2/Connections.JPG" width=55%>

Here we can see the final image before the unit was sealed.

<img src="/Images/V2/Complete_Unit.JPG" width=55%>

## Version 3

A third version is being planned and will hopefully be built in the future when money and time become available.

This third version will consist of the following.

- A custom aluminum cut enclosure with laser etched engravings
- Each output will have its own individual current, voltage and temperature sensing units with a dedicated power relay
- Each output will also have its own dedicated microcontroller
- A main microcontroller will be implemented and will communicate with the other microcontrollers via CAN or some other protocol
- The main microcontroller will have an RJ45 connection for a physical connection to a LAN
- The main microcontroller will also support a Wi-Fi connection
- The mains input will have surge protection and fuses
- There will be 3 subversions with 8x, 10x and 12x outputs

## Questions/Orders

If you have any questions, orders or would like to collaborate with some other projects then, please contact me.



