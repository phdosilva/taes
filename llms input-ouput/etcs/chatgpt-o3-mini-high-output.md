1. Req 4, 5, 9, 15, 47 **vs.** Req 8, 52  
    Conflict Explanation: Some requirements mandate that the driver must acknowledge level transitions (with actions taken if not acknowledged), while others state that no driver input or acknowledgement is required for level transitions.

2. Req 3, 12 **vs.** Req 10   
    Conflict Explanation: Requirements 3 and 12 require providing track-to-train and train-to-track information via continuous (radio) transmission media, whereas Requirement 10 prohibits such provision.

3. Req 44, 55 **vs.** Req 56  
    Conflict Explanation: Requirements 44 and 55 specify that basic track-to-train information may be provided via intermittent media (e.g. balises), while Requirement 56 restricts this information to radio only, excluding balises.

4. Req 6, 64 (and implicitly Req 58\) **vs.** Req 13   
    Conflict Explanation: Requirements 6 and 64 (and the conditional compatibility of Req 58\) require ETCS to be compatible with national systems, while Requirement 13 explicitly states that ETCS shall not be compatible with any national systems.

5. Req 18 **vs.** Req 37, 38, 49  
    Conflict Explanation: Conflicting maximum train speed specifications exist—Requirement 18 demands functionality up to 600 km/h, while Requirements 38/49 limit it to 500 km/h and Requirement 37 limits it to 100 km/h.

6. Req 19, 25 **vs.** Req 45, 53  
    Conflict Explanation: Requirements 19 and 25 prohibit ETCS from supervising shunting (or train) movements, whereas Requirements 45 and 53 require ETCS to supervise both train and shunting movements.

7. Req 31, 46 **vs.** Req 43  
    Conflict Explanation: Requirement 31 (and its duplicate 46\) mandate switching to the highest level for which the train is equipped during multi-level transitions, while Requirement 43 mandates an automatic switch to the lowest level available—even if the train is not equipped for that level.

8. Req 23, 24 **vs.** Req 61  
    Conflict Explanation: Requirements 23 and 24 require that the driver always receive information for safe train operation, while Requirement 61 restricts this provision to situations where the train speed is below 400 km/h.

9. Req 36, 41 **vs.** Req 63  
    Conflict Explanation: Requirements 36 and 41 state that once received, national values remain valid (even if the equipment is switched off), but Requirement 63 limits their validity to a defined period after which they are automatically deleted.  