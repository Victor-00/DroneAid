### What is a Drone

- Drone is usually referred to an Unmanned Aerial Vehicle (UAV) 
- Can also be referred to be a part of an Unmanned Aircraft System (UAS)
- UASs use that same UAV but also have additional components, like sensors or tools, to carry out specific objectives like surveillance or firefighting. In short, UAVs are just for flying, while UASs have extra capabilities
- They are either operated autonomously or by a human with remote control


### History of UAVs

#####  **Military Drones**

- The first pilotless vehicles were developed during World War I by britian and USA.
- Britain’s Aerial Target, a small radio-controlled aircraft, was first tested in March 1917
- The American aerial torpedo known as the [**Kettering Bug**](https://en.wikipedia.org/wiki/Kettering_Bug) first flew in October 1918.
- Although both showed promise in flight tests, neither were used operationally during the war
- Archibald Low , An english engineer and head of the Royal Flying Corps Experimental Works , built a radio- controlled plane known as the “Ruston Proctor AT” (Aerial Target). The intention was to place explosives on the plane and fly it into a target, making this the first cruise missile.
- At the end of WWI, Reginald Denny—another Englishman who had served in the Royal Flying Corps—became interested in radio-controlled model planes. This led to him setting up a model plane shop in 1934 and developing his own line of “Dennyplanes.” Which were used for anti-aircraft gunners.
- In 1935 the British produced a number of radio-controlled aircraft to be used as targets for training purposes. It's thought the term 'drone' started to be used at this time, inspired by the name of one of these models, the [DH.82B Queen Bee](https://www.dehavillandmuseum.co.uk/aircraft/de-havilland-dh82b-queen-bee/). Radio-controlled drones were also manufactured in the United States and used for target practice and training.
- Unmanned aircraft also featured during the Vietnam War, when the 4080th Strategic Recon wing of the USAF launched drones from adapted C-130 transport planes. The drones would fly over the designated target area taking photographs, and then parachute to the ground once they were in safe territory, ready to be picked up by helicopter.
- However, it was Israel’s 1982 invasion of Syria that demonstrated more offensive uses for unmanned aerial vehicles (UAVs). As well as flying reconnaissance missions, Israel used drones as electronic decoys and jamming tools, helping them to secure a firm victory over the Syrian Air Force.
- The first fatal US missile attack was in 2002 and resulted in the death of a civilian scrap-metal merchant who was selected as a target by the CIA at least in part because he was “about the same height as Bin Laden.”

##### **Non-Military**

- The 2006 success of the Nintendo Wii with its motion-sensing controller inspired many enthusiasts to create projects that could use those sensors. One such project was MultiWii, which operates on an Arduino board and the board extracted from a Wii controller (which is a cheap source of motion-sensing components).
- Chris Anderson, then editor of _Wired_ magazine, built on Arduino in 2007 to create the ArduPilot (and now ArduCopter). He created a community site, [DIYDrones.com](http://DIYDrones.com), to support the project. [DIYDrones.com](http://DIYDrones.com) has since added a commercial arm—3DRobotics— which sells ready-build ‘copters and fixed-wing aircraft, as well as its own flight controllers.
- But multicopters, or drones, were something of a minority interest until a little-known car entertainment company, Parrot, grabbed the world’s attention with the AR.Drone at the 2010 International Consumer Electronics Show (CES) in Las Vegas.
- With somewhat less fanfare, developers who were already working on an open-source autopilot system for fixed-wing model aircraft began work on ArduCopter in the summer of 2010. This was released the following summer and enabled enthusiasts to construct their own quadcopter, similar to the way in which they could already build other model aircraft.
- By 2013, Chinese company DJI had built up an impressive array of components for enthusiasts and professionals, including one of the most respected flight controllers (the brain of the drone) on the market. When DJI started pulling components together to launch its Phantom quadcopter, taking advantage of its complete vertical control of manufacturing as well as marketing, it quickly grabbed the lion’s share of the ‘copter market as well.
- they targeted creatives looking for an aerial photography and video solution, so DJI set about making the Phantom easier to use, with improved picture-taking capabilities. Later, DJI and other firms sought to widen that market further. In addition to the product itself, DJI’s marketing blitz was bigger than anything that came before it, so the Phantom’s “halo effect” (and people’s suspicion of it) is still being felt across the industry.


### Types of UAVs

#### Rotary Drone

###### Multi-Rotor

- These are most common and widely recognized type of drones. 
- They are characterized by having more than two rotors with classfication based on the number of rotors: tricopter, quadcopter, hexacopter, octocopter. 
- The flight of a multi-rotor is controlled by precisely varying the rotational speed of each individual motor.
- his differential thrust allows for immediate and precise control over the aircraft's pitch, roll, yaw, and altitude. This control system grants them exceptional maneuverability, the ability to hover motionless, and the capacity to operate safely in confined spaces and close to structures.
- The primary disadvantage of the multi-rotor design is its inherent inefficiency.
- A significant amount of energy is constantly expended simply to counteract the force of gravity and keep the aircraft airborne. This high power consumption, coupled with the limited energy density of current battery technology, results in short flight times, typically ranging from 20 to 40 minutes.

###### Single-Rotor

- Single-rotor UAVs are structurally and aerodynamically analogous to conventional helicopters.
- They feature a single, large main rotor to generate lift and a smaller, vertically-oriented tail rotor to counteract torque and provide directional control.
- The main rotor blades are significantly longer and more airfoil-like than the propellers on a multi-rotor, functioning more like spinning wings.
- This design provides a much greater aerodynamic efficiency
- They can carry substantially heavier payloads than multi-rotors and can achieve significantly longer flight times
- This makes them the preferred rotary-wing platform for missions requiring both VTOL/hover capability and the ability to carry heavy, specialized sensors, such as high-end aerial LiDAR laser scanners for detailed surveying or large-volume spray tanks for precision agriculture
- However, these capabilities come at the cost of increased complexity and expense. The mechanics of a single-rotor system, with its swashplates, linkages, and gearboxes, are far more intricate than those of a multi-rotor

#### Fixed Winged Drone

- Fixed-wing UAVs operate on the same aerodynamic principles as conventional airplanes.
- They possess a rigid wing structure that generates lift as the aircraft moves forward through the air, propelled by an engine, typically driving a propeller.
- The primary advantage of the fixed-wing design is its exceptional energy efficiency.
- Gas-powered fixed-wing platforms can achieve flight times of 16 hours or more, making them the superior choice for missions that require covering vast areas, such as large-scale aerial mapping, agricultural surveying, pipeline and power line inspection, and long-range military intelligence, surveillance, and reconnaissance (ISR).
- However, this efficiency comes with significant operational constraints. Fixed-wing UAVs cannot hover in a fixed position, as they must maintain constant forward momentum to generate lift. This makes them unsuitable for tasks requiring stationary observation or operation in confined areas.
- Furthermore, they typically require a runway or a launch system

#### Hybrid Vertical Take-Off and Landing (VTOL) Drone

- Hybrid VTOL UAVs represent a significant engineering effort to synthesize the most desirable characteristics of fixed-wing and rotary-wing aircraft into a single, versatile platform.
- These systems are designed to overcome the primary limitations of the other two main categories: the need for a runway for fixed-wing UAVs and the limited endurance of multi-rotors.
- They achieve this by integrating both systems: rotors (typically two or four) provide vertical lift for takeoff and landing, while a fixed wing provides aerodynamic lift for efficient, long-range forward flight.
- Hybrid VTOLs are not without their disadvantages, the design complexity is greater than that of a pure fixed-wing or multi-rotor system, which can increase cost and introduce additional points of potential failure.
- Furthermore, many designs represent an engineering compromise; they may not be as aerodynamically efficient in forward flight as a dedicated fixed-wing platform, nor as stable or maneuverable in hover as a dedicated multi-rotor.

### Components of a Multirotor drone

#### Mechanical Components

 **Frame and Arms :-**
 - The frame, or chassis, serves as the drone's structural backbone
 - The design and material of the frame are critical, as they directly influence the drone's agility, payload capacity, and overall strength.
 - The choice of material involves a crucial trade-off between strength, weight, and cost.

**Materials :-**
- High-performance and racing drones predominantly use carbon fiber for its exceptional strength-to-weight ratio, rigidity, and durability.
- Aluminum alloys serve as a cost-effective alternative, offering good durability and strength, making them suitable for commercial and industrial drones that operate in rugged environments.
- For consumer and hobbyist drones, engineering plastics like Acrylonitrile Butadiene Styrene (ABS) and composites are common due to their low cost and ease of manufacturing through processes like injection molding.

**Design :-**
- Extending from the central frame are the arms that hold the motors.
- The length of these arms affects flight characteristics; longer arms provide greater stability, which is beneficial for aerial photography, while shorter arms allow for better maneuverability, a key trait for racing drones.
- Frame geometry also plays a role, with **X-frame** designs being popular for racing due to their balanced weight distribution and agility, and **H-frame** designs offering more space for mounting components in freestyle and photography drones.

**Motors :-**
- Multirotor drones almost exclusively use brushless DC (BLDC) motors for their high efficiency, reliability, power-to-weight ratio, and long lifespan.
- Most multirotor motors are of the "outrunner" design, where the outer case of the motor (the rotor, containing permanent magnets) spins around the internal stationary windings (the stator).
- This configuration produces higher torque at lower RPMs (revolutions per minute), which is ideal for driving the large propellers needed to lift heavy payloads.
- To achieve stable flight and control, the motors work in pairs. On a quadcopter, two motors spin clockwise (CW) and two spin counter-clockwise (CCW). This arrangement of counter-rotating propellers on opposite arms cancels out the motor torque, preventing the drone from spinning uncontrollably on its vertical axis.
- A motor's performance is defined by its KV rating, which indicates how many RPM it will turn per volt of electricity supplied.
- High-KV motors (e.g., 1900-2500KV) spin faster and are used in racing drones for speed, while low-KV motors (e.g., 300-900KV) spin slower but provide more torque, making them suitable for heavy-lift drones with larger propellers.

**Propellers :-**
- Attached directly to the motors, propellers are the airfoils that convert the motor's rotational energy into aerodynamic thrust, generating the lift required for flight.
- Key design parameters include **diameter** and **pitch**. Larger diameter propellers move more air and generate more thrust, making them suitable for lifting heavy payloads, but they require more powerful, low-KV motors.
- Pitch is the theoretical distance a propeller moves forward in one rotation; a higher pitch allows for higher top speeds but is less efficient and requires more power, while a lower pitch offers better acceleration and control, ideal for cinematic flying.
- The number of blades also affects performance. **Two-blade** propellers are generally the most efficient and are favored for long-range flight. **Three-blade** propellers offer a good balance of thrust and efficiency, providing better "grip" in the air, which makes them the most popular choice for freestyle and racing drones. Propellers with four or more blades provide even more thrust and stability but at the cost of reduced efficiency and shorter flight times.
- Propellers are made from various materials to suit different applications. **Plastic** (like ABS) and **polycarbonate** are common for their low cost and flexibility
- For high-performance applications, **carbon fiber** is preferred due to its rigidity and light weight, which reduces vibration and improves aerodynamic efficiency, leading to longer flight times.

**Landing Gear :-**
- This component provides a stable base for the drone during takeoff and landing
- Protects the undercarriage and sensitive payloads like cameras.
- Designs range from simple fixed legs, common on many commercial drones, to more advanced retractable systems that move out of the way during flight to provide an unobstructed camera view and improve aerodynamics.
- Some specialized designs integrate grasping mechanisms or are designed to adapt to uneven terrain.




#### Electronic Components

**Flight Controller(FC) :-**
- The flight controller is the "brain" of the drone, a circuit board containing a microprocessor and a suite of sensors.
- It processes inputs from the pilot's remote control and real-time data from its onboard sensors to maintain stable flight.
- The FC's primary task is to run complex algorithms that calculate the precise speed each motor needs to spin to achieve the desired movement—whether it's hovering in place, pitching forward, rolling sideways, or rotating.
- The FC relies on an **Inertial Measurement Unit (IMU)**, which combines an accelerometer and a gyroscope, to measure the drone's angular velocity and linear acceleration, providing the fundamental data needed for stabilization.

**Electronic Speed Controllers (ESCs) :-**
- Each motor is paired with an Electronic Speed Controller, or a single "4-in-1" ESC board is used for all motors. The ESC acts as an essential intermediary, taking the low-power digital signal from the flight controller and translating it into a high-power, three-phase electrical current that drives the brushless motor at the commanded speed.
- The ESC's ability to rapidly and precisely adjust the voltage sent to the motors thousands of times per second is what allows for the drone's agility and stability.
- Key specifications for an ESC include its maximum continuous **current rating** (in amps) and the **voltage** range it can handle, which must be compatible with the motors and battery.

**Battery :-**
- The power source for nearly all multirotor drones is a Lithium Polymer (LiPo) battery, chosen for its high energy density and ability to discharge power quickly to meet the high demands of the motors.
- Key specifications include **voltage**, which is determined by the number of cells connected in series (indicated by the "S" rating; e.g., a 4S battery has four 3.7V cells for a nominal voltage of 14.8V).
- **Capacity**, measured in milliamp-hours (mAh), dictates the battery's energy storage and is a primary factor in determining flight time.
- The **discharge rate (C-rating)** indicates how quickly the battery can safely release its energy, a crucial factor for high-performance racing and freestyle drones that require sudden bursts of power.

**GPS Module :-**
- A Global Positioning System (GPS) module is a vital sensor for many drone applications, providing precise geographical location data by receiving signals from a network of orbiting satellites.
- This allows for a range of advanced functions, including autonomous waypoint navigation, position hold (where the drone maintains its location without pilot input), and a critical safety feature known as "return-to-home," which automatically brings the drone back to its takeoff point in case of signal loss or low battery.


**Radio Transmitter and Receiver :-**
- This system forms the communication link between the pilot and the drone.
- The **transmitter** is the handheld remote control used by the pilot.
- signals are sent across multiple **channels**, with the four primary channels controlling throttle, yaw, pitch, and roll.
- The **receiver** is a small component on the drone that captures these signals and passes them to the flight controller for execution.
- The transmitter and receiver must be compatible and "bound" to each other to establish a secure communication link.


### 6 Degrees of freedom of a drone

#### Translational Movement :-

- **Surge (Forward/backward) :** This is the drone's movement along its longitudinal Y-axis. A multirotor achieves this by tilting its body forward or backward. To move forward, the flight controller increases the speed of the rear motors and decreases the speed of the front motors, causing the drone to pitch forward and accelerate in that direction. The reverse action is performed to move backward.
- **Sway (Left/Right) :** This refers to the side-to-side motion along the transverse X-axis. Similar to surging, swaying is accomplished by tilting. To sway right, the motors on the left side spin faster than those on the right, causing the drone to roll to the right and move sideways.
- **Heave (Up/Down):** This is the vertical movement along the Z-axis. Unlike surge and sway, heave does not require the drone to tilt. To ascend, the flight controller increases the speed of all four motors equally, generating more lift than the force of gravity. To descend, it decreases the speed of all motors, reducing lift. A stable hover is maintained when the total lift equals the force of gravity.

#### Rotational Movement :- 

- **Roll:** This is the rotation around the longitudinal (Y) axis, causing the drone to tilt left or right, like a barrel roll. It is controlled by creating a thrust differential between the motors on the left and right sides. Speeding up the right-side motors while slowing the left-side motors will cause the drone to roll to the left.
- **Pitch:** This is the rotation around the transverse (X) axis, making the drone's nose tilt up or down. This is achieved by increasing the speed of the rear motors while decreasing the speed of the front motors, which causes the drone to pitch forward.
- **Yaw:** This is the rotation around the vertical (Z) axis, allowing the drone to turn left or right without changing its position. Yaw is controlled by leveraging the torque generated by the spinning propellers. On a quadcopter, two motors spin clockwise and two spin counter-clockwise to cancel out torque during a hover. To yaw, the flight controller increases the speed of one pair of diagonal motors (e.g., the clockwise ones) and decreases the speed of the other pair, creating a net torque that rotates the aircraft.




### Purposes and uses of different types of UAVs

#### Multi-Rotor UAVs :-

- **Aerial Photography and Cinematography:** Their stability and controlled camera movements make them the perfect platform for professional filmmaking, amateur photography, and media production.
- **Infrastructure Inspection:** Multi-rotors excel at close-quarters visual and thermal inspections of hard-to-access structures like bridges, wind turbines, power lines, and cell towers.
- **Public Safety and Emergency Response:** Law enforcement and first responders use them for surveillance, crowd monitoring, accident scene reconstruction, and disaster management. Firefighters use thermal-equipped multi-rotors to identify hotspots through smoke.
- **Construction and Surveying:** They are used for monitoring construction progress, conducting 3D scans, and performing small-scale mapping tasks where VTOL is necessary.
- **Recreational and Hobbyist Flying:** Due to their ease of use and affordability, quadcopters are the most popular choice for recreational flying and personal enjoyment.

#### Fixed-Winged UAVs :-

- **Precision Agriculture:** Farmers use fixed-wing drones to survey thousands of acres of farmland, monitor crop health, and analyze soil conditions to optimize yields and reduce costs.
- **Large-Scale Mapping and Surveying:** Their ability to cover vast areas makes them the ideal choice for creating high-resolution topographic maps and 3D models for industries like land surveying, mining, and environmental monitoring.
- **Long-Range Inspection:** They are used for inspecting linear infrastructure such as pipelines, power lines, and coastal areas.
- **Military Intelligence, Surveillance, and Reconnaissance (ISR):** Large fixed-wing platforms, categorized as Medium Altitude, Long Endurance (MALE) and High Altitude, Long Endurance (HALE), are essential military assets for strategic, long-range reconnaissance and persistent surveillance over vast territories.
- **Environmental and Wildlife Monitoring:** Their long flight times are valuable for conducting wildlife surveys, tracking animal populations, and monitoring large ecosystems like forests and oceans.

#### Single-Rotor UAVs :-

- **Heavy-Lift and Cargo Transport:** Their high payload capacity makes them ideal for industrial and military logistics, transporting supplies, medical equipment, or other heavy cargo to remote or inaccessible areas.
- **Advanced Aerial Surveying:** They are the preferred platform for carrying heavy, specialized sensors like high-end LiDAR laser scanners for creating precise 3D maps and digital elevation models.
- **Precision Agriculture:** Single-rotor drones are widely used for agricultural tasks that require heavy payloads, such as carrying large tanks for the precise aerial spraying of pesticides or fertilizers.
- **Military and Defense Operations:** In addition to cargo transport, they are deployed for demanding surveillance, reconnaissance, and border patrol missions that require both endurance and VTOL capability.
- **High-End Cinematography:** Their stability and ability to carry professional-grade cameras and lenses make them suitable for high-quality filmmaking.


#### Hybrid VTOL UAVs :-

- **Package and Cargo Delivery:** The ability to travel long distances efficiently and then land vertically in a precise location makes them a leading candidate for future logistics and delivery networks, such as Amazon's Prime Air.
- **Mapping in Inaccessible Areas:** They are perfect for large-scale surveying and mapping missions in remote or rugged terrain where no runway is available for takeoff or landing.
- **Search and Rescue:** Hybrid VTOLs can cover vast search areas quickly and efficiently, then hover over a location of interest or land in a confined space to deliver aid.
- **Urban Air Mobility (UAM):** The VTOL capability is a foundational technology for future UAM systems, which envision air taxis transporting people and goods within cities.


### **Different famous drone companies and what they do**

#### DJI (Da-Jiang Innovations)

-  DJI is the undisputed global leader in the civilian drone market, holding over 70% of the market share.
- The company is known for its high-quality, user-friendly drones that made aerial photography accessible to consumers and professionals.
- Its famous consumer lines, like the Mavic and Phantom series, are celebrated for their advanced flight control and high-resolution cameras, while the Matrice series serves enterprise clients in public safety, inspection, and surveying.

#### **Parrot SA**

- A French company, Parrot was an early pioneer in the consumer drone space but has since shifted its focus to professional and military applications.
- As a leading European drone manufacturer, Parrot offers a secure alternative for sensitive government and defense contracts.
- Its flagship ANAFI series is known for its compact design and is used for aerial mapping, security, and industrial inspections.


#### Skydio

- Skydio has become the leading U.S. drone manufacturer by focusing on cutting-edge autonomous flight technology. 
- The company's drones are powered by advanced AI and sophisticated obstacle avoidance systems, allowing them to navigate complex environments with minimal human intervention.
- Targeting enterprise, public safety, and defense sectors, Skydio drones excel at tasks requiring close-proximity flight, such as bridge inspections and tactical situational awareness.

#### **AeroVironment Inc.**

- A veteran in the aerospace industry, California-based AeroVironment is a top supplier of small, tactical drones to the U.S. military and its allies.  
- The company specializes in lightweight, hand-launched UAVs like the Raven and Puma for reconnaissance.
- AeroVironment is also famous for pioneering "kamikaze" drones with its Switchblade loitering munitions, which combine surveillance with a precision strike capability and have been used effectively in global conflicts.