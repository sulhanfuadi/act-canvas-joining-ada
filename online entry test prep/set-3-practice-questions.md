Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 2 - Practice Set 3
 Self-assessment Quiz for Practice Set 3
Time limit: 90 minutes
Suggested split: A 20m, B 20m, C 15m, D 15m, E 20m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `5, 9, 15, 23, 33, ?`
Select one:
a. 43
b. 44
c. 45
d. 46

Question 2
Question text
A car travels `180 km` in `2.5 hours`. What is its average speed?
Select one:
a. 60 km/h
b. 70 km/h
c. 72 km/h
d. 75 km/h

Question 3
Question text
Consider these statements:
- All Product Managers (PMs) communicate clearly.
- Some communicators write documentation.
- Therefore, some PMs write documentation.

Is the conclusion logically valid?
Select one:
a. Yes, because PMs communicate clearly, and since some communicators write documentation, some PMs must write documentation.
b. No, because the group of communicators who write documentation does not necessarily overlap with the subset of communicators who are PMs.
c. Yes, because writing documentation is a PM's primary responsibility.
d. No, because no PMs write documentation.

Question 4
Question text
Number pattern: `2, 6, 12, 20, 30, ?`
Select one:
a. 40
b. 42
c. 44
d. 45

Question 5
Question text
You completed `45%` of the tasks in sprint week 1 and `30%` in week 2. What percentage of the tasks remains?
Select one:
a. 15%
b. 25%
c. 35%
d. 20%

Question 6
Question text
Evaluate the logical validity of the following argument:
- No prototypes are final products.
- Some prototypes are tested by users.
- Therefore, some tested items are not final products.

Select one:
a. Not valid, because prototypes are always final products.
b. Valid, because the tested prototypes are a subset of tested items, and since no prototypes are final products, those tested prototypes cannot be final products either.
c. Valid, because all tested items are prototypes.
d. Not valid, because some final products are prototypes.

---

### Section B - Programming / Swift Basics

Question 7
Question text
What is the output of the following Swift code?
```swift
let values = [3, 6, 9]
print(values.reduce(0, +))
```
Select one:
a. `[3, 6, 9]`
b. `18`
c. `9`
d. `0`

Question 8
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

Question 9
Question text
Which statement best explains optional binding using `if let` in Swift?
Select one:
a. It is used to force-unwrap optionals unconditionally.
b. It safely checks if an optional contains a value, and if so, unwraps it into a temporary non-optional constant that is available only within the local conditional scope.
c. It makes a variable globally accessible across all screens.
d. It compiles optionals into reference types.

Question 10
Question text
What is the output of the following Swift code?
```swift
let words = ["ada", "ios", "swift"]
let lengths = words.map { $0.count }
print(lengths.filter { $0 > 3 })
```
Select one:
a. `[3, 3, 5]`
b. `[5]`
c. `["swift"]`
d. `[]`

Question 11
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
```
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

Question 12
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
```
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

---

### Section C - OOP & Swift Concepts

Question 13
Question text
What is the difference between identity and equality for class instances in Swift?
Select one:
a. Identity is checked using `==`, and equality is checked using `===`.
b. Identity checks whether two references point to the exact same object in memory using `===`, while equality checks whether two instances contain equivalent values using `==`.
c. Identity applies to structs, and equality applies to classes.
d. There is no distinction; both check for memory addresses.

Question 14
Question text
Why do immutable models (declared with `let` in Swift structs) help reduce software bugs?
Select one:
a. They prevent memory leaks and cycles automatically.
b. They prevent unintended modifications from other parts of the codebase, ensuring that state changes are predictable and explicit.
c. They allow classes to inherit properties faster.
d. They force variables to be stored on the stack rather than the heap.

Question 15
Question text
When is the `mutating` keyword required before a method definition in a Swift struct?
Select one:
a. When the method returns an optional value.
b. When the method mutates the stored properties of the structure itself.
c. When the method is defined inside a class subclass.
d. When the method is static.

Question 16
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
c. `10 15`
d. `15 10`

Question 17
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
b. `true true`
c. `false true`
d. `true false`

