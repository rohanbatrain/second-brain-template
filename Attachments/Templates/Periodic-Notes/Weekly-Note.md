---
tags: weekly-note, [[<%tp.date.now("YYYY-[M]MM")%>]]
links: [[Weekly-Reviews]]
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
week-summary:
week-achievements:

---

# <% tp.file.title %>

---

[[<%tp.date.now("YYYY-[W]ww", -9)%>|Past Week]] <== [[<%tp.date.now("YYYY-MM")%>|This Month]] ==> [[<%tp.date.now("YYYY-[W]ww", 2)%>|Next Week]]

## Days
---

1. [[<%tp.date.now("YYYY-MM-DD", -6)%>]]
2. [[<%tp.date.now("YYYY-MM-DD", -5)%>]]
3. [[<%tp.date.now("YYYY-MM-DD", -4)%>]]
4. [[<%tp.date.now("YYYY-MM-DD", -3)%>]]
5. [[<%tp.date.now("YYYY-MM-DD", -2)%>]]
6. [[<%tp.date.now("YYYY-MM-DD", -1)%>]]
7. [[<%tp.date.now("YYYY-MM-DD")%>]]

## Visualisation 
---

### Week Days Summary

```dataview
TABLE day-summary as Summary
FROM "Notes/Periodic-Notes/Daily-Notes"
WHERE date >= <%tp.date.now("YYYY-MM-DD", -6)%> AND date <= <%tp.date.now("YYYY-MM-DD")%>
SORT date ASC
LIMIT 7
```


### Efficiency Score
---

 ```tracker
searchType: frontmatter
searchTarget: mood, health, productivity, stress-levels, cried-counter
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Mood, Health, Productivity, Stress Levels, Cried Counter 
line:
    title: Efficiency Score
    lineColor: yellow, green, orange, blue, red
    yAxisLabel: Value
    yMin: 1
    yMax: 10
    showLegend: true
	legendOrientation: vertical
```


#### Summary

##### Mood

```tracker
searchType: frontmatter
searchTarget: mood
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
summary:
    template: "My average mood for this week was {{sum()}}."
    style: "font-size:20px;color:yellow;margin-left: 50px;margin-top:00px;"
```


##### Health

```tracker
searchType: frontmatter
searchTarget: health
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
summary:
    template: "My average health for this week was {{sum()}}."
    style: "font-size:20px;color:yellow;margin-left: 50px;margin-top:00px;"
```

##### Productivity

```tracker
searchType: frontmatter
searchTarget: productivity
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
summary:
    template: "My average productivity for this week was {{sum()}}."
    style: "font-size:20px;color:yellow;margin-left: 50px;margin-top:00px;"
```

##### Stress levels

```tracker
searchType: frontmatter
searchTarget: stress-levels
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
summary:
    template: "My average stress levels for this week was {{sum()}}.."
    style: "font-size:20px;color:yellow;margin-left: 50px;margin-top:00px;"
```


### Health
---

#### Meditation Duration
---

```tracker
searchType: frontmatter
searchTarget: morning-mental-health-meditation-duration, evening-mental-health-meditation-duration 
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Morning-Meditation, Evening-Meditation
line:
    title: Meditation
    lineColor: orange, yellow
    yAxisLabel: Time
    yAxisUnit: Mins
    yMin: 0
    showLegend: true
	legendOrientation: vertical
```

> Morning Weekly Summary

```tracker
searchType: frontmatter
searchTarget: morning-mental-health-meditation-duration
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Morning-Meditation
summary:
    template: "Longest Streak: {{maxStreak()}} day(s)\nLongest Breaks: {{maxBreaks()}} day(s)\nLast streak: {{currentStreak()}} day(s)"
```

> Evening Weekly Summary

```tracker
searchType: frontmatter
searchTarget: evening-mental-health-meditation-duration
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Evening-Meditation
summary:
    template: "Longest Streak: {{maxStreak()}} day(s)\nLongest Breaks: {{maxBreaks()}} day(s)\nLast streak: {{currentStreak()}} day(s)"
```


#### Weight Tracker
---

```tracker
searchType: frontmatter
searchTarget: weight-tracker
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Weight
line:
    title: Performance Score
    lineColor: yellow
    yAxisLabel: Value
    yMin: 0
    showLegend: false
```

##### Summary

```tracker
searchType: frontmatter
searchTarget: weight-tracker
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Weight
summary:
    template: "Minimum: {{min()}}kg\nMaximum: {{max()}}kg\nMedian: {{median()}}kg\nAverage: {{average()}}kg"
```


#### Hydration
---

```tracker
searchType: frontmatter
searchTarget: water-counter
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Water
line:
    title: Performance Score
    lineColor: yellow
    yAxisLabel: Value
    yAxisUnit: Litres
    yMin: 0
    showLegend: false
```


#### Sleep
---

##### Sleep Hours:
---

```tracker
searchType: frontmatter
searchTarget: sleep-hrs
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Sleep
line:
    title: Sleep Hours
    lineColor: yellow
    yAxisLabel: Value
    yAxisUnit: Hours
    yMin: 0
    showLegend: false
```


