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
# MesoStation.java
# PosAvg.java
