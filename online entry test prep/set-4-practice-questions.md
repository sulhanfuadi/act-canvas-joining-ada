Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 3 - Practice Set 4
 Self-assessment Quiz for Practice Set 4
Time limit: 90 minutes
Suggested split: A 20m, B 20m, C 15m, D 15m, E 20m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `1, 2, 6, 24, 120, ?`
Select one:
a. 240
b. 600
c. 720
d. 840

Question 2
Question text
Two workers can complete a task in `6 hours` and `9 hours` respectively. If both work together at their constant rates, how long will it take to finish one task?
Select one:
a. 3.6 hours
b. 3.8 hours
c. 4 hours
d. 3 hours

Question 3
Question text
Consider these statements:
- All accessible apps are user-centered.
- Some user-centered products fail in the market.
- Therefore, some accessible apps fail in the market.

Is the conclusion logically valid?
Select one:
a. Yes, because accessible apps are user-centered, and since some user-centered products fail, some accessible apps must fail.
b. No, because the group of user-centered products that fail does not necessarily overlap with the subset that are accessible apps.
c. Yes, because accessible apps are difficult to monetize, making them fail.
d. No, because no accessible apps ever fail in the market.

Question 4
Question text
Number pattern: `7, 10, 16, 25, 37, ?`
Select one:
a. 50
b. 51
c. 52
d. 53

Question 5
Question text
A runner increases their average pace from `8 km/h` to `10 km/h` on a `20 km` route. How much time is saved?
Select one:
a. 15 minutes
b. 30 minutes
c. 45 minutes
d. 20 minutes

Question 6
Question text
Evaluate the logical validity of the following argument:
- If a feature is confusing, users drop off.
- Users did not drop off.
- Therefore, the feature is not confusing.

Select one:
a. Not valid, because user behavior is unpredictable.
b. Valid, because by Modus Tollens (If P then Q; Not Q; Therefore Not P), the absence of the effect (drop off) guarantees the absence of the sufficient cause (confusing feature).
c. Not valid, because it is denying the antecedent.
d. Valid, because users never drop off from confusing features.

---

### Section B - Programming / Swift Basics

Question 7
Question text
What is the output of the following Swift code?
```swift
let n = [1, 2, 3, 4]
let out = n.filter { $0 % 2 == 0 }.reduce(0, +)
print(out)
```
Select one:
a. `10`
b. `6`
c. `4`
d. `2`

Question 8
Question text
Which Swift implementation correctly filters an array of integers to return unique values while preserving their first-seen order?
Select one:
a.
```swift
func uniquePreservingOrder(_ values: [Int]) -> [Int] {
    var seen = Set<Int>()
    var result: [Int] = []
    for v in values {
        if !seen.contains(v) {
            seen.insert(v)
            result.append(v)
        }
    }
    return result
}
```
b.
```swift
func uniquePreservingOrder(_ values: [Int]) -> [Int] {
    return Array(Set(values))
}
```
c.
```swift
func uniquePreservingOrder(_ values: [Int]) -> [Int] {
    return values.sorted()
}
```
d.
```swift
func uniquePreservingOrder(_ values: [Int]) -> [Int] {
    return values.filter { $0 != 0 }
}
```

Question 9
Question text
What is the primary difference in architecture/nesting between `guard let` and `if let` in Swift?
Select one:
a. `guard let` is used for classes, and `if let` is used for structs.
b. `guard let` is designed to handle exit paths early and keeps the happy path flat, whereas `if let` wraps the success path inside a nested conditional scope.
c. `if let` runs faster than `guard let` under heavy CPU load.
d. `guard let` can unwrap multiple values, but `if let` can only unwrap one.

Question 10
Question text
What is the output of the following Swift code?
```swift
let texts = ["10", "x", "20", "30a", "40"]
let total = texts.compactMap(Int.init).reduce(0, +)
print(total)
```
Select one:
a. `100`
b. `70`
c. `10`
d. `0`

Question 11
Question text
Which Swift implementation correctly returns at most the two largest integers from an array in descending order?
Select one:
a.
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return Array(values.sorted(by: >).prefix(2))
}
```
b.
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return values.filter { $0 > 2 }
}
```
c.
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return Array(values.sorted().prefix(2))
}
```
d.
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return [values.max() ?? 0]
}
```