##### Sleep Track:
---

```tracker
searchType: frontmatter
searchTarget: morning-wakeup-routine-wake-up-time, night-bed-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Woke up at, Slept at
line:
    title: Sleep Score
    lineColor: yellow, green
    yAxisLabel: Value
    yAxisUnit: Time
    yMax: 2400
    yMin: 0000
    showLegend: false
```


#### Workout
---

##### Morning
---

###### Warm up
---

```tracker
searchType: frontmatter
searchTarget: morning-physical-health-warmup-jumping-jacks-reps, morning-physical-health-warmup-high-knees-reps, morning-physical-health-warmup-arm-circles-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: jumping-jacks, high-knees, arm-circles
line:
    title: Exercise Reps
    lineColor: orange, yellow, green
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
	legendOrientation: vertical
```


###### Upper body
---

```tracker
searchType: frontmatter
searchTarget: morning-physical-health-upper-body-pushups-reps, morning-physical-health-upper-body-dips-reps, morning-physical-health-upper-body-plank-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: pushups, dips, plank
line:
    title: Exercise Reps
    lineColor: orange, yellow, green
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```

###### Lower body
---

```tracker
searchType: frontmatter
searchTarget: morning-physical-health-lower-body-squats-reps, morning-physical-health-lower-body-lunges-reps, morning-physical-health-lower-body-glute-bridges-reps, morning-physical-health-lower-body-calf-raises-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: squats, lunges, glute-bridges, calf-raises
line:
    title: Exercise Reps
    lineColor: orange, yellow, green, blue
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```

###### Core
---

```tracker
searchType: frontmatter
searchTarget: morning-physical-health-core-training-left-side-plank-length, morning-physical-health-core-training-right-side-plank-length, morning-physical-health-core-training-bicycle-crunches-reps, morning-physical-health-core-training-russian-twists-reps, morning-physical-health-core-training-leg-raises-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: left-side-plank, right-side-plank, bicycle-crunches, russian-twists, leg-raises
line:
    title: Exercise Reps
    lineColor: orange, yellow, green, blue, purple
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```


###### Cardiovascular Training 

```tracker
searchType: frontmatter
searchTarget: morning-physical-health-cardiovascualar-training-rope-skipping-count, morning-physical-health-cardiovascualar-training-burpees-reps, morning-physical-health-cardiovascualar-training-mountain-climbers-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: rope-skipping, burpees, mountain-climbers
line:
    title: Exercise Reps
    lineColor: orange, yellow, green
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```



##### Evening

###### Upper Body

```tracker
searchType: frontmatter
searchTarget: evening-physical-health-upper-body-weight-dumbell-push-press-reps, evening-physical-health-upper-body-weight-dumbell-renegade-rows-reps, evening-physical-health-upper-body-weight-single-arm-dumbell-floor-press-reps, evening-physical-health-upper-body-weight-dumbell-bent-over-rows-reps, evening-physical-health-upper-body-weight-dumbell-overhead-tricep-extension-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: push-press, renegade-rows, single-arm-floor-press, bent-over-rows, overhead-tricep-extension
line:
    title: Exercise Reps
    lineColor: orange, yellow, green, blue, purple
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```


######  Lower Body

```tracker
searchType: frontmatter
searchTarget: evening-physical-health-lower-body-weight-goblet-squats-reps, evening-physical-health-lower-body-weight-romanian-deadlift-reps, evening-physical-health-lower-body-weight-dumbell-lunges-reps, evening-physical-health-lower-body-weight-dumbell-reverse-lunges-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: goblet-squats, romanian-deadlift, dumbell-lunges, dumbell-reverse-lunges
line:
    title: Exercise Reps
    lineColor: orange, yellow, green, blue
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```

###### Core Training

```tracker
searchType: frontmatter
searchTarget: evening-physical-health-core-training-weight-dumbell-russian-twists-reps
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: dumbell-russian-twists
line:
    title: Exercise Reps
    lineColor: orange
    yAxisLabel: Value
    yAxisUnit: Repetition
    yMin: 0
    showLegend: true
    legendOrientation: vertical
```


### Finances
---


```tracker
searchType: frontmatter
searchTarget: expense, income, investment
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: expense, income, investment
bar:
    title: Finance
    yAxisLabel: Value
    yMin: 0
    barColor: yellow, green, orange 
    showLegend: True
    legendOrientation: vertical
```


### Time Trackers
---

#### College 

```tracker
searchType: frontmatter
searchTarget: college-clock-in-time, college-clock-out-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Clock-In, Clock-Out
line:
    title: "Working Hours"
    yAxisLabel: "Time (24h)"
    reverseYAxis: true
    lineColor: yellow, red
    showPoint: true
    showLegend: true
```

#### Self Study

##### Engineering

```tracker
searchType: frontmatter
searchTarget: engineering-self-study-clockin-time, engineering-self-study-clockout-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Clock-In, Clock-Out
line:
    title: "Study Hours"
    yAxisLabel: "Time (24h)"
    reverseYAxis: true
    lineColor: yellow, red
    showPoint: true
    showLegend: true
```


