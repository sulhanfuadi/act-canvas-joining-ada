Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 2 - Practice Set 3 - ANSWER KEY
 Self-assessment Quiz for Practice Set 3 - Answer Key
Started on	Monday, 15 June 2026, 1:00 PM
State	Finished
Completed on	Monday, 15 June 2026, 2:30 PM
Time taken	1 hour 30 mins
Grade	30 out of 30 (100%)
Feedback	
Well done! This is the answer key and feedback for Practice Set 3.

---

### Section A - Logic & Reasoning

Question 1
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Number pattern: `5, 9, 15, 23, 33, ?`
Select one:
a. 43
b. 44
c. 45 Correct! The differences between consecutive terms are consecutive even numbers starting from +4: +4, +6, +8, +10. The next difference is +12, which yields 33 + 12 = 45.
d. 46
Feedback
The correct answer is: 45

Question 2
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
A car travels `180 km` in `2.5 hours`. What is its average speed?
Select one:
a. 60 km/h
b. 70 km/h
c. 72 km/h Correct! Average speed equals distance / time: 180 km / 2.5 hours = 72 km/h.
d. 75 km/h
Feedback
The correct answer is: 72 km/h

Question 3
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Consider these statements:
- All Product Managers (PMs) communicate clearly.
- Some communicators write documentation.
- Therefore, some PMs write documentation.

Is the conclusion logically valid?
Select one:
a. Yes, because PMs communicate clearly, and since some communicators write documentation, some PMs must write documentation.
b. No, because the group of communicators who write documentation does not necessarily overlap with the subset of communicators who are PMs. Correct! Just because some communicators write documentation, it doesn't mean PMs (who are also communicators) are part of that specific subset.
c. Yes, because writing documentation is a PM's primary responsibility.
d. No, because no PMs write documentation.
Feedback
The correct answer is: No, because the group of communicators who write documentation does not necessarily overlap with the subset of communicators who are PMs.

Question 4
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Number pattern: `2, 6, 12, 20, 30, ?`
Select one:
a. 40
b. 42 Correct! The pattern represents n * (n + 1) for consecutive integers: 1*2, 2*3, 3*4, 4*5, 5*6. The next term is 6 * 7 = 42. (Alternatively, the differences are +4, +6, +8, +10. The next difference is +12, giving 30 + 12 = 42).
c. 44
d. 45
Feedback
The correct answer is: 42

Question 5
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
You completed `45%` of the tasks in sprint week 1 and `30%` in week 2. What percentage of the tasks remains?
Select one:
a. 15%
b. 25% Correct! Total completed is 45% + 30% = 75%. The remaining tasks are 100% - 75% = 25%.
c. 35%
d. 20%
Feedback
The correct answer is: 25%

Question 6
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Evaluate the logical validity of the following argument:
- No prototypes are final products.
- Some prototypes are tested by users.
- Therefore, some tested items are not final products.

Select one:
a. Not valid, because prototypes are always final products.
b. Valid, because the tested prototypes are a subset of tested items, and since no prototypes are final products, those tested prototypes cannot be final products either. Correct! This is a valid syllogism (Ferio).
c. Valid, because all tested items are prototypes.
d. Not valid, because some final products are prototypes.
Feedback
The correct answer is: Valid, because the tested prototypes are a subset of tested items, and since no prototypes are final products, those tested prototypes cannot be final products either.

---

### Section B - Programming / Swift Basics

Question 7
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let values = [3, 6, 9]
print(values.reduce(0, +))
```
Select one:
a. `[3, 6, 9]`
b. `18` Correct! The `reduce` function sums all elements in the array: 0 + 3 + 6 + 9 = 18.
c. `9`
d. `0`
Feedback
The correct answer is: `18`

Question 8
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which Swift implementation correctly calculates the average of an array of Doubles, returning `nil` if the array is empty?
Select one:
a.
```swift
func average(_ items: [Double]) -> Double? {
    guard !items.isEmpty else { return nil }
    return items.reduce(0, +) / Double(items.count)
}
``` 
Correct! This avoids division by zero by checking if the array is empty using `guard`, and calculates the average using `reduce` and `count`.
b.
```swift
func average(_ items: [Double]) -> Double? {
    return items.reduce(0, +) / Double(items.count)
}
```
c.
```swift
func average(_ items: [Double]) -> Double? {
    if items.isEmpty { return 0 }
    return items.reduce(0, +)
}
```
d.
```swift
func average(_ items: [Double]) -> Double? {
    return items.max()
}
```
Feedback
The correct answer is:
```swift
func average(_ items: [Double]) -> Double? {
    guard !items.isEmpty else { return nil }
    return items.reduce(0, +) / Double(items.count)
}
```

Question 9
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which statement best explains optional binding using `if let` in Swift?
Select one:
a. It is used to force-unwrap optionals unconditionally.
b. It safely checks if an optional contains a value, and if so, unwraps it into a temporary non-optional constant that is available only within the local conditional scope. Correct! This is the fundamental purpose and scope limit of optional binding via `if let`.
c. It makes a variable globally accessible across all screens.
d. It compiles optionals into reference types.
Feedback
The correct answer is: It safely checks if an optional contains a value, and if so, unwraps it into a temporary non-optional constant that is available only within the local conditional scope.

Question 10
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let words = ["ada", "ios", "swift"]
let lengths = words.map { $0.count }
print(lengths.filter { $0 > 3 })
```
Select one:
a. `[3, 3, 5]`
b. `[5]` Correct! The map operation transforms words to their lengths: `["ada", "ios", "swift"]` -> `[3, 3, 5]`. The filter keeps only numbers strictly greater than 3, resulting in `[5]`.
c. `["swift"]`
d. `[]`
Feedback
The correct answer is: `[5]`

