# GENo'Grady*
<b>By Solomon and Raffi </b><br><br><b>Engineering IV, Fall 2024</b><br><br>
*named after the funniest teacher in CHS history<br><br>
Links for our project (onshape, bill of materials, etc.): https://tinyurl.com/GENoGradyLINKS<br>

## Planning

### Problem
We are constantly looking for different ways to move around today, looking for clean sources of energy and a proactive, enjoyable experience on the road. At the same time, many of our charging needs can't wait except for at these stress-free times.

### Concept
Our idea is to build a bike generator to charge small devices, including cell phones. This is modeled off stationary generators which can already function as a solid source of electricity. However, in order to make this mobile so it doesn't seem trivially time-wasting, we can make this function as the bike is mobile. Although this requires more initial input in energy, the electricity which can be harnessed is also well worth it. 

### Research
Initially, we didn't research much. This is actually a common progression in projects, wanting to work quicker rather than effectively. However, we identified this quickly and soon started finding out information on bikes. Solomon brought in his bike in the middle of September, but it was somewhat small and we didn't know if this was a feasible model. As of September 26, we are experimenting with how the bike can generate electricity, and want to start with a stationary model as well as finding a way to mount the bike. The biggest research aspect is to figure out how a bike generates electricity, and how we can make such a model.

### Rough Sketches
Here is a sketch we started with at the beginning of September. It is insufficient in scope and I plan to make a new one. For example, it doesn't say exactly where we will mount the electronics, which is still a big barrier we need to get over.
<br><img src="https://raw.githubusercontent.com/Raffi-Chen/generator/refs/heads/main/Schematics/Initial_oGrady_Schematic.jpg">

<br>Here is a new schematic from October 1st that incorporates more realistic locations on any bike. We are still working on solutions to mount each contraption, especially in area where the parts are elevated in relation to the bike wheel.
<img src="https://github.com/Raffi-Chen/generator/blob/main/Schematics/schematic%2010-1.jpg">

### Diagrams
Below is our initial wiring diagram from the beginning of September. We ended up realizing we didn't need the electronics for the battery, as you don't need a battery to charge a phone, for instance.
<img src="https://raw.githubusercontent.com/Raffi-Chen/generator/86741abf0989b225ce2ef9798456df859e540b64/Schematics/Schematic_Bicycle-alternator_2024-09-13.svg">

This is a schematic which our Link Lab mentor helped us with when we her on October 2nd. This helped us gague a point by which we could jump off of.
<img src="https://raw.githubusercontent.com/Raffi-Chen/generator/refs/heads/main/Schematics/SkyeDrawings.jpg">

Afterwards, we came up with some dimensions that could help us with our more polished drawings. These were finalized on October 4th.<br>
<img src="https://raw.githubusercontent.com/Raffi-Chen/generator/refs/heads/main/Schematics/dimensions.jpg">

This led me to a more finished sketch of the bike with dimensions.<br>
<img src="https://raw.githubusercontent.com/Raffi-Chen/generator/refs/heads/main/Schematics/dimensions%20with%20bike.jpg">

Right now, we are thinking of solutions for how to incorporate an adapter into the grand scheme of the project, since it interferes with the pedal.<br>
<img src="https://github.com/Raffi-Chen/generator/blob/main/Schematics/adapter%20options.jpg">

### Variations
After we complete the main idea of this project, we have several other ideas of where to go. First of all, we could add an LCD display, most importantly checking the status of the generator and if it is communicating with the device it is charging. Additionally, it might help to add a motor so electricity could be stored in a hybrid format and make it easier to pedal. However, this is an ambitious addition and likely will not be visited.

### Function
A working project will be able to harness the spin of motor, generating a certain voltage that is converted by the alternator and subsequently connected to an outlet that can charge devices.

### Bill of Materials
Here is our current Bill of Materials: <a href="https://docs.google.com/spreadsheets/d/1djZTwYndhB5teGSTFrf0gxe1GKC-UUmbuojJfftjynM">BOM</a>

### Pseudocode
As we do not already have a working conception of our code besides the basic LCD code I started with, there is nothing to see here, really. For now, we don't have much of a wiring/coding aspect.

### Schedule
Can be found within our project proposal: <a href="https://docs.google.com/document/d/1L9IMAola1WDWwxcp_cP9-0LkZaMpwWcJz7ReJo8bZH0">Project Proposal</a>

### Success Criteria
We will know we are successful when we have a working generator that can both allow the bike to move relatively seamlessly, while being able to generate an ample amount of electricity.

### Safety
The most important aspect of safety for this project is not to blow up anything, not to kill ourselves ... you know, the basics. Also, no internal combustion engines or any other crazy Solomon stuff. Other than that, we should make sure to clean up after ourselves and not make everything a mess. This aspect should go fine if we're somewhat self-aware.

### Gearbox
We attempted to fabricate a gear box. We decided against this however because the
gears were made of PLA. The gears would imediatley strip if used for this purpose.

## Materials

## Updates

### October 10, 2024
Raffi: We've been distracted for a while and are trying to get back on track. Right now we are figuring out how each part interacts with each other, specifically:
<li>Testing the motor for voltage</li>
<li>Attaching brackets to the back wheel to anticipate the generator being attached to the same vicinity</li>
<li>Discussing the outlet location so that would be able to attach it later. It will go near the handle bars, and we could use o-rings, rather than having to design an entire bracket.</li>

### October 21, 2024
Raffi: Now we're kind of done with the back motor mount, but it's somewhat unstable. We're also not sure if it actually works, especially since there isn't much tension between the motor and the wheel. For our next steps, we should:
<li>Get the hose clamps for the front alternator and middle wires and attach them</li>
<li>Design a box in Onshape for the motor</li>
<li>Think about Arduino components to incorporate</li>

### October-November 18, 2024
Solomon & Raffi: We forgot to update this for several weeks. We finished the motor mount. The gear that is mounted to the tire is slightly off center but throwing a bunch more power at the motor results in it turning anyway.
We have not tested the generator capabilities yet. Our next step is to create a mount for the inverter. That way we can power it and get 120vac out. At first we tried having the gear push against the tire.
After doing this we found the motor imediatley stalls and we can't push the bike at all. After this we put a gear on the tire to have it interact with the motor. Because our welding equipment is defunct we had to bolt it directly
to the wheel which resulted in it being off center. This is because there was no hole for polts so we had to bolt it to the spokes. It worked while being off center. Not sure why our welding equipment doesn't work otherwise we'd
be done in 20 minutes after simply welding the gear to the tire and having that connected to the motor.

### November 21, 2024
Solomon: Welp I was banned from the engineering lab 💀 I can come back next week thankfully. I am very diorganized and I think I don't have enough adderall.
I left random things around the lab and made a mess. I am working on how we can do this. Instead of bolting it at awkward angles, I will weld it to the tire. This way it will be centered and the chains will stop popping off. 
I want to bring my own stick welder into the lab because our current welders run off 240 instead of 120 and we dont have any 240 outlets.
I need to work out how to not blind people in the lab. I also need to ask Mr. Rediesky if I can bring it to the lab. I will use a 3/32" 7018 welding electrode. This is a low hydrogen industrial strength electrode. 
I will not weld it to the axel as the axel is stationary.
