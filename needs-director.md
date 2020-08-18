# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

  Given: Monitoring System is in use during working day  

  When: Patients visits hospital  

  Then Incremnet count when patient enters and decrement when leaves

## Scenario: Compute parking slots to reserve for visiting specialists

  Given: Specialist Schedule and Parking details  

  When: Prior to specialist visiting time  

  Then Reserve a parking spot for arriving specialist
