Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 6 - Practice Set 7
 Self-assessment Quiz for Practice Set 7
Time limit: 90 minutes
Suggested split: A 12m, B 12m, C 12m, D 24m, E 30m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `3, 5, 9, 15, 23, ?`
Select one:
a. 31
b. 32
c. 33
d. 35

Question 2
Question text
A bicyclist travels at a constant speed of `30 km/h` for `2 hours`, and then at `45 km/h` for `1 hour`. What is the total distance traveled?
Select one:
a. 75 km
b. 90 km
c. 105 km
d. 120 km

Question 3
Question text
Consider these statements:
- All empathetic teammates listen actively.
- Some active listeners are facilitators.
- Therefore, some empathetic teammates are facilitators.

Is the conclusion logically valid?
Select one:
a. Yes, because empathetic teammates listen actively, and some active listeners are facilitators.
b. No, because the group of active listeners who are facilitators does not necessarily overlap with the subset who are empathetic teammates.
c. Yes, because all facilitators are empathetic teammates.
d. No, because empathetic teammates can never be facilitators.

---

### Section B - Programming / Swift Basics

Question 4
Question text
What is the output of the following Swift code?
```swift
let arr = [2, 3, 4]
print(arr.reduce(1, *))
```
Select one:
a. `9`
b. `24`
c. `1`
d. `0`

Question 5
Question text
Which Swift implementation correctly returns `true` if and only if all integers in an array are strictly positive?
Select one:
a.
```swift
func allPositive(_ values: [Int]) -> Bool {
    return values.allSatisfy { $0 > 0 }
}
```
b.
```swift
func allPositive(_ values: [Int]) -> Bool {
    return values.filter { $0 > 0 }.isEmpty
}
```
c.
```swift
func allPositive(_ values: [Int]) -> Bool {
    return values.contains { $0 > 0 }
}
```
d.
```swift
func allPositive(_ values: [Int]) -> Bool {
    return values.allSatisfy { $0 >= 0 }
}
```

Question 6
Question text
Why does proper optional handling (e.g., using `if let` or `guard let` instead of `!`) matter in production iOS applications?
Select one:
a. It reduces the size of the compiled app bundle.
b. It prevents runtime crashes by safely handling missing data and making developers explicitly resolve the `nil` state.
c. It ensures that the app compiles faster.
d. It automatically formats the codebase according to strict styling guides.

---

### Section C - OOP & Swift Concepts

Question 7
Question text
What is one practical difference between a `struct` and a `class` in a team collaboration context?
Select one:
a. Structs support class inheritance, making code sharing easier.
b. Struct copies reduce accidental shared edits (since value types copy data on assignment), whereas classes share a single mutable reference across all instances.
c. Classes automatically make code thread-safe without locks.
d. Structs are always stored on the heap, preventing memory cycle issues.

Question 8
Question text
Predict the output of the following Swift code:
```swift
class Team {
    var size = 3
}
let a = Team()
let b = a
b.size = 5
print(a.size)
```
Select one:
a. `3`
b. `5`
c. The code will fail to compile.
d. The code will crash at runtime.

Question 9
Question text
Why are protocols highly useful for enabling collaboration between different modules or teams?
Select one:
a. They automatically resolve merge conflicts in Git.
b. They define clear behavioral contracts (interfaces) that decouple the implementation details, reducing tight coupling and allowing teams to work in parallel.
c. They force all types to behave as reference types.
d. They speed up compilation by converting code to machine assembly.

---

### Section D - Design & UX (FGD-style)

Question 10
Question text
Your team has 30 minutes to design an app feature for campus shuttle accessibility. Which MVP user journey best balances speed, empathy, and feasibility?
Select one:
a. Build a 3D shuttle tour first, then add virtual reality support, and leave route details to V2.
b. Focus on a clear persona (e.g., wheelchair student commuting daily) and design a 5-step flow: Open app -> Select route -> Check accessible stops -> Track shuttle location -> Receive arrival guidance.
c. Add an AI chat bot that answers questions about shuttle schedules.
d. Design a social media feature where students rate the driver's driving style.

Question 11
Question text
A teammate proposes a highly complex AI feature for V1 of your app. You believe it is too risky for the deadline. How should you respond collaboratively?
Select one:
a. Tell them their idea is unrealistic and will cause the project to fail.
b. Acknowledge the value of the idea, state the V1 time constraint, suggest a phased approach (AI in V2), and invite team feedback to align on V1 priorities.
c. Complain to the mentor so they resolve the issue.
d. Remain silent and let the team build the risky feature.

Question 12
Question text
Given limited engineering capacity, which prioritization hierarchy of these shuttle features best serves V1 user reliability?
Select one:
a. Voice navigation, Saved routes, Live bus location, Delay notification.
b. Delay notification, Live bus location, Saved routes, and Voice navigation.
c. Saved routes, Voice navigation, Live bus location, Delay notification.
d. Voice navigation, Live bus location, Saved routes, Delay notification.

---

### Section E - Motivation & Soft Skills (Interview-style)

Question 13
Question text
You are asked to describe a time you were wrong in a team discussion. Which response best demonstrates accountability and active adaptation?
Select one:
a. "I was never wrong; the team eventually realized my original plan was correct."
b. "I advocated for a complex navigation flow. After my teammate showed user testing data where users struggled, I acknowledged my error, embraced their data-driven layout, and helped implement it, which resolved the user confusion."
c. "I realized I was wrong but did not say anything so I wouldn't lose authority in the team."
d. "I was wrong because my teammates did not explain the requirements properly."

Question 14
Question text
How do you handle a teammate who dominates every project conversation?
Select one:
a. Interrupt them and shout to ensure my ideas are heard.
b. Listen actively, acknowledge their inputs, and then ask structured questions to invite other quieter teammates to contribute, ensuring balanced team participation.
c. Stop attending meetings and work independently.
d. Complain about their behavior to the instructors.

Question 15
Question text
Which response describes the best way to turn constructive criticism into positive action?
Select one:
a. Write down the critic's name and avoid working with them in the future.
b. Separating my ego from the work, listening non-defensively, asking for clarification on the underlying issues, and creating a concrete action checklist to improve my work.
c. Expressing my disagreement openly and continuing with my original design.
d. Asking a different teammate to review my work to get a second opinion.

Question 16
Question text
What does "empathy over ego" mean in product collaboration?
Select one:
a. Prioritizing my personal designs because they are visually appealing.
b. Focusing on the user's needs and the team's collective outcome, and being willing to let go of personal ideas if testing or discussions show a different path is better.
c. Always agreeing with the most senior member of the team to avoid conflict.
d. Letting the user decide everything without applying engineering design constraints.

Question 17
Question text
Why should the Apple Developer Academy choose you for a cross-functional cohort?
Select one:
a. "Because I already know how to write iOS apps and can complete projects faster than anyone else."
b. "Because I bring a balanced technical skill set, a growth mindset ready to learn from others, and a strong collaborative drive to build impactful, user-centered apps with diverse peers."
c. "Because I need to learn how to code and there are no other free courses."
d. "Because I have always wanted to work at Apple."

Question 18
Question text
Which statement about creating app impact for underserved users demonstrates the deepest empathy?
Select one:
a. "I want to build an app that makes technology fun for them."
b. "I want to build apps that reduce barriers to essential services (e.g., simplifying transit schedules or medical bookings), focusing on accessibility to increase their independence and quality of life."
c. "I want to build a clone of a delivery app with a discount coupon system."
d. "I don't know who underserved users are, but I will design for them if paid."
