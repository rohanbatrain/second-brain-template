---
tags: templates/daily-note
reviewed-on:
date: <% tp.date.now("YYYY-MM-DD") %>
day-summary:
created: <% tp.date.now("YYYY-MM-DD HH:mm") %>
week: <% tp.date.now("YYYY-[W]w", 0, tp.file.title) %>
# Stastistics
## Personal
### Dailies
expense:
income:
investment:
mood: 
productivity:
health:
water-counter:
weight-tracker:
stress-levels:
sleep-hrs:
total-calorie-intake-amount:
total-protein-intake-amount:
morning-wakeup-routine-wake-up-time:
morning-mental-health-meditation-duration:
evening-mental-health-meditation-duration:
cried-counter:
morning-shower-duration:
evening-shower-duration:


### Screen time
laptop-screen-time:
android-screen-time:
iphone-screen-time:

# Morning routine
## Health
## running
morning-running-duration:
### Warmup
morning-physical-health-warmup-jumping-jacks-reps:
morning-physical-health-warmup-high-knees-reps:
morning-physical-health-warmup-arm-circles-reps:
### Upper body
morning-physical-health-upper-body-pushups-reps:
morning-physical-health-upper-body-dips-reps:
morning-physical-health-upper-body-plank-reps:
### Lower Body
morning-physical-health-lower-body-squats-reps:
morning-physical-health-lower-body-lunges-reps:
morning-physical-health-lower-body-glute-bridges-reps:
morning-physical-health-lower-body-calf-raises-reps:
### Core training
morning-physical-health-core-training-left-side-plank-length:
morning-physical-health-core-training-right-side-plank-length:
morning-physical-health-core-training-bicycle-crunches-reps:
morning-physical-health-core-training-russian-twists-reps:
morning-physical-health-core-training-leg-raises-reps:
### Cardio Vascular Training
morning-physical-health-cardiovascualar-training-rope-skipping-count:
morning-physical-health-cardiovascualar-training-burpees-reps:
morning-physical-health-cardiovascualar-training-mountain-climbers-reps:



# Self Study
## Self-study-time-engineering
### Semester-1
btech-advance-engineering-mathematics-hours-spent:
btech-environment-sustainibility-and-climate-change-hours-spent:
btech-linux-lab-hours-spent:
btech-living-conversations-hours-spent:
btech-problem-solving-hours-spent:
btech-programming-in-c-hours-spent:


## Self-study-time-bba
### Semester-1
bba-basic-mathematics-hours-spent:
bba-business-computing-hours-spent:
bba-business-economics-hours-spent:
bba-financial-accounting-hours-spent:
bba-managerial-written-communication-hours-spent:
bba-psychology-hours-spent:

## Hobbies
coursera-hours-spent:
### Library 
library-time-spent:
### College clubs 
runway-incubation-hours-spent:

## Projects



# Evening
## Health
### Upper body
evening-physical-health-upper-body-weight-dumbell-push-press-reps:
evening-physical-health-upper-body-weight-dumbell-renegade-rows-reps:
evening-physical-health-upper-body-weight-single-arm-dumbell-floor-press-reps:
evening-physical-health-upper-body-weight-dumbell-benot-over-rows-reps:
evening-physical-health-upper-body-weight-dumbell-overhead-tricep-extention-reps:
### Lower Body
evening-physical-health-lower-body-weight-goblet-squats-reps:
evening-physical-health-lower-body-weight-romanian-deadlift-reps:
evening-physical-health-lower-body-weight-dumbell-lunges-reps:
evening-physical-health-lower-body-weight-dumbell-reverse-lunges-reps:
### Core training
evening-physical-health-core-training-weight-dumbell-russian-twists-reps:

