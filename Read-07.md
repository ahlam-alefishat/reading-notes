# Read-07

## What Google Learned From Its Quest to Build the Perfect Team

google's data-saturated age enables them to examine their work habits and office quirks with a scrutiny that their cubicle-bound forebears could only dream of. Today, on corporate campuses and within university laboratories, psychologists, sociologists and statisticians are devoting themselves to studying everything from team composition to email patterns in order to figure out how to make employees into faster, better and more productive versions of themselves.
- **THE WORK ISSUE**:
- REIMAGINING THE OFFICE
1. How to Build a Perfect Team
2. The War on Meetings
3. The Case for Blind Hiring
4. Failure to Lunch
5. The 'Good Jobs' Gamble
6. Rethinking the Work-Life Equation
7. The Rise of White-Collar Automation
8. The Post-Cubicle Office
9. The New Dream Jobs

##### after looking at over a hundred groups for more than a year, Project Aristotle researchers concluded that understanding and influencing group norms were the keys to improving Google’s teams. But Rozovsky, now a lead researcher, needed to figure out which norms mattered most. Google’s research had identified dozens of behaviors that seemed important, except that sometimes the norms of one effective team contrasted sharply with those of another equally successful group. Was it better to let everyone speak as much as they wanted, or should strong leaders end meandering debates? Was it more effective for people to openly disagree with one another, or should conflicts be played down? The data didn’t offer clear verdicts. In fact, the data sometimes pointed in opposite directions. The only thing worse than not finding a pattern is finding too many of them.

# REST

Representational state transfer and it’s an architectural style for  The whole world wide web  providing standards between computer systems on the web.

# SuperAgent
- light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs.

# Request basics
- A request can be initiated by invoking the appropriate method on the request object, then calling `.then()` (or `.end()` or await) to send the request.



# Dark Sky API :
- The Dark Sky API allows you to look up the weather anywhere on the globe, returning (where available):

* Current weather conditions
* Minute-by-minute forecasts out to one hour
* Hour-by-hour and day-by-day forecasts out to seven days
* Hour-by-hour and day-by-day 


## Weather API Call Types
We provide two types of API requests to retrieve the weather anywhere in the world:

The Forecast Request returns the current weather forecast for the next week.
The Time Machine Request returns the observed or forecast weather conditions for a date in the past or future.

Weather Conditions
* The Dark Sky API offers a full collection of meteorological conditions in 39 different languages, including:

1. Apparent (feels-like) temperature
2. Atmospheric pressure
3. Cloud cover
4. Dew point
5. Humidity
6. Liquid precipitation rate
7. Moon phase
8. Nearest storm distance
9. Nearest storm direction
10. Ozone
11. Precipitation type
12. Snowfall
13. Sun rise/set
14. Temperature
15. Text summaries
16. UV index
17. Wind gust
18. Wind speed
19. Wind direction

*Both forecast and time machine requests return the same weather conditions, in the same convenient JSON format. You can parse the response directly, or use one several community-contributed libraries to interact with our API in the programming language of your choice.*