Question 12
Question text
Which snippet safely refactors the following code, avoiding force-unwrapping and avoiding duplicate parsing of the optional string into an integer?
```swift
let input: String? = "15"
if Int(input!) != nil {
    print(Int(input!)! * 2)
}
```
Select one:
a.
```swift
let input: String? = "15"
if let input, let n = Int(input) {
    print(n * 2)
}
```
b.
```swift
let input: String? = "15"
print(Int(input!)! * 2)
```
c.
```swift
let input: String? = "15"
if input != nil { print(Int(input!)! * 2) }
```
d.
```swift
let input: String? = "15"
print((Int(input ?? "0") ?? 0) * 2)
```

---

### Section C - OOP & Swift Concepts

Question 13
Question text
Why are strong reference cycles (memory leaks) a risk when using classes but not when using plain structures in Swift?
Select one:
a. Structs have complex garbage collection routines built-in.
b. Classes are reference types and store instances in heap memory with multiple shared references (which can form circular reference dependencies), whereas structs are value types copied by value and do not support shared references.
c. Classes are always compiled on the stack, where cycles occur.
d. Structs are compiled in C, which automatically handles reference counting.

Question 14
Question text
When is it preferable to define and adopt a protocol rather than creating a subclass hierarchy in Swift?
Select one:
a. When you want to allow instances to have shared mutable storage.
b. When you need to define a shared behavioral contract across multiple unrelated types without forcing them into a rigid, tightly coupled parent-child inheritance structure.
c. When all conforming types are guaranteed to be classes.
d. When subclassing is not supported by the iOS operating system.

Question 15
Question text
What is a performance or architectural reason to mark a Swift class or member as `final`?
Select one:
a. It allows other classes to subclass it dynamically.
b. It prevents classes from conforming to protocols.
c. It prevents subclass overriding, which helps maintain the architecture boundaries, and allows the compiler to optimize calls by using direct dispatch instead of dynamic table dispatch.
d. It automatically shifts reference storage from heap to stack.

Question 16
Question text
Predict the output of the following Swift code:
```swift
struct Config {
    var retries: Int
}
var c1 = Config(retries: 2)
func update(_ cfg: Config) -> Config {
    var copy = cfg
    copy.retries += 1
    return copy
}
let c2 = update(c1)
print(c1.retries, c2.retries)
```
Select one:
a. `2 2`
b. `3 3`
c. `2 3`
d. `3 2`

Question 17
Question text
Predict the output of the following Swift code:
```swift
class Counter {
    var value = 0
}
func increment(_ c: Counter) {
    c.value += 1
}
let c = Counter()
increment(c)
print(c.value)
```
Select one:
a. `0`
b. `1`
c. The code will crash at runtime.
d. The code will fail to compile.

Question 18
Question text
Which snippet correctly defines a protocol `Cacheable` with associated key/value behaviors?
Select one:
a.
```swift
protocol Cacheable {
    associatedtype Key: Hashable
    associatedtype Value
    mutating func set(_ value: Value, for key: Key)
    func get(_ key: Key) -> Value?
}
```
b.
```swift
class Cacheable {
    var cache: [String: Any] = [:]
}
```
c.
```swift
protocol Cacheable {
    var data: Any { get set }
}
```
d.
```swift
struct Cacheable {
    func get(_ key: String) -> Any? { return nil }
}
```

---

### Section D - Design & UX

Question 19
Question text
Which group of features represents the most appropriate MVP (V1) scope for a transit application focused on accessibility?
Select one:
a. Premium subscription tiers, social media travel sharing, dark mode, weather forecasting, and custom route themes.
b. Accessible route search, step-free station filtering, real-time voice guidance, disruption alerts, and saved frequent trips.
c. 3D station models, community chat forums, in-app mini-games, and integration with fitness bands.
d. AI shuttle passenger forecasting, driver tip system, and local sightseeing recommendations.

Question 20
Question text
What are three primary user experience (UX) risks associated with a 9-step booking or checkout flow?
Select one:
a. Fast loading speed, low error count, and high user focus.
b. High user drop-off rate, accumulation of input validation errors, and cognitive overload leading to abandonment.
c. Increased device storage usage, compiler warnings, and battery draining.
d. Lack of support for custom typography, missing dark mode, and lack of horizontal scrolling.

