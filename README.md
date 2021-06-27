# Personalized_Realtime_Control: A Proof of Concept to control adaptive facades
Definition: A system with a high degree of freedom that an occupant in a shared work environment can control part of the adaptive elements of a non-conventional AF in real-time behavior

![image](https://user-images.githubusercontent.com/17779829/123534424-7550e480-d760-11eb-8bd7-ebd5ca3774d3.png)

# Limitations of the Current Concept
With respect to the research methodology, since the workflow is genuinely a simulation-driven approach, there are assumptions that influenced the results significantly:
-	From results, we could see there are times that discomfort glare can occur even if the façade section or modules are fully-closed. This finding is due to the existing gaps in the designed non-conventional AF prototype that does not cover the façade 100%. 
-	Selected four shading positions from the original prototype resulted a limited range of view ratio to outdoors in which there is no view ration between 34% and 85% and caused further challenges for the PRC to find an optimum solution to satisfy user demands.
-	The proposed control strategy depends on workstations that are fixed for users with specific view directions, while in reality view fields might change at any seconds. 
-	The methodology is only applicable on adaptive façade typologies that allow user interactions and decentralization mechanisms like foldable responsive facades. So, biomimetic or similar typologies should be excluded. 
-	User behaviour and preferences are replaced with pre-calculated simulations and identified thresholds for each visual comfort metric, that in reality this is not the case and user behaviour might be subjected to many unexpected psychological or physiological aspects that should be sent in real-time manner by user interfaces. 
-	It is true that occupancy profiles are generated stochastically to consider occupant’s presence/absence in the space for each time interval, but as the PRC algorithm is not aware of who will be present or absent in the next 20 minutes. Therefore, the generated 64 shading configurations through the PRC algorithm along with their implications on visual comfort performance are based on the assumption that all occupants will be present in the next time interval as the worst case scenario. However, in a real building with real time input from space and occupants using occupancy sensors and smart phones, you would have stronger control data, and you could have finer time steps than 20 minutes if computational power allows.
