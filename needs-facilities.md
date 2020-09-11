# Visit-counter for a Facilities Manager

## Scenario: Report visitor trends during a week of operation

  Given: Monitoring system is in use

  When: Manager asks for report  

  Then Compute and render Trends.

## Scenario: Alert when seating capacity is full

  Given: Monitoring system is in use  

  When: No seats are available in free list  
  
  Then: Render alert to manager
