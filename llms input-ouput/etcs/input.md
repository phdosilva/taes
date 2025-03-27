**Role:** You are an **expert analyst in software/technical requirements**.

**Context:** We have **a list of requirements** for a system. Some of these requirements may conflict or contradict each other—either in pairs or in more complex combinations of three or more.

**Goal:** Your task is to **identify and list all actual conflicts** among these requirements **without** introducing any false conflicts. A conflict arises if two or more requirements **cannot logically coexist**. For example:

* One requirement explicitly denies or forbids what another allows or mandates.

* Two requirements specify **incompatible frequencies** (e.g., once a week vs. once a month for the same operation).

* Two or more requirements impose **directly contradictory rules** (e.g., “must be done” vs. “must never be done”) about the same scenario.

* A **three-or-more** requirement conflict arises where no two requirements alone look contradictory, but together they create a logical impossibility.

**Instructions & Format:**

1. **Be thorough and systematic.** Review all requirements carefully to ensure no conflict is overlooked.

2. **Avoid false positives.** If there is ambiguity rather than a direct contradiction, do not report it as a conflict.

3. **Structure your answer** as a clear, enumerated list of conflicts. For each conflict, reference the exact requirement numbers involved and **briefly explain** why they conflict.

Use the format:

 markdown  
CopyEdit  
`1. Req X, Y, (Z, ... if more)`   
   `Conflict Explanation: ...`

*   
4. **No extraneous commentary**: Do not add explanations about your reasoning process or disclaimers about your capabilities. Simply present the conflict list.

5. **Cover all real conflicts** but do not mention anything that is not explicitly or logically stated in the listed requirements.

6. **Final answer only**: Provide only your final conflict findings as a list. Do not include any other text or steps.

---

### **List of Requirements**

