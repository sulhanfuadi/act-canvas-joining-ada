Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 3 - Practice Set 4 - ANSWER KEY
 Self-assessment Quiz for Practice Set 4 - Answer Key
Started on	Monday, 15 June 2026, 3:00 PM
State	Finished
Completed on	Monday, 15 June 2026, 4:30 PM
Time taken	1 hour 30 mins
Grade	30 out of 30 (100%)
Feedback	
Well done! This is the answer key and feedback for Practice Set 4.

---

### Section A - Logic & Reasoning

Question 1
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Number pattern: `1, 2, 6, 24, 120, ?`
Select one:
a. 240
b. 600
c. 720 Correct! The sequence represents factorials of consecutive integers: 1!, 2!, 3!, 4!, 5!. The next term is 6! = 720. (Alternatively: 1*2=2, 2*3=6, 6*4=24, 24*5=120, 120*6=720).
d. 840
Feedback
The correct answer is: 720

Question 2
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Two workers can complete a task in `6 hours` and `9 hours` respectively. If both work together at their constant rates, how long will it take to finish one task?
Select one:
a. 3.6 hours Correct! The combined work rate is 1/6 + 1/9 = 3/18 + 2/18 = 5/18 task per hour. The time to finish is 1 / (5/18) = 18/5 = 3.6 hours (3 hours and 36 minutes).
b. 3.8 hours
c. 4 hours
d. 3 hours
Feedback
The correct answer is: 3.6 hours

Question 3
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Consider these statements:
- All accessible apps are user-centered.
- Some user-centered products fail in the market.
- Therefore, some accessible apps fail in the market.

Is the conclusion logically valid?
Select one:
a. Yes, because accessible apps are user-centered, and since some user-centered products fail, some accessible apps must fail.
b. No, because the group of user-centered products that fail does not necessarily overlap with the subset that are accessible apps. Correct! All accessible apps could be in the subset of user-centered products that succeed. The conclusion is not logically guaranteed.
c. Yes, because accessible apps are difficult to monetize, making them fail.
d. No, because no accessible apps ever fail in the market.
Feedback
The correct answer is: No, because the group of user-centered products that fail does not necessarily overlap with the subset that are accessible apps.

Question 4
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Number pattern: `7, 10, 16, 25, 37, ?`
Select one:
a. 50
b. 51
c. 52 Correct! The differences between terms are consecutive multiples of 3: +3, +6, +9, +12. The next difference is +15, which yields 37 + 15 = 52.
d. 53
Feedback
The correct answer is: 52

Question 5
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
A runner increases their average pace from `8 km/h` to `10 km/h` on a `20 km` route. How much time is saved?
Select one:
a. 15 minutes
b. 30 minutes Correct! Time at 8 km/h is 20/8 = 2.5 hours. Time at 10 km/h is 20/10 = 2 hours. The time saved is 2.5 - 2.0 = 0.5 hours, which is 30 minutes.
c. 45 minutes
d. 20 minutes
Feedback
The correct answer is: 30 minutes

Question 6
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Evaluate the logical validity of the following argument:
- If a feature is confusing, users drop off.
- Users did not drop off.
- Therefore, the feature is not confusing.

Select one:
a. Not valid, because user behavior is unpredictable.
b. Valid, because by Modus Tollens (If P then Q; Not Q; Therefore Not P), the absence of the effect (drop off) guarantees the absence of the sufficient cause (confusing feature). Correct! Under strict deductive logic, this argument is valid.
c. Not valid, because it is denying the antecedent.
d. Valid, because users never drop off from confusing features.
Feedback
The correct answer is: Valid, because by Modus Tollens (If P then Q; Not Q; Therefore Not P), the absence of the effect (drop off) guarantees the absence of the sufficient cause (confusing feature).

---

### Section B - Programming / Swift Basics