##### B.B.A.

```tracker
searchType: frontmatter
searchTarget: bba-self-study-clockin-time, bba-self-study-clockout-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Clock-In, Clock-Out
line:
    title: "Study Hours"
    yAxisLabel: "Time (24h)"
    reverseYAxis: true
    lineColor: yellow, red
    showPoint: true
    showLegend: true
```

##### Online-Education

```tracker
searchType: frontmatter
searchTarget: coursera-hours-spent, leetcode-hours-spent
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Coursera, Leetcode
line:
    title: "Study Hours"
    yAxisLabel: "Time (24h)"
    reverseYAxis: true
    lineColor: yellow, green
    showPoint: true
    showLegend: true
```




#### Shower
---

 ```tracker
searchType: frontmatter
searchTarget: morning-shower-duration, evening-shower-duration
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Morning, Evening
line:
    title: Efficiency Score
    lineColor: yellow, green
    yAxisLabel: Value
    yAxisUnit: Time
    yMin: 0000
    yMax: 0200
    showLegend: true
	legendOrientation: vertical
```

#### Screen time

```tracker
searchType: frontmatter
searchTarget: laptop-screen-time, android-screen-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Laptop, Android
line:
    title: Efficiency Score
    lineColor: yellow, green
    yAxisLabel: Value
    yAxisUnit: Time
    yMin: 0000
    yMax: 1800
    showLegend: true
	legendOrientation: vertical
```

#### Android 
---

 ```tracker
searchType: frontmatter
searchTarget: android-productivity-account-usage, android-education-account-usage, android-entertainment-account-usage, android-finance-and-government-account-usage
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Productivity, Education, Entertainment, Finance and Govt.
line:
    title: Efficiency Score
    lineColor: orange, red, green , yellow
    yAxisLabel: Value
    yAxisUnit: Time
    yMin: 0000
    yMax: 1500
    showLegend: true
	legendOrientation: vertical
```

#### Meals
---

```tracker
searchType: frontmatter
searchTarget: breakfast-time, lunch-time, snacks-time, dinner-time
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Breakfast, Lunch, Snacks, Dinner
line:
    title: Efficiency Score
    lineColor: orange, red, green , yellow
    yAxisLabel: Value
    yAxisUnit: Time
    yMin: 0000
    yMax: 2400
    showLegend: true
	legendOrientation: vertical
```

### Reviews
---

###### Breakfast
---

```dataview
TABLE breakfast-name AS Breakfast, breakfast-feedback as Feedback
FROM "Notes/Periodic-Notes/Daily-Notes"
WHERE date >= <%tp.date.now("YYYY-MM-DD", -6)%> AND date <= <%tp.date.now("YYYY-MM-DD")%>
SORT date ASC
LIMIT 7
```

###### Lunch
---

```dataview
TABLE Date, lunch-name AS Lunch, lunch-feedback as Feedback
FROM "Notes/Periodic-Notes/Daily-Notes"
WHERE date >= <%tp.date.now("YYYY-MM-DD", -6)%> AND date <= <%tp.date.now("YYYY-MM-DD")%>
SORT date ASC
LIMIT 7
```


###### Snacks
---

```dataview
TABLE Date, snacks-name AS Snacks, snacks-feedback as Feedback
FROM "Notes/Periodic-Notes/Daily-Notes"
WHERE date >= <%tp.date.now("YYYY-MM-DD", -6)%> AND date <= <%tp.date.now("YYYY-MM-DD")%>
SORT date ASC
LIMIT 7
```

###### DInner
---

```dataview
TABLE Date, dinner-name AS Dinner, dinner-feedback as Feedback
FROM "Notes/Periodic-Notes/Daily-Notes"
WHERE date >= <%tp.date.now("YYYY-MM-DD", -6)%> AND date <= <%tp.date.now("YYYY-MM-DD")%>
SORT date ASC
LIMIT 7
```



##### Total Daily Nutrition Values
---

###### Calories
---

```tracker
searchType: frontmatter
searchTarget: total-calorie-intake-amount
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Calories
line:
    title: Calorie Intake
    lineColor: orange
    yAxisLabel: Value
    yAxisUnit: kcal
    yMin: 0
    showLegend: true
	legendOrientation: vertical
```

###### Protein
---

```tracker
searchType: frontmatter
searchTarget: \total-protein-intake-amount
folder: Notes/Periodic-Notes/Daily-Notes/
startDate: <%tp.date.now("YYYY-MM-DD", -6)%>
endDate: <%tp.date.now("YYYY-MM-DD")%>
datasetName: Protein
line:
    title: Protein Intake
    lineColor: orange
    yAxisLabel: Value
    yAxisUnit: grams
    yMin: 0
    showLegend: true
	legendOrientation: vertical
```



## Reflections
---

### Past week suggestions
---

- [ ] Have you checked your past week suggestions for improving this week?
      ![[<%tp.date.now("YYYY-[W]ww", -9)%>###Improvements]]


### Improvements
---



## Weekly Tasks
---

- [ ] Inbox zero
- [ ] 