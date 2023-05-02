# Berkeley-Bike-Pedestrian-Crashes-2021
## Data Diary
### Steps
1. Bold top row and freeze
2. Insert Pivot Table 1
* Values: Case Number (COUNTA)
* Rows: Injury Severity and At-Fault Party

 ![pt1](/images/pivottable1.png)

3. Insert Pivot Table 2
* Values: Case Number (COUNTA)
* Rows: At-Fault Party
* Add Calculated Field in Column C: =B2/$B$10 and autofill

!['pivottable','2'](/images/pivottable2.png)

4. Insert Pivot Table 3
* Values: Case Number (COUNTA)
* Rows: At-Fault Party then Injury Severity
* Copy and paste pivot table 3 into sheet 3 
  * Remove total counts and fill in At-Fault Party for each row to clean for Datawrapper
  
  !['pivottable','3'](/images/pivottable3.png)
  
5. Insert Pivot Table 4
* Values: Case Number (COUNTA)
* Rows: Collision Type then At-Fault Party
* Copy and paste pivot table 4 into sheet 4

6. Insert Pivot Table 5
* Values: Case Number (COUNTA)
* Rows: Collision Type then Injury Severity
* Add calculated field in Column C for cyclist collisions: =C2/$C$12

7. Insert Pivot Table 6
* Values: Case NUmber (COUNTA)
* Rows: Primary Collision Factor
 * Copy and paste pivot table 6 into sheet 5 to use for Datawrapper