# Meals
## Meal Clock in time starts at when we decided to have a meal till when we return to the task with our hands on.
## Breakfast
breakfast-name:
breakfast-clock-in-time:
breakfast-clock-out-time:
breakfast-feedback:
breakfast-estimated-cost:
## Lunch
lunch-name:
lunch-clock-in-time:
lunch-clock-out-time:
lunch-feedback:
lunch-estimated-cost:
## Snacks
snacks-name:
snacks-clock-in-time:
snacks-clock-out-time:
snacks-feedback:
snacks-estimated-cost:
## Dinner
dinner-name:
dinner-clock-in-time:
dinner-clock-out-time:
dinner-feedback:
dinner-estimated-cost:

# Night
night-bed-time:


# Time-Trackers (Total Time Spent on a certain activity)
music-listening:
gaming:
youtube:
khan-academy:


## College-Time-Trackers, write where were you engaged in college today.
College-hour-0900: 
College-hour-1000:
College-hour-1100:
College-hour-1200:
College-hour-1300:
College-hour-1400:
College-hour-1500:
College-hour-1600:
College-hour-1700:

---

# <% tp.date.now("YYYY-MM-DD") %>’s Note

---
[[<%tp.date.now("YYYY-MM-DD", -1)%>|↶ Previous Day]] | [[<% tp.date.now("YYYY-[W]w") %>]] | [[<%tp.date.now("YYYY-MM-DD", +1)%>|Following Day ↷]] 

---

# Reminders

- [ ] Have you checked your yesterday suggestions for improving today?
	 ![[<%tp.date.now("YYYY-MM-DD", -1)%>#Improvements]]
- [ ] Carbohydrate drink has to be consumed asap after preparation 
- [ ] All the spaces in yaml values should be replaced with an underscore symbol. Except for sentences.

# Routine Tasks

## Morning

### Wake-up Routine


- [ ] Lemon water taken
- [ ] Supplements taken
    - [ ] Vitamins
    - [ ] Biotin



### Health

#### Preparation

- [ ] Meditation done
- [ ] Morning Workout
	- [ ] [[00-Morning-Workout-db]]


#### Post-Workout

- [ ] Protein shake taken
- [ ] Post-meal digestive supplement taken
- [ ] Full body coconut oil massage done
- [ ] Shower taken

#### Breakfast

- [ ] Breakfast taken
	- [ ] [[01-Meal-db]] 

### Skincare

- [ ] Cleanser applied
- [ ] Face icing applied
- [ ] Moisturiser applied
- [ ] Sun protection applied



---

## Afternoon

- [ ] Lunch taken
	- [ ] [[01-Meal-db]] 

---

## Evening

### Mental Health

- [ ] Meditation done
- [ ] Evening-Workout
	- [ ] [[05-Evening-Workout-db]]
 
### Post Workout

- [ ] Protein shake taken
- [ ] Post-meal supplement taken

---

## Night

- [ ] Shower done
- [ ] Dinner done
- [ ] Tongue cleaning done
- [ ] Brushing done
- [ ] Gargle done
- [ ] Dry fruits soaking done
- [ ] Review Databases.
     - [ ] [[00-Morning-Workout-db]]
     - [ ] [[01-Meal-db]]
     - [ ] [[02-Dailies-db]]
     - [ ] [[03-Screen-time]]
     - [ ] [[04-Study-db]]
     - [ ] [[05-Evening-Workout-db]]
     - [ ] [[06-Night-db]]

---

# Improvements
---

1. 


# Today's Log
---



# Today's Task
---


```tasks
has due date
not done
group by due
hide edit button
hide due date
```




# Journal
---


## Gratitude Journal
---


> 3 Things that i am grateful for in my life

1. <% tp.file.cursor(1) %> 
2. 
3.  


> 3 Things that i am grateful for myself

1. 
2. 
3. 




# Accounting
---

| S.No. | Credit/Debit | From/To | Notes | Bank-Account | Notes | 
| ----- | ------------ | ------- | ----- | ------------ | ----- |


# Statistical-Logs
---


## Khan Academy
---

| Course-Name | Started-Studying-On | Ended-Studying-On | Duration | 
| ----------- | ------------------- | ----------------- | -------- |

## Music
---

| Song-Name | Started-Listening-On | Ended-Listening-On | Duration | Platform | 
| --------- | -------------------- | ------------------ | -------- | -------- |







