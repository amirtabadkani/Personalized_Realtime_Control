# Personalized_Realtime_Control (PRC): A Proof of Concept to control adaptive facades
Definition: A system with a high degree of freedom that an occupant in a shared work environment can control part of the adaptive elements of a non-conventional AF in real-time behavior

CASE STUDY: An international published Patent was used for this research as a hypothetical case study. Detailed information of the patent can be accessed here:

https://patents.google.com/patent/US20180216399A1/en?inventor=Seyed+Amir+Tabadkani

The proposed control strategy facilitates an integrated algorithmic workflow by creating a live linkage between two different simulation interfaces to overcome the existing challenges as discussed, including: 

(1) simulations using EnergyPlus and Ladybug-tools to cover the energy and comfort-related calculations, 

(2) an offline simulation using Python programming language to program a personalized control.

![image](https://user-images.githubusercontent.com/17779829/123539302-637d3a80-d77c-11eb-8d6b-ef49eb098477.png)

# Limitations of the Current Concept
With respect to the research methodology, since the workflow is genuinely a simulation-driven approach, there are assumptions that influence the results significantly:
-	From results, we could see there are times that discomfort glare can occur even if the façade section or modules are fully-closed. This finding is due to the existing gaps in the designed non-conventional AF prototype that does not cover the façade 100%. 
-	Selected four shading positions from the original prototype resulted a limited range of view ratio to outdoors in which there is no view ration between 34% and 85% and caused further challenges for the PRC to find an optimum solution to satisfy user demands.
-	The proposed control strategy depends on workstations that are fixed for users with specific view directions, while in reality view fields might change at any seconds. 

![image](https://user-images.githubusercontent.com/17779829/123539314-7728a100-d77c-11eb-9d63-df193758c89d.png)

-	The methodology is only applicable on adaptive façade typologies that allow user interactions and decentralization mechanisms like foldable responsive facades. So, biomimetic or similar typologies should be excluded. 
-	User behaviour and preferences are replaced with pre-calculated simulations and identified thresholds for each visual comfort metric, that in reality this is not the case and user behaviour might be subjected to many unexpected psychological or physiological aspects that should be sent in real-time manner by user interfaces. 
-	It is true that occupancy profiles are generated stochastically to consider occupant’s presence/absence in the space for each time interval, but as the PRC algorithm is not aware of who will be present or absent in the next 20 minutes. Therefore, the generated 64 shading configurations through the PRC algorithm along with their implications on visual comfort performance are based on the assumption that all occupants will be present in the next time interval as the worst case scenario. However, in a real building with real time input from space and occupants using occupancy sensors and smart phones, you would have stronger control data, and you could have finer time steps than 20 minutes if computational power allows.

![UI_PRC](https://user-images.githubusercontent.com/17779829/123538281-7e997b80-d777-11eb-8fe1-5558fd6fbc54.jpg)

# References

Daylight in Buildings and Visual Comfort Evaluation: the Advantages and Limitations (Journal of Daylighting)
https://solarlits.com/jd/8-181

Analysis of the impact of automatic shading control scenarios on occupant’s comfort and energy load (Applied Energy)
https://www.sciencedirect.com/science/article/pii/S0306261921003883?via%3Dihub

Design approaches and typologies of adaptive facades: A review (Automation in Construction)
https://www.sciencedirect.com/science/article/pii/S092658052031030X?via%3Dihub

A review of occupant-centric control strategies for adaptive facades (Automation in Construction)
https://www.sciencedirect.com/science/article/pii/S092658052031044X?via%3Dihub

A review of automatic control strategies based on simulations for adaptive facades (Building and Environment)
https://www.sciencedirect.com/science/article/pii/S0360132320301591?via%3Dihub

Innovative control approaches to assess energy implications of adaptive facades based on simulation using EnergyPlus (Solar Energy)
https://www.sciencedirect.com/science/article/pii/S0038092X20305879?via%3Dihub

Integrated parametric design of adaptive facades for user’s visual comfort (Automation in Construction)
https://www.sciencedirect.com/science/article/pii/S0926580518308240?via%3Dihub

For more information, please contact:
stabadkani@deakin.edu.au
