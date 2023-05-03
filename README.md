# Bicycle Safety in a Bifurcated Neighborhood

A proposal to establish a protected bike lane has become North Berkeley’s most contentious issue. Here’s a look at bicycle safety in Berkeley, CA and one of the city’s plans to improve it.

**By: Laura Fitzgerald**

It was May of 2022 when the Berkeley City Council first approved a proposal to incorporate a protected, two-way bike lane on Hopkins Street in North Berkeley. Now almost a year later, those plans have halted after Berkeley’s City Manager, Dee Williams-Ridley, wrote a letter to the city’s mayor and city councilmembers asking that they reschedule the April 18 Special Session to vote on the proposal, citing concerns that the city is understaffed and cannot sufficiently evaluate the proposal and its potential impacts. 

The city’s decision to delay comes after a year of tension between North Berkeley residents who either support or oppose the proposal. Lawn signs reading “Save Hopkins Street” began to appear in the windows of homes and small businesses and the community became further divided between those wanting increased bicycle infrastructure and those concerned about the availability of parking spaces.

“I’m glad that the whole thing has been postponed and I hope it will stay postponed forever,” said a woman who was shopping near the corner of Hopkins St. and California St. She refused to give her name, saying that the issue had become so personal between her and her neighbors. “I think it’s totally biased towards bicycles and they haven’t taken anybody else into consideration,” she said.

“We need safer routes for kids on bikes, families on bikes, commuters on bikes,” said a man shopping on Hopkins Street who also wanted to remain unnamed. “It has not been safe, we need to switch over to a more bicycle friendly infrastructure. I think people are so focused on losing a little bit of parking that they aren’t willing to see the bigger picture and I think it’s unfortunate.”

Some city officials and representatives have pointed out that bicycle and pedestrian collisions in the City of Berkeley have decreased over the last five years. While that is true, the most recent bicycle and pedestrian collision data for a full year released by the Berkeley Police Department was for 2021 and indicates that bikes and cars still do not always coexist on city streets.

During 2021, there were 141 collisions involving either a bicycle or pedestrian. 84 of them involved a bicycle in some manner. When it comes to who was to blame for these collisions, BDP’s data indicates that it was fairly even between cyclists and drivers.

![DataViz1](https://www.datawrapper.de/_/LvOC2/)

And the cause for these collisions? Unsafe speed was most frequently the primary collision factor for crashes involving a cyclist. That was the case for when drivers and also when bicycles were the party at fault for the collision.

![DataViz2](https://datawrapper.dwcdn.net/wOCvU/1/)

The Berkeley Police Department's data indicates that cars are not always to blame for collisions involving cars and bicycles. But many cyclists are still hesitant to ride in vehicle traffic. Benicia Rush is no different.

“I only ride my bike on trails. I never would do it on the street ever,” Rush said. “But if it was protected, specifically just for bikes, then yeah. I would do that and I would do that with my son.”

Out of the 83 collisions involving a cyclist, 76% (68 incidents) resulted in moderate injuries (while 21.7% (18 incidents) resulted in serious injuries. There were no fatalities among cyclists in 2021, but there were five pedestrians that died due to collision incidents that involved a vehicle. Pedestrians and cyclists may have the right of way, yet that does not end up being enough protection for many choosing to travel by bike or on foot. This is the very fear that has led many Berkeley bikers to advocate for protected bike lanes to physically separate vehicle and pedestrian traffic. 

https://www.datawrapper.de/_/sv7xc/

The Berkeley Police Department has noted the need for bicycle safety awareness among the city’s busy streets. Sergeant Andrew Frankel in BDP’s Traffic Bureau pointed out that the month of May in the city of Berkeley is Bicycle Safety Awareness Month and was established by a grant from the California Office of Traffic Safety. 

“I can tell you that we stand behind the promotion of traffic safety through data-driven, community-informed, outreach and enforcement. The grant we received through the Office of Traffic Safety enables this approach,” Frankel said. “The Traffic Bureau (three to four officers) will be conducting one operation a week for the next five weeks to spread the message.”

The question that remains is whether BPD’s action and outreach efforts are enough for Berkeley bikers who are advocating for protected bike lanes, like the lane proposed for Hopkins Street.

Just as the data illustrated above sheds light on literal collisions between bicycles and cars in the Berkeley area, the debate around the Hopkins bike lane proposal has come to represent  the collision between two different visions for safer, more accessible city streets.




#Data Diary
For this analysis, I used a dataset from the Berkeley Police Department that recorded bicycle and pedestrian collision data from the year of 2021. The dataset was clean enough to navigate, but additional cleaning was needed for some of my pivot tables to be able to use for Datawrapper.
##Steps
1. Bold top row and freeze
2. Insert Pivot Table 1
* Values: Case Number (COUNTA)
* Rows: Injury Severity and At-Fault Party

 ![pivottable1](/PivotTable1.png)

3. Insert Pivot Table 2
* Values: Case Number (COUNTA)
* Rows: At-Fault Party
* Add Calculated Field in Column C: =B2/$B$10 and autofill

![pivottable2](/PivotTable2.png)

4. Insert Pivot Table 3
* Values: Case Number (COUNTA)
* Rows: At-Fault Party then Injury Severity
* Copy and paste pivot table 3 into sheet 3 
  * Remove total counts and fill in At-Fault Party for each row to clean for Datawrapper
  
  ![pivottable3](/PivotTable3.png)
  
5. Insert Pivot Table 4
* Values: Case Number (COUNTA)
* Rows: Collision Type then At-Fault Party
* Copy and paste pivot table 4 into sheet 4

 ![pivottable4](/PivotTable4.png)

6. Insert Pivot Table 5
* Values: Case Number (COUNTA)
* Rows: Collision Type then Injury Severity
* Add calculated field in Column C for cyclist collisions: =C2/$C$5

  ![pivottable5](/PivotTable5New.png)


7. Insert Pivot Table 6
* Values: Case NUmber (COUNTA)
* Rows: Primary Collision Factor
 * Copy and paste pivot table 6 into sheet 5 to use for Datawrapper

   ![pivottable6](/PivotTable6.png)


