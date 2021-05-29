# Saftey_Event_Detection


develop a home safety events dispatch service called “Corner“ with the ability to identify emergency situations and ask to dispatch emergency medical help... 

- Define emergency situations
- Gather videos of those cinarios happening
- Compare the training videos against the actual
- Optimize 
ask the user for false positives to make it easy to retrain in the pipeline 

PROCESS:


ALERT
  ASK USER TO DISPATCH ACTION ("WOULD YOU LIKE TO DISPACTH THIS ACTION?), VIA EMAIL TXT PHONE CALL ETC...
    IF YES:
      - ANNOUNCE VIA SPEAKER STANDART OPERATING PROCEDURES TO ASSIST THE EMERGENCY AT HAND SENARIO | "WHAT IS THE BEST COURSE OF ACTION IF THERE IS A {SENARIO} ---            READ ALOUD GOOGLE RESULTS...
      - SEND {GLOBAL DATA}
    IF NO:
      - ASK IF THIS IS A REAL EMERGENCY...
      - REMOVE THE CENARIO VIDEO FROM THE DATASET AND RECUSIVLEY REMOVE IT FROM THE ALGORITHEM
  
 
