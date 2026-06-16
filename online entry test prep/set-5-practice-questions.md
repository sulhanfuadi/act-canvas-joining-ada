Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 4 - Practice Set 5
 Self-assessment Quiz for Practice Set 5
Time limit: 90 minutes
Suggested split: A 35m, B 18m, C 15m, D 12m, E 10m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `6, 11, 18, 27, 38, ?`
Select one:
a. 49
b. 50
c. 51
d. 53

Question 2
Question text
Number pattern: `1, 8, 27, 64, ?, 216`
Select one:
a. 100
b. 120
c. 125
d. 150

Question 3
Question text
Number pattern: `2, 3, 5, 9, 17, ?`
Select one:
a. 25
b. 33
c. 35
d. 29

Question 4
Question text
A machine makes `240 units` in `6 hours`. At the exact same rate, how many units will it make in `8.5 hours`?
Select one:
a. 320 units
b. 340 units
c. 360 units
d. 380 units

Question 5
Question text
A `300 km` trip is completed in two parts: the first `120 km` is traveled at a constant speed of `60 km/h`, and the remaining distance is traveled at `90 km/h`. What is the total travel time?
Select one:
a. 3.5 hours
b. 4 hours
c. 4.5 hours
d. 5 hours

Question 6
Question text
Team A can finish a project in `10 days`, and Team B can finish the same project in `15 days`. If both teams work together, how many days will it take them to finish the project?
Select one:
a. 5 days
b. 6 days
c. 7.5 days
d. 8 days

Question 7
Question text
Consider these statements:
- All applicants submit a Curriculum Vitae (CV).
- Some CV submitters fail screening.
- Therefore, some applicants fail screening.

Is the conclusion logically valid?
Select one:
a. Yes, because applicants submit CVs, and some CV submitters fail screening.
b. No, because the group of CV submitters who fail screening does not necessarily overlap with the subset of CV submitters who are applicants.
c. Yes, because all applicants are guaranteed to pass screening.
d. No, because all applicants fail screening.

Question 8
Question text
Evaluate the logical validity of the following argument:
- If the application is slow, users complain.
- Users do not complain.
- Therefore, the application is not slow.

Select one:
a. Invalid, because users might be too polite to complain.
b. Valid, because by Modus Tollens (If P then Q; Not Q; Therefore Not P), the absence of user complaints guarantees the application is not slow.
c. Invalid, because it commits the fallacy of affirming the consequent.
d. Valid, because the application is never slow.

Question 9
Question text
A class has `40 students`. `65%` of the students pass the Logic exam, `55%` pass the Programming exam, and `20%` fail both. How many students pass both exams?
Select one:
a. 12 students
b. 16 students
c. 20 students
d. 24 students

Question 10
Question text
You have `12 identical-looking balls`, one of which is slightly heavier than the others. Which strategy describes how to find the heavier ball in exactly `3 weighings` using a simple balance scale?
Select one:
a. Weigh 6 against 6, then split the heavier group to 3 against 3, and then weigh 1 against 1.
b. Divide into three groups of 4 (A, B, C). Weigh A vs B. If balanced, the heavier ball is in C; if unbalanced, it is in the heavier group. Divide the candidate group of 4 into 2 vs 2 for the second weighing, and then 1 vs 1 for the third weighing.
c. Weigh the balls one-by-one against a single reference ball.
d. Weigh all 12 balls at once on the scale.

---

### Section B - Programming / Swift Basics

Question 11
Question text
What is the output of the following Swift code?
```swift
let data = [1, 3, 5, 7]
print(data.filter { $0 > 3 }.count)
```
Select one:
a. `4`
b. `3`
c. `2`
d. `1`

Question 12
Question text
Which Swift implementation correctly and efficiently calculates the sum of all even numbers in an array of integers?
Select one:
a.
```swift
func sumEven(_ values: [Int]) -> Int {
    return values.filter { $0 % 2 == 0 }.reduce(0, +)
}
```
b.
```swift
func sumEven(_ values: [Int]) -> Int {
    return values.map { $0 * 2 }.reduce(0, +)
}
```
c.
```swift
func sumEven(_ values: [Int]) -> Int {
    return values.filter { $0 % 2 != 0 }.reduce(0, +)
}
```
d.
```swift
func sumEven(_ values: [Int]) -> Int {
    return values.reduce(0, +)
}
```

Question 13
Question text
What is the primary risk associated with force-unwrapping optional variables (using the `!` operator) in Swift production code?
Select one:
a. It slows down the runtime performance.
b. It causes an immediate runtime crash if the optional variable is `nil` at the moment of access.
c. It increases the memory usage of the application.
d. It prevents the code from compiling.

---

### Section C - OOP & Swift Concepts

Question 14
Question text
Predict the output of the following Swift code:
```swift
struct S {
    var n: Int
}
var a = S(n: 2)
var b = a
b.n += 3
print(a.n, b.n)
```
Select one:
a. `2 2`
b. `5 5`
c. `2 5`
d. `5 2`

Question 15
Question text
Predict the output of the following Swift code:
```swift
class C {
    var n = 2
}
let x = C()
let y = x
y.n += 3
print(x.n, y.n)
```
Select one:
a. `2 2`
b. `5 5`
c. `2 5`
d. `5 2`

Question 16
Question text
Why is reference sharing (reference semantics) useful in mobile application architecture?
Select one:
a. It copies data to prevent memory leaks.
b. It makes variables thread-safe by default.
c. It enables sharing mutable state across different screens, ensuring they remain synchronized without manual synchronization code.
d. It compiles code into a faster binary.

---

### Section D - Design & UX

Question 17
Question text
Which three metrics or user behaviors are primary signs that a checkout flow has too much friction?
Select one:
a. Fast loading speed, low error count, and high download count.
b. High step-by-step drop-off rates, long completion times, and repeated input validation errors.
c. Large button sizes, high color contrast, and simple labels.
d. High app rating, long session length, and high social sharing.

Question 18
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Improve search quality"?
Select one:
a. "Make search results much better."
b. "Increase successful search result click-through from 42% to 58% by improving relevance ranking and typo tolerance."
c. "Search should load in less than 3 seconds."
d. "Add a search bar to all screens."

---

### Section E - Motivation & Soft Skills

Question 19
Question text
Which approach is most effective to stay calm and perform well when solving difficult logic questions under tight time limits?
Select one:
a. Rush through the questions as fast as possible to finish early.
b. Maintain a disciplined process: read the question carefully, sketch the problem structure visually, keep track of time, and skip to the next question if stuck, keeping emotional anxiety in check.
c. Focus only on the hardest question until it is solved, ignoring the rest.
d. Randomly select options if the question takes more than 10 seconds.

Question 20
Question text
You are asked to describe a learning mistake you corrected recently. Which response best demonstrates self-reflection and adaptability?
Select one:
a. "I had no mistakes; my learning process has always been perfect."
b. "I used to jump straight into writing code without planning, leading to messy architectures. I corrected this by introducing a 30-minute system design phase before coding, which has halved our debugging time."
c. "I did not study enough, so I failed. Next time, I will read more slides."
d. "I relied on my teammates' code, but they made mistakes that I had to fix."
