# Berkeley-Bike-Pedestrian-Crashes-2021
## Data Diary
### Steps
1. Bold top row and freeze
2. Insert Pivot Table 1
* Values: Case Number (COUNTA)
* Rows: Injury Severity and At-Fault Party

![PT1](/images/PivotTable1.png)

3. Insert Pivot Table 2
* Values: Case Number (COUNTA)
* Rows: At-Fault Party
* Add Calculated Field in Column C: =B2/$B$10 and autofill
4. Insert Pivot Table 3
* Values: Case Number (COUNTA)
* Rows: At-Fault Party then Injury Severity
* Copy and paste pivot table 3 into sheet 3 
  * Remove total counts and fill in At-Fault Party for each row to clean for Datawrapper
5. Insert Pivot Table 4
* Values: Case Numner (COUNTA)
* Rows: Collision Type then At-Fault Party
* Copy and paste pivot table 4 into sheet 4

