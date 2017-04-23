# GraphTheory2017
A project for 3rd Year Graph Theory in Software Development GMIT

A project for Graph Theory. Built using Neo4J. 
I was tasked to create a database using data from the GMIT timetable. 
I obtained the data manually using my own timetable for reference. 

You can see the final graph by opening the "FinalGraph.png" file. 

I chose to use the following structure:

Course   --HAS-->     Module --LAB/LECTURE--> Room --TIME--> Day
Lecturer --Teaches-->

I named and implemented the student groups in the LAB relationship, for example "Group C" can be found by looking for "LAB_C".
I split the "Room" node into 3 types "Room", "Lab" and, "Prefab".
I formatted the TIME relationship as such: "T10_11" meaning "From 10am to 11am".

Neo4J was slightly difficult to use at first, but it becomes fun the more you use it.
I have by no means mastered it. But I hope to return to using it in the future.

Thanks for reading,

Philip