1. The current operational status shall be indicated to the driver on the DMI  
2. The current application level shall be indicated on the DMI.  
3. Basic track to train and train to track information via continuous transmission media, i.e. radio. The train detection is provided by trackside  
4. The driver shall acknowledge the level transitions, if requested from trackside. If the driver does not acknowledge after the transition the brake shall be applied. If the driver acknowledges afterwards, the brake can be released  
5. For transitions to and from national Operation (STM) the ETCS shall request, an acknowledgement by the driver.  
6. ETCS shall be compatible with existing national systems listed in the CCS TSI such that it does not interfere with the national systems and is not interfered with by the national systems.  
7. Any transition which occurs while the train is moving shall in principle occur automatically.  
8. ETCS shall not require any driver input for level transitions.  
9. If, as a result of an automatic transition, except for transitions to and from national Operation (STM), the responsibility for the driver increases, the ETCS shall seek an acknowledgement from the driver, whether the train is stationary or not.  
10. "ETCS shall not be required to provide any track-to-train or train-to-track information via continuous transmission media, i.e. radio."  
11. In case the transition has to be acknowledged and the driver fails to acknowledge as required, the ETCS shall initiate a brake application  
12. Basic track to train and train to track information via continuous transmission media, i.e. radio. The train detection is provided by trackside.  
13. ETCS shall not be compatible with any national systems listed in the CCS TSI.  
14. Any transition which occurs while the train is moving shall in principle occur automatically.  
15. If, as a result of an automatic transition, except for transitions to and from national Operation (STM), the responsibility for the driver increases, the ETCS shall seek an acknowledgement from the driver, whether th responsibility for the driver increases, the ETCS shall seek an acknowledgement from the driver, whether the train is stationary or not.  
16. "If the on-board has no valid national values for the current location, default values shall be used by the onboard equipment."  
17. "track to train information provided by national system. Onboard functions provided by national system (STM) in co-operation with onboard ETCS."  
18. ETCS is required to be functional to a maximum train speed of 600 km/h.  
19. ETCS shall not be able to supervise shunting movements.  
20. "In case the transition has to be acknowledged and the driver fails to acknowledge as required, the ETCS shall initiate a brake application"  
21. national values shall be applicable to a defined area.  
22. "track to train information provided by national system. Onboard functions provided by national system (STM) in co-operation with onboard ETCS."  
23. ETCS shall provide the driver with information to allow him to drive the train safely.  
24. "Default values shall be harmonised values, permanently stored in all ERTMS/ETCS on board equipment. ETCS shall provide the driver with information to allow him to drive the train safely."  
25. ETCS shall not be able to supervise train or shunting movements.  
26. "ETCS active for limited train control function; trackside not fitted with any train control system or fitted with a train control system for which no STM is available onboard."  
27. "During the transition period between two operational states (including two different national operations) the supervision provided shall at least ensure the same protection provided by the least restrictive state."  
28. ETCS shall allow for manual speed control by the driver at all times, regardless of the maximum train speed.  
29. Default values shall be harmonised values, permanently stored in all ERTMS/ETCS on board equipment.  
30. "If an ETCS equipped train passes a level transition to one or more levels for which it is not equipped, ETCS shall initiate a brake application."  
31. "If an ETCS equipped train passes a level transition to a line fitted with more than one level, the onboard shall switch to the highest level, according to the priority given by trackside, for which it is equipped."  
32. The current operational status shall be indicated to the driver on the DMI  
33. "If an ETCS equipped train passes a level transition to one or more levels for which it is not equipped, ETCS shall initiate a brake application."  
34. transitions which occur while the train is stationary, shall be initiated automatically or manually as appropriate.  
35. "Trains equipped for ERTMS/ETCS application level 3 shall be able to run on lines equipped with ERTMS/ETCS application level 3, 2, 1 and 0, trains equipped for ERTMS/ETCS application level 2 shall be able to run on lines equipped with ERTMS/ETCS application level 2, 1 and 0 and trains equipped for ERTMS/ETCS application level 1 shall be able to run on lines equipped with ERTMS/ETCS application level 1 and 0."  
36. Once received onboard the national values shall remain valid even if the onboard equipment is switched off.  
37. ETCS shall only be functional up to a maximum train speed of 100 km/h.  
38. ETCS is required to be functional to a maximum train speed of 500 km/h.  
39. national values shall be applicable to a defined area.  
40. "The ETCS on-board shall be capable of receiving national values from the trackside to adapt to national requirements"  
41. Once received onboard the national values shall remain valid even if the onboard equipment is switched off.  
42. ETCS shall not provide any information to the driver during level transitions.  
43. "The ETCS onboard equipment shall automatically switch to the lowest level available on a line, even if it is not equipped for that level."  
44. "Basic track to train information via intermittent transmission media, e.g. balises. This information can be supported by infill, transmitted via balise, loop or radio."  
45. ETCS shall be able to supervise train and shunting movements.  
46. "If an ETCS equipped train passes a level transition to a line fitted with more than one level, the onboard shall switch to the highest level, according to the priority given by trackside, for which it is equipped"  
47. "The driver shall acknowledge the level transitions, if requested from trackside. If the driver does not acknowledge after the transition the brake shall be applied. If the driver acknowledges afterwards, the brake can be released"  
48. transitions which occur while the train is stationary, shall be initiated automatically or manually as appropriate.  
49. ETCS is required to be functional to a maximum train speed of 500 km/h.  
50. For transitions to and from national Operation (STM) the ETCS shall request, an acknowledgement by the driver.  
51. "Trains equipped for ERTMS/ETCS application level 3 shall be able to run on lines equipped with ERTMS/ETCS application level 3, 2, 1 and 0, trains equipped for ERTMS/ETCS application level 2 shall be able to run on lines equipped with ERTMS/ETCS application level 2, 1 and 0 and trains equipped for ERTMS/ETCS application level 1 shall be able to run on lines equipped with ERTMS/ETCS application level 1 and 0."  
52. ETCS shall not require the driver to acknowledge any level transitions, even if requested from trackside.  
53. ETCS shall be able to supervise train and shunting movements.  
54. "If the on-board has no valid national values for the current location, default values shall be used by the onboard equipment."  
55. "Basic track to train information via intermittent transmission media, e.g. balises. This information can be supported by infill, transmitted via balise, loop or radio."  
56. Basic track to train information shall only be provided via radio and not via balises.  
57. "ETCS active for limited train control function; trackside not fitted with any train control system or fitted with a train control system for which no STM is available onboard."  
58. "ETCS shall only be compatible with national systems listed in the CCS TSI if those systems are also equipped with ETCS."  
59. The current application level shall be indicated on the DMI.  
60. "The ETCS on-board shall be capable of receiving national values from the trackside to adapt to national requirements"  
61. "ETCS shall only provide the driver with information to allow him to drive the train safely if the train speed is below 400 km/h."  
62. "During the transition period between two operational states (including two different national operations) the supervision provided shall at least ensure the same protection provided by the least restrictive state."  
63. "national values received from the trackside shall be valid only for a limited time, after which they will be automatically deleted from the onboard equipment."  
64. "ETCS shall be compatible with existing national systems listed in the CCS TSI such that it does not interfere with the national systems and is not interfered with by the national systems."