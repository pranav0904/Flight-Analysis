# Flight Arrival Analysis
 
### Environment requirements: <br>
Pandas <br>
sklearn <br>
matplotlib <br>
seaborn <br>

### Dataset Column	Description<br>

YEAR	        Year that the flight took place<br>
QUARTER	        Quarter that the flight took place (1-4)<br>
MONTH	        Month that the flight took place (1-12)<br>
DAY_OF_MONTH	Day of the month that the flight took place (1-31)<br>
DAY_OF_WEEK	        Day of the week that the flight took place (1=Monday, 2=Tuesday, etc.)<br>
UNIQUE_CARRIER	    Airline carrier code (e.g., DL)<br>
TAIL_NUM 	        Aircraft tail number<br>
FL_NUM	            Flight number<br>
ORIGIN_AIRPORT_ID	ID of the airport of origin<br>
ORIGIN	            Origin airport code (ATL, DFW, SEA, etc.)<br>
DEST_AIRPORT_ID	    ID of the destination airport<br>
DEST	            Destination airport code (ATL, DFW, SEA, etc.)<br>
CRS_DEP_TIME	    Scheduled departure time<br>
DEP_TIME	        Actual departure time<br>
DEP_DELAY	        Number of minutes departure was delayed<br>
DEP_DEL15	        0=Departure delayed less than 15 minutes, 1=Departure delayed 15 minutes or more<br>
CRS_ARR_TIME	    Scheduled arrival time<br>
ARR_TIME	   Actual arrival time<br>
ARR_DELAY	   Number of minutes flight arrived late<br>
ARR_DEL15	   0=Arrived less than 15 minutes late, 1=Arrived 15 minutes or more late<br>
CANCELLED	   0=Flight was not cancelled, 1=Flight was cancelled<br>
DIVERTED	   0=Flight was not diverted, 1=Flight was diverted<br>
CRS_ELAPSED_TIME	   Scheduled flight time in minutes<br>
ACTUAL_ELAPSED_TIME	   Actual flight time in minutes<br>
DISTANCE	           Distance traveled in miles<br>