Question 21
Question text
How does the design pattern of "progressive disclosure" improve app completion rates?
Select one:
a. By showing all possible configurations and options on the first page to save taps.
b. By presenting only necessary information initially, revealing advanced options or fields contextually as needed to avoid overwhelming the user.
c. By forcing the user to progress through pages quickly using timers.
d. By using animations that lock the screen until the user reads the text.

Question 22
Question text
If you have 2 weeks left before the app launch and discover critical usability issues in testing, which triage framework should you adopt?
Select one:
a. Fix everything in alphabetical order.
b. Prioritize issues by Severity x Frequency x User Impact; resolve critical blocking flows first and defer visual polish or minor issues to V2.
c. Ignore all issues and launch on time, resolving problems only when bad reviews appear.
d. Re-design the entire user interface from scratch.

Question 23
Question text
You observe that user retention drops significantly after day 3 of downloading your app. Which three data slices should you inspect first?
Select one:
a. App store rating, developer line count, and database size.
b. Retention cohorts segmented by acquisition channel, device/performance specifications, and user path tracking within the first session.
c. Server logs, push notification volume, and code reviews.
d. Marketing budgets, competitor updates, and daily active users.

Question 24
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Make accessibility much better"?
Select one:
a. "Improve accessibility options."
b. "Raise accessibility audit score from 68 to 90 by adding screen-reader labels, contrast-compliant colors, and dynamic type support across the core booking flow."
c. "The app must be easy to use for disabled users."
d. "Add a toggle for accessibility on the home screen."

---

### Section E - Motivation & Soft Skills

Question 25
Question text
You are asked to describe a failure that improved your way of working. Which response shows the highest level of accountability and professional growth?
Select one:
a. "A project failed because my team members did not work hard enough. Next time, I will make sure they do their jobs."
b. "We missed a project deadline because of poor task estimations. I took responsibility, analyzed our tracking gaps, and introduced a scrum board with daily standups in our next project, which helped us deliver all subsequent features on time."
c. "The project was a failure, but since it was only a prototype, I didn't care much."
d. "I have never failed; all my projects have been perfect successes."

Question 26
Question text
How do you contribute to a project when your role is not formally defined?
Select one:
a. I wait until the team leader gives me a formal list of tasks.
b. I observe the team's needs, identify gaps (e.g., missing tests or undocumented requirements), propose where I can add value, and collaborate with others to fill those gaps proactively.
c. I focus only on coding my own parts and don't get involved in other work.
d. I complain about the lack of project structure to the mentors.

Question 27
Question text
Which response describes the most appropriate tradeoff made under deadline pressure?
Select one:
a. "I disabled user input validation to complete the registration screen faster."
b. "We had to deliver a prototype. Under pressure, we scoped out the custom profile editor and focused on securing the primary booking flow, logging the profile work for V2 while keeping our code base tested and clean."
c. "I wrote messy code to meet the date, hoping to fix it later, though we never did."
d. "I extended our deadline by two weeks without asking the product owner."

Question 28
Question text
How do you ensure that quieter or less confident teammates are heard during discussions?
Select one:
a. By speaking louder to ensure the team stays on topic.
b. By actively pausing the discussion, asking quieter teammates for their thoughts on specific areas, and creating a supportive, non-judgmental environment.
c. By assuming they agree with the majority if they remain silent.
d. By assigning them tasks without asking for their input first.

Question 29
Question text
What impact do you want your app development work to create in 3 years?
Select one:
a. "I want to have built several apps that generate advertising revenue for myself."
b. "I want to design and deploy apps that improve daily life for underserved communities, such as facilitating accessible transport or digital literacy for seniors, showing measurable improvements in their independence."
c. "I want to be recognized as the fastest coder in my company."
d. "I hope to write code that does not require maintenance."

Question 30
Question text
How do you recover after receiving tough criticism on your work?
Select one:
a. I ignore it and keep doing my work the same way.
b. I process it non-defensively, separate my ego from my work, seek clarification on specific points, and create a concrete checklist of actions to improve my performance.
c. I express my frustration to the team and refuse to work.
d. I ask the team to assign me to a different project.