Question 7
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let n = [1, 2, 3, 4]
let out = n.filter { $0 % 2 == 0 }.reduce(0, +)
print(out)
```
Select one:
a. `10`
b. `6` Correct! The filter keeps even numbers `[2, 4]`. The reduce sums them: 2 + 4 = 6.
c. `4`
d. `2`
Feedback
The correct answer is: `6`

Question 8
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This correctly uses a `Set` for O(1) membership checks and an `Array` to preserve the original first-seen sequence order.
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
Feedback
The correct answer is:
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

Question 9
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the primary difference in architecture/nesting between `guard let` and `if let` in Swift?
Select one:
a. `guard let` is used for classes, and `if let` is used for structs.
b. `guard let` is designed to handle exit paths early and keeps the happy path flat, whereas `if let` wraps the success path inside a nested conditional scope. Correct! This highlights the syntactic and flow-control differences between the two optional binding mechanisms.
c. `if let` runs faster than `guard let` under heavy CPU load.
d. `guard let` can unwrap multiple values, but `if let` can only unwrap one.
Feedback
The correct answer is: `guard let` is designed to handle exit paths early and keeps the happy path flat, whereas `if let` wraps the success path inside a nested conditional scope.

Question 10
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let texts = ["10", "x", "20", "30a", "40"]
let total = texts.compactMap(Int.init).reduce(0, +)
print(total)
```
Select one:
a. `100`
b. `70` Correct! The initializer `Int.init` parses strings. "10", "20", and "40" parse successfully, whereas "x" and "30a" return nil and are filtered out by `compactMap`. The sum of `[10, 20, 40]` is 70.
c. `10`
d. `0`
Feedback
The correct answer is: `70`