Question 18
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
```
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

---

### Section D - Design & UX

Question 19
Question text
For a medication reminder app, which group of features represents the most appropriate MVP (V1) scope?
Select one:
a. Social sharing, medication price comparison, gamified levels, virtual doctor appointments, custom app icons.
b. Reminder schedule, medication list, adherence log, refill alerts, and caregiver sharing.
c. AR pill scanner, medical news feed, health insurance portal, community chat forum.
d. AI dosage recommendations, fitness tracker sync, dark mode, developer blog.

Question 20
Question text
Which three design techniques are most effective at reducing cognitive load in a checkout flow?
Select one:
a. Splitting the flow into separate, small steps (chunking), using plain language labels, and providing default smart selections.
b. Displaying all fields on a single page, using technical jargon, and forcing manual inputs.
c. Adding popups for product recommendations, using abstract icons, and changing button positions.
d. Requiring password verification at every step, using small text, and disabling autofill.

Question 21
Question text
Why is accessibility (a11y) considered a core requirement, rather than a "nice to have" feature?
Select one:
a. It increases the app's size in the store.
b. It expands the app's potential user base, promotes digital inclusion, and ensures compliance with legal regulations.
c. It makes it easier to compile the app for different devices.
d. It guarantees higher advertising revenue.

Question 22
Question text
A user must grant multiple device permissions (camera, location, notifications) on the first launch of your app. How would you redesign this?
Select one:
a. Request all permissions immediately in a sequence of system alerts on the first splash screen.
b. Request permissions contextually when the user interacts with a feature that requires them, accompanied by a clear explanation of the user benefits.
c. Hide the features that require permissions so you never have to ask.
d. Force the user to go to their device settings manually before they can open the app.

Question 23
Question text
An app experiences a high uninstall rate on the first day after download. Which three hypotheses should you test first?
Select one:
a. App has too few filters, lacks a tablet version, or lacks dark mode.
b. Weak onboarding value proposition, permission fatigue (asking too much too early), or slow app performance on first run.
c. Server cost is too high, code has too many files, or UI doesn't use custom fonts.
d. Marketing ads are too cheap, competitor launched a sale, or database query is not indexed.

Question 24
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Improve onboarding experience"?
Select one:
a. "Make onboarding better."
b. "Increase onboarding completion rate from 62% to 80% by reducing the number of screens from 6 to 3 and adding progress indicators."
c. "The onboarding should load faster and have nicer colors."
d. "Delete the onboarding flow entirely to make it simple."

---

### Section E - Motivation & Soft Skills

Question 25
Question text
Which response best describes a learning habit that helps you improve consistently?
Select one:
a. "I learn by reading books occasionally when I feel motivated."
b. "I establish a daily coding routine, set specific, measurable learning targets, and build small projects to apply concepts while actively seeking peer feedback."
c. "I listen to podcasts on double speed while doing other chores."
d. "I try to memorize code snippets so I don't have to think during tests."

Question 26
Question text
A team discussion results in constructive feedback that contradicts your proposed solution. How do you respond?
Select one:
a. Acknowledge the team's feedback, analyze their points objectively, and adapt my solution to incorporate their suggestions, recognizing that a better overall product is the goal.
b. Argue my case repeatedly until the team gets tired and yields to my idea.
c. Withdraw from the discussion and let others make all the decisions.
d. Implement my original solution in secret anyway.

Question 27
Question text
You are working under a tight deadline and need to balance speed and quality. How do you approach this tradeoff?
Select one:
a. Focus only on speed, skipping code reviews and testing to meet the date.
b. Prioritize the core features, maintain clean coding standards for that path, write tests for critical functions, and log any non-critical technical debt to resolve immediately after launch.
c. Extend the deadline unilaterally without telling the team.
d. Write messy code quickly and assume someone else will clean it up later.

Question 28
Question text
What does empathy look like in technical collaboration?
Select one:
a. Coding everything for your teammates so they don't have to deal with stress.
b. Active listening, seeking to understand your teammates' technical constraints, offering support when they struggle, and explaining technical concepts without condescension.
c. Criticizing peers openly when they write buggy code so they improve.
d. Letting teammates make mistakes so they learn the hard way.

Question 29
Question text
Which app domain motivation statement demonstrates the strongest drive and alignment with the Academy?
Select one:
a. "I want to build whatever app domain gets the most downloads."
b. "I am motivated to build apps in the educational accessibility domain, using simplified interfaces to help students with learning differences access study materials, which aligns with my passion for inclusive education."
c. "I want to build a clone of a messaging app to practice coding."
d. "I don't mind the domain as long as the code is easy to write."

Question 30
Question text
How do you plan to support peers from non-technical backgrounds in a cross-functional cohort?
Select one:
a. By taking over their work so they don't have to code.
b. By explaining programming concepts using simple, non-jargon analogies, inviting their input on design and domain logic, and creating a supportive space where no question is considered too basic.
c. By ignoring them and working only with technical peers.
d. By telling them to learn programming from online tutorials before talking to you.