Question 11
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which implementation correctly completes the function `normalize(_:)` to trim whitespace and returns `"N/A"` if the text is `nil` or empty?
Select one:
a.
```swift
func normalize(_ text: String?) -> String {
    guard let text else { return "N/A" }
    let trimmed = text.trimmingCharacters(in: .whitespacesAndNewlines)
    return trimmed.isEmpty ? "N/A" : trimmed
}
``` Correct! This safely unwraps the optional, trims any whitespace or newlines, and handles empty-string cases by returning "N/A".
b.
```swift
func normalize(_ text: String?) -> String {
    return text!.trimmingCharacters(in: .whitespaces)
}
```
c.
```swift
func normalize(_ text: String?) -> String {
    return text ?? "N/A"
}
```
d.
```swift
func normalize(_ text: String?) -> String {
    let trimmed = text?.trimmingCharacters(in: .whitespacesAndNewlines)
    return trimmed!
}
```
Feedback
The correct answer is:
```swift
func normalize(_ text: String?) -> String {
    guard let text else { return "N/A" }
    let trimmed = text.trimmingCharacters(in: .whitespacesAndNewlines)
    return trimmed.isEmpty ? "N/A" : trimmed
}
```

Question 12
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which code snippet safely refactors the following unsafe optional force-unwrapping?
```swift
let raw: String? = "42"
let n = Int(raw!)!
print(n + 1)
```
Select one:
a.
```swift
let raw: String? = "42"
if let raw, let n = Int(raw) {
    print(n + 1)
}
``` Correct! This uses nested optional binding to safely unwrap `raw` and safely parse it into an integer, preventing runtime crashes.
b.
```swift
let raw: String? = "42"
print(Int(raw) ?? 0 + 1)
```
c.
```swift
let raw: String? = "42"
print(Int(raw!)! + 1)
```
d.
```swift
let raw: String? = "42"
if raw != nil { print(Int(raw)! + 1) }
```
Feedback
The correct answer is:
```swift
let raw: String? = "42"
if let raw, let n = Int(raw) {
    print(n + 1)
}
```

---

### Section C - OOP & Swift Concepts

Question 13
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the difference between identity and equality for class instances in Swift?
Select one:
a. Identity is checked using `==`, and equality is checked using `===`.
b. Identity checks whether two references point to the exact same object in memory using `===`, while equality checks whether two instances contain equivalent values using `==`. Correct! This is a core distinction for reference types in Swift.
c. Identity applies to structs, and equality applies to classes.
d. There is no distinction; both check for memory addresses.
Feedback
The correct answer is: Identity checks whether two references point to the exact same object in memory using `===`, while equality checks whether two instances contain equivalent values using `==`.

Question 14
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Why do immutable models (declared with `let` in Swift structs) help reduce software bugs?
Select one:
a. They prevent memory leaks and cycles automatically.
b. They prevent unintended modifications from other parts of the codebase, ensuring that state changes are predictable and explicit. Correct! Immutability ensures that once an object is created, its data cannot change unexpectedly under your feet.
c. They allow classes to inherit properties faster.
d. They force variables to be stored on the stack rather than the heap.
Feedback
The correct answer is: They prevent unintended modifications from other parts of the codebase, ensuring that state changes are predictable and explicit.

Question 15
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
When is the `mutating` keyword required before a method definition in a Swift struct?
Select one:
a. When the method returns an optional value.
b. When the method mutates the stored properties of the structure itself. Correct! Since structs are value types, Swift requires methods that modify internal properties to be explicitly marked as `mutating`.
c. When the method is defined inside a class subclass.
d. When the method is static.
Feedback
The correct answer is: When the method mutates the stored properties of the structure itself.

