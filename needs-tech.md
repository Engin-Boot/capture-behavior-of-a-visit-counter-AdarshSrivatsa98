# Visit-counter technical needs

## Scenario: Recover across restarts of the server that runs the visit-counter

  Given:  Monitoring system is in use  

  When: visit-counter goes down :(  

  Then Resume operation from point of break  

## Scenario: Reconcile counts if the sensor is offline for a while

  Given: Monitoring system is in use  

  When: Sensor is offline for a while  
  
  Then Resume operation from point of break  
