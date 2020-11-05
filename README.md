# Project2

# DateTimeInherit.java
This class extends DateTimeAbstract and is used to calculate the first and last weekdays of a given month and year.

The method daysOfAnyMonth takes in the integer representation of the month and the year, and uses this find the first and last day of the month. A calendar is created and set to the first day of the month of the given year. The int firstDayOfMonth stores the value of the day of the week of this calendar. Then, to find the last day, the getActualMaximum method is used to return the maximum day of the month. The calendar is then set to this value, and uses the same process as earlier to get the last day of the month. This values are converted to Strings and then printed out in the corresponding statements.

The method toWeekDay takes in the intValue that corresponds to the weekday and returns the corresponding String.
# LetterAvg.java
This class goes through the ArrayList of codes and finds all of the codes with the same letter and prints them.

The method numberOfStationWithLetterAvg clears the ArrayList matching. Then, it iterates through the ArrayList codes and finds the first letter for each Station ID. If the station has a matching ID, it is added to matching and the count of Stations with matching letters represented by count is increased. This method returns count.

The method toString turns the ArrayList matching into an array. Then, a copy of match is made called matchString. This is then turned to String and formatted and creates the String to be outputted, listing all the matching stations.
# MesoInherit.java
This class extends MesoAbstract and finds the letter averages for the MesoStation.

The constructor takes in a MesoStation Staion and stores its Station ID and each letter. It then finds the average int value for all of the characters, and finds the ceiling value, which would round up the average value, and the floor value, which rounds down the average value to the nearest integer. If the decimal portion of the average is greater than .75, the mid value is equal to the ceiling; otherwise, it is equal to the floor. The ceiling, floor, and mid value are then stored in the array avg.

The method calAverage returns the array avg.

The method letterAverage returns the character equivalent to the integer representation mid.
# PosAvg.java
This class finds the MesoStations before and after the given MesoStation so that they can be returned in a String. 

The constructor takes in and saves a Station ID.

The method indexOfStation calls on readFile if the ArrayList codes is empty. It then stores the index of the ID plus 1 and returns this value.

The method readFile reads through the Mesonet file and uses BufferedReader to read through it by line. The Station Id is then pulled from the line and stored in the ArrayList codes.

The method toString overides toString and returns the Strings that have the index of the average and the two StationIDs, if present, that come before and after the StationID.

The method getCodes calls on readFile if codes is empty and returns codes. This is there so the list can be accessed by other classes.