Question 16
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Predict the output of the following code snippet:
```swift
struct Timer {
    var seconds: Int
    mutating func add(_ s: Int) { seconds += s }
}
var t1 = Timer(seconds: 10)
var t2 = t1
t2.add(5)
print(t1.seconds, t2.seconds)
```
Select one:
a. `10 10`
b. `15 15`
c. `10 15` Correct! `Timer` is a struct (value type), meaning `t2` is a distinct copy. Mutating `t2` has no impact on `t1`.
d. `15 10`
Feedback
The correct answer is: `10 15`

Question 17
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Predict the output of the following Swift code:
```swift
class Session {
    var active = false
}
let s1 = Session()
let s2 = s1
s2.active = true
print(s1.active, s2.active)
```
Select one:
a. `false false`
b. `true true` Correct! `Session` is a class (reference type), meaning `s1` and `s2` reference the same underlying instance. Changing `s2.active` updates the shared state.
c. `false true`
d. `true false`
Feedback
The correct answer is: `true true`

Question 18
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which snippet correctly defines a protocol `Trackable` with a method `track(event:)` and implements it in a struct?
Select one:
a.
```swift
protocol Trackable {
    func track(event: String)
}
struct Analytics: Trackable {
    func track(event: String) {
        print("Track: \(event)")
    }
}
``` Correct! This correctly defines a protocol signature and conforms to it within a struct.
b.
```swift
class Trackable {
    func track(event: String) {}
}
struct Analytics: Trackable {}
```
c.
```swift
protocol Trackable {
    var event: String { get }
}
```
d.
```swift
struct Trackable {
    func track(event: String) {}
}
```
Feedback
The correct answer is:
```swift
protocol Trackable {
    func track(event: String)
}
struct Analytics: Trackable {
    func track(event: String) {
        print("Track: \(event)")
    }
}
```

---

### Section D - Design & UX

Question 19
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
For a medication reminder app, which group of features represents the most appropriate MVP (V1) scope?
Select one:
a. Social sharing, medication price comparison, gamified levels, virtual doctor appointments, custom app icons.
b. Reminder schedule, medication list, adherence log, refill alerts, and caregiver sharing. Correct! These represent the essential utility features needed to solve the core user problem of tracking medication compliance.
c. AR pill scanner, medical news feed, health insurance portal, community chat forum.
d. AI dosage recommendations, fitness tracker sync, dark mode, developer blog.
Feedback
The correct answer is: Reminder schedule, medication list, adherence log, refill alerts, and caregiver sharing.

Question 20
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which three design techniques are most effective at reducing cognitive load in a checkout flow?
Select one:
a. Splitting the flow into separate, small steps (chunking), using plain language labels, and providing default smart selections. Correct! These techniques minimize decision fatigue and make the form inputs straightforward.
b. Displaying all fields on a single page, using technical jargon, and forcing manual inputs.
c. Adding popups for product recommendations, using abstract icons, and changing button positions.
d. Requiring password verification at every step, using small text, and disabling autofill.
Feedback
The correct answer is: Splitting the flow into separate, small steps (chunking), using plain language labels, and providing default smart selections.

Question 21
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Why is accessibility (a11y) considered a core requirement, rather than a "nice to have" feature?
Select one:
a. It increases the app's size in the store.
b. It expands the app's potential user base, promotes digital inclusion, and ensures compliance with legal regulations. Correct! Good accessibility ensures that everyone, including those with temporary or permanent disabilities, can use your product.
c. It makes it easier to compile the app for different devices.
d. It guarantees higher advertising revenue.
Feedback
The correct answer is: It expands the app's potential user base, promotes digital inclusion, and ensures compliance with legal regulations.

Question 22
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
A user must grant multiple device permissions (camera, location, notifications) on the first launch of your app. How would you redesign this?
Select one:
a. Request all permissions immediately in a sequence of system alerts on the first splash screen.
b. Request permissions contextually when the user interacts with a feature that requires them, accompanied by a clear explanation of the user benefits. Correct! Contextual permission requests reduce user friction and increase the likelihood of approval.
c. Hide the features that require permissions so you never have to ask.
d. Force the user to go to their device settings manually before they can open the app.
Feedback
The correct answer is: Request permissions contextually when the user interacts with a feature that requires them, accompanied by a clear explanation of the user benefits.

Question 23
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
An app experiences a high uninstall rate on the first day after download. Which three hypotheses should you test first?
Select one:
a. App has too few filters, lacks a tablet version, or lacks dark mode.
b. Weak onboarding value proposition, permission fatigue (asking too much too early), or slow app performance on first run. Correct! These issues represent the primary causes of negative first impressions leading to immediate abandonment.
c. Server cost is too high, code has too many files, or UI doesn't use custom fonts.
d. Marketing ads are too cheap, competitor launched a sale, or database query is not indexed.
Feedback
The correct answer is: Weak onboarding value proposition, permission fatigue (asking too much too early), or slow app performance on first run.

