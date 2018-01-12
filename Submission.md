# CSC 485D/SENG 480D — Activity #2

### What?
The dataset we have been presented with is Seaspan’s ferry schedule, which shows each scheduled route along with the ferry tasked to it.



### Why?
The stakeholder wants to manipulate the schedule when necessary, and be able to view the status of each ferry. This includes each ferry’s respective status, location, load, and the scheduled route it is on.



### How?
We are using bar graphs to show the current load status of each of the ferries. Additionally, colours are used to visually depict how close each ferry is to their respective capacity. For instance, if a ferry is approaching, or is at full capacity (i.e. > 75%), the bar graph will display red. If it is nearing full capacity (i.e. 60-75%), the graph will display yellow. Otherwise, it will display green (i.e. < 59%).

We will also provide a weekly schedule for each ferry in an agenda-like format. For each scheduled route or maintenance activity that the ferry must undergo, it will appear in the agenda for the given period of time it is not available for other activities. The schedule can be changed to show each ferry’s weekly schedule.



### Assumptions
We are going to assume that Seaspan ferries has the ability to have up-to-date data on the ferries including:
* Capacity of each ferry
* Location of each ferry


### Visualization
![alt text][model]

[model]: https://github.com/InfoVizW2018/activity-2-aj-rhys-nick-team/blob/master/SeaspanModelVisualization.png