Question 11
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which Swift implementation correctly returns at most the two largest integers from an array in descending order?
Select one:
a.
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return Array(values.sorted(by: >).prefix(2))
}
``` Correct! Sorting descending (`>`) and using `prefix(2)` yields up to 2 largest elements. Wrapping in `Array` converts the slice back to an array.
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
Feedback
The correct answer is:
```swift
func topTwoDescending(_ values: [Int]) -> [Int] {
    return Array(values.sorted(by: >).prefix(2))
}
```

Question 12
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This safely unwraps the optional and binds the parsed integer into `n` in a single flow, performing the parsing operation only once.
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
Feedback
The correct answer is:
```swift
let input: String? = "15"
if let input, let n = Int(input) {
    print(n * 2)
}
```

---

### Section C - OOP & Swift Concepts

Question 13
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Why are strong reference cycles (memory leaks) a risk when using classes but not when using plain structures in Swift?
Select one:
a. Structs have complex garbage collection routines built-in.
b. Classes are reference types and store instances in heap memory with multiple shared references (which can form circular reference dependencies), whereas structs are value types copied by value and do not support shared references. Correct! Since structs copy their data and do not maintain shared instances, they cannot form reference cycles.
c. Classes are always compiled on the stack, where cycles occur.
d. Structs are compiled in C, which automatically handles reference counting.
Feedback
The correct answer is: Classes are reference types and store instances in heap memory with multiple shared references (which can form circular reference dependencies), whereas structs are value types copied by value and do not support shared references.

Question 14
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
When is it preferable to define and adopt a protocol rather than creating a subclass hierarchy in Swift?
Select one:
a. When you want to allow instances to have shared mutable storage.
b. When you need to define a shared behavioral contract across multiple unrelated types without forcing them into a rigid, tightly coupled parent-child inheritance structure. Correct! Protocol-oriented programming is preferred for decoupling types and enabling flexible behavior compositions.
c. When all conforming types are guaranteed to be classes.
d. When subclassing is not supported by the iOS operating system.
Feedback
The correct answer is: When you need to define a shared behavioral contract across multiple unrelated types without forcing them into a rigid, tightly coupled parent-child inheritance structure.

Question 15
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is a performance or architectural reason to mark a Swift class or member as `final`?
Select one:
a. It allows other classes to subclass it dynamically.
b. It prevents classes from conforming to protocols.
c. It prevents subclass overriding, which helps maintain the architecture boundaries, and allows the compiler to optimize calls by using direct dispatch instead of dynamic table dispatch. Correct! Direct dispatch reduces runtime call overhead and enables compiler inlining.
d. It automatically shifts reference storage from heap to stack.
Feedback
The correct answer is: It prevents subclass overriding, which helps maintain the architecture boundaries, and allows the compiler to optimize calls by using direct dispatch instead of dynamic table dispatch.

Question 16
Correct
Mark 1 out of 1
Not flaggedFlag question
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
c. `2 3` Correct! `Config` is a struct (value type). Passing `c1` into `update` passes a copy. The function mutations do not modify the original `c1.retries`.
d. `3 2`
Feedback
The correct answer is: `2 3`

Question 17
Correct
Mark 1 out of 1
Not flaggedFlag question
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
b. `1` Correct! `Counter` is a class (reference type), so the reference is passed to `increment`. Modifying the object inside the function mutates the same instance, changing `c.value` to 1.
c. The code will crash at runtime.
d. The code will fail to compile.
Feedback
The correct answer is: `1`

Question 18
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This correctly uses generics/associatedtypes to define a clear protocol contract for a cache system.
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
Feedback
The correct answer is:
```swift
protocol Cacheable {
    associatedtype Key: Hashable
    associatedtype Value
    mutating func set(_ value: Value, for key: Key)
    func get(_ key: Key) -> Value?
}
```

---

### Section D - Design & UX

Question 19
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which group of features represents the most appropriate MVP (V1) scope for a transit application focused on accessibility?
Select one:
a. Premium subscription tiers, social media travel sharing, dark mode, weather forecasting, and custom route themes.
b. Accessible route search, step-free station filtering, real-time voice guidance, disruption alerts, and saved frequent trips. Correct! These address the primary needs of visually and mobility-impaired users directly.
c. 3D station models, community chat forums, in-app mini-games, and integration with fitness bands.
d. AI shuttle passenger forecasting, driver tip system, and local sightseeing recommendations.
Feedback
The correct answer is: Accessible route search, step-free station filtering, real-time voice guidance, disruption alerts, and saved frequent trips.

Question 20
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What are three primary user experience (UX) risks associated with a 9-step booking or checkout flow?
Select one:
a. Fast loading speed, low error count, and high user focus.
b. High user drop-off rate, accumulation of input validation errors, and cognitive overload leading to abandonment. Correct! Multi-step flows introduce significant friction and user fatigue on mobile.
c. Increased device storage usage, compiler warnings, and battery draining.
d. Lack of support for custom typography, missing dark mode, and lack of horizontal scrolling.
Feedback
The correct answer is: High user drop-off rate, accumulation of input validation errors, and cognitive overload leading to abandonment.

Question 21
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
How does the design pattern of "progressive disclosure" improve app completion rates?
Select one:
a. By showing all possible configurations and options on the first page to save taps.
b. By presenting only necessary information initially, revealing advanced options or fields contextually as needed to avoid overwhelming the user. Correct! This matches the definition and benefit of progressive disclosure, reducing upfront cognitive load.
c. By forcing the user to progress through pages quickly using timers.
d. By using animations that lock the screen until the user reads the text.
Feedback
The correct answer is: By presenting only necessary information initially, revealing advanced options or fields contextually as needed to avoid overwhelming the user.

Question 22
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
If you have 2 weeks left before the app launch and discover critical usability issues in testing, which triage framework should you adopt?
Select one:
a. Fix everything in alphabetical order.
b. Prioritize issues by Severity x Frequency x User Impact; resolve critical blocking flows first and defer visual polish or minor issues to V2. Correct! This ensures the app is functional and stable on its primary paths before release.
c. Ignore all issues and launch on time, resolving problems only when bad reviews appear.
d. Re-design the entire user interface from scratch.
Feedback
The correct answer is: Prioritize issues by Severity x Frequency x User Impact; resolve critical blocking flows first and defer visual polish or minor issues to V2.

Question 23
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
You observe that user retention drops significantly after day 3 of downloading your app. Which three data slices should you inspect first?
Select one:
a. App store rating, developer line count, and database size.
b. Retention cohorts segmented by acquisition channel, device/performance specifications, and user path tracking within the first session. Correct! Segmenting cohorts helps identify if drops are caused by poor channel matching, performance bottlenecks, or confusion during the initial experience.
c. Server logs, push notification volume, and code reviews.
d. Marketing budgets, competitor updates, and daily active users.
Feedback
The correct answer is: Retention cohorts segmented by acquisition channel, device/performance specifications, and user path tracking within the first session.

Question 24
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Make accessibility much better"?
Select one:
a. "Improve accessibility options."
b. "Raise accessibility audit score from 68 to 90 by adding screen-reader labels, contrast-compliant colors, and dynamic type support across the core booking flow." Correct! This specifies measurable standards and concrete engineering deliverables.
c. "The app must be easy to use for disabled users."
d. "Add a toggle for accessibility on the home screen."
Feedback
The correct answer is: "Raise accessibility audit score from 68 to 90 by adding screen-reader labels, contrast-compliant colors, and dynamic type support across the core booking flow."

---

### Section E - Motivation & Soft Skills

Question 25
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
You are asked to describe a failure that improved your way of working. Which response shows the highest level of accountability and professional growth?
Select one:
a. "A project failed because my team members did not work hard enough. Next time, I will make sure they do their jobs."
b. "We missed a project deadline because of poor task estimations. I took responsibility, analyzed our tracking gaps, and introduced a scrum board with daily standups in our next project, which helped us deliver all subsequent features on time." Correct! This demonstrates ownership of failure, analysis of the cause, implementation of a corrective framework, and positive outcomes.
c. "The project was a failure, but since it was only a prototype, I didn't care much."
d. "I have never failed; all my projects have been perfect successes."
Feedback
The correct answer is: "We missed a project deadline because of poor task estimations. I took responsibility, analyzed our tracking gaps, and introduced a scrum board with daily standups in our next project, which helped us deliver all subsequent features on time."

Question 26
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
How do you contribute to a project when your role is not formally defined?
Select one:
a. I wait until the team leader gives me a formal list of tasks.
b. I observe the team's needs, identify gaps (e.g., missing tests or undocumented requirements), propose where I can add value, and collaborate with others to fill those gaps proactively. Correct! Proactive contribution and filling execution gaps are highly valued attributes in cross-functional, flat teams.
c. I focus only on coding my own parts and don't get involved in other work.
d. I complain about the lack of project structure to the mentors.
Feedback
The correct answer is: I observe the team's needs, identify gaps (e.g., missing tests or undocumented requirements), propose where I can add value, and collaborate with others to fill those gaps proactively.

Question 27
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which response describes the most appropriate tradeoff made under deadline pressure?
Select one:
a. "I disabled user input validation to complete the registration screen faster."
b. "We had to deliver a prototype. Under pressure, we scoped out the custom profile editor and focused on securing the primary booking flow, logging the profile work for V2 while keeping our code base tested and clean." Correct! This prioritizes core functionality and maintains code quality/testing while pragmatically reducing secondary scope.
c. "I wrote messy code to meet the date, hoping to fix it later, though we never did."
d. "I extended our deadline by two weeks without asking the product owner."
Feedback
The correct answer is: "We had to deliver a prototype. Under pressure, we scoped out the custom profile editor and focused on securing the primary booking flow, logging the profile work for V2 while keeping our code base tested and clean."

Question 28
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
How do you ensure that quieter or less confident teammates are heard during discussions?
Select one:
a. By speaking louder to ensure the team stays on topic.
b. By actively pausing the discussion, asking quieter teammates for their thoughts on specific areas, and creating a supportive, non-judgmental environment. Correct! Active facilitation and encouraging inclusive input is vital for team synergy.
c. By assuming they agree with the majority if they remain silent.
d. By assigning them tasks without asking for their input first.
Feedback
The correct answer is: By actively pausing the discussion, asking quieter teammates for their thoughts on specific areas, and creating a supportive, non-judgmental environment.

Question 29
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What impact do you want your app development work to create in 3 years?
Select one:
a. "I want to have built several apps that generate advertising revenue for myself."
b. "I want to design and deploy apps that improve daily life for underserved communities, such as facilitating accessible transport or digital literacy for seniors, showing measurable improvements in their independence." Correct! This highlights a purpose-driven, impact-oriented long-term vision.
c. "I want to be recognized as the fastest coder in my company."
d. "I hope to write code that does not require maintenance."
Feedback
The correct answer is: "I want to design and deploy apps that improve daily life for underserved communities, such as facilitating accessible transport or digital literacy for seniors, showing measurable improvements in their independence."

Question 30
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
How do you recover after receiving tough criticism on your work?
Select one:
a. I ignore it and keep doing my work the same way.
b. I process it non-defensively, separate my ego from my work, seek clarification on specific points, and create a concrete checklist of actions to improve my performance. Correct! This shows emotional intelligence, professional resilience, and an action-oriented growth mindset.
c. I express my frustration to the team and refuse to work.
d. I ask the team to assign me to a different project.
Feedback
The correct answer is: I process it non-defensively, separate my ego from my work, seek clarification on specific points, and create a concrete checklist of actions to improve my performance.