Question 24
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Improve onboarding experience"?
Select one:
a. "Make onboarding better."
b. "Increase onboarding completion rate from 62% to 80% by reducing the number of screens from 6 to 3 and adding progress indicators." Correct! This is a measurable and specific target with clear indicators of what changes will be implemented.
c. "The onboarding should load faster and have nicer colors."
d. "Delete the onboarding flow entirely to make it simple."
Feedback
The correct answer is: "Increase onboarding completion rate from 62% to 80% by reducing the number of screens from 6 to 3 and adding progress indicators."

---

### Section E - Motivation & Soft Skills

Question 25
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which response best describes a learning habit that helps you improve consistently?
Select one:
a. "I learn by reading books occasionally when I feel motivated."
b. "I establish a daily coding routine, set specific, measurable learning targets, and build small projects to apply concepts while actively seeking peer feedback." Correct! This combines discipline, goal-setting, practical application, and feedback loops.
c. "I listen to podcasts on double speed while doing other chores."
d. "I try to memorize code snippets so I don't have to think during tests."
Feedback
The correct answer is: "I establish a daily coding routine, set specific, measurable learning targets, and build small projects to apply concepts while actively seeking peer feedback."

Question 26
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
A team discussion results in constructive feedback that contradicts your proposed solution. How do you respond?
Select one:
a. Acknowledge the team's feedback, analyze their points objectively, and adapt my solution to incorporate their suggestions, recognizing that a better overall product is the goal. Correct! This shows humility, active listening, and willingness to adapt for team success.
b. Argue my case repeatedly until the team gets tired and yields to my idea.
c. Withdraw from the discussion and let others make all the decisions.
d. Implement my original solution in secret anyway.
Feedback
The correct answer is: Acknowledge the team's feedback, analyze their points objectively, and adapt my solution to incorporate their suggestions, recognizing that a better overall product is the goal.

Question 27
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
You are working under a tight deadline and need to balance speed and quality. How do you approach this tradeoff?
Select one:
a. Focus only on speed, skipping code reviews and testing to meet the date.
b. Prioritize the core features, maintain clean coding standards for that path, write tests for critical functions, and log any non-critical technical debt to resolve immediately after launch. Correct! This ensures the application remains robust and maintainable while meeting constraints.
c. Extend the deadline unilaterally without telling the team.
d. Write messy code quickly and assume someone else will clean it up later.
Feedback
The correct answer is: Prioritize the core features, maintain clean coding standards for that path, write tests for critical functions, and log any non-critical technical debt to resolve immediately after launch.

Question 28
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What does empathy look like in technical collaboration?
Select one:
a. Coding everything for your teammates so they don't have to deal with stress.
b. Active listening, seeking to understand your teammates' technical constraints, offering support when they struggle, and explaining technical concepts without condescension. Correct! Empathy means respecting others' experiences, listening, and offering support constructively.
c. Criticizing peers openly when they write buggy code so they improve.
d. Letting teammates make mistakes so they learn the hard way.
Feedback
The correct answer is: Active listening, seeking to understand your teammates' technical constraints, offering support when they struggle, and explaining technical concepts without condescension.

Question 29
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which app domain motivation statement demonstrates the strongest drive and alignment with the Academy?
Select one:
a. "I want to build whatever app domain gets the most downloads."
b. "I am motivated to build apps in the educational accessibility domain, using simplified interfaces to help students with learning differences access study materials, which aligns with my passion for inclusive education." Correct! This is focused on a clear user need, a specific domain, and reflects a purposeful, user-centric drive.
c. "I want to build a clone of a messaging app to practice coding."
d. "I don't mind the domain as long as the code is easy to write."
Feedback
The correct answer is: "I am motivated to build apps in the educational accessibility domain, using simplified interfaces to help students with learning differences access study materials, which aligns with my passion for inclusive education."

Question 30
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
How do you plan to support peers from non-technical backgrounds in a cross-functional cohort?
Select one:
a. By taking over their work so they don't have to code.
b. By explaining programming concepts using simple, non-jargon analogies, inviting their input on design and domain logic, and creating a supportive space where no question is considered too basic. Correct! This builds a collaborative learning culture and respects non-technical perspectives.
c. By ignoring them and working only with technical peers.
d. By telling them to learn programming from online tutorials before talking to you.
Feedback
The correct answer is: By explaining programming concepts using simple, non-jargon analogies, inviting their input on design and domain logic, and creating a supportive space where no question is considered too basic.
