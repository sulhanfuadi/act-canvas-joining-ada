Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 ONLINE ENTRY TEST - PRACTICE
 Self-assessment Quiz - Practice Simulation (Sections A-E)
Time limit: 90 minutes
Suggested split: A 20m, B 20m, C 15m, D 15m, E 20m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `3, 6, 11, 18, 27, ?`
Select one:
a. 36
b. 37
c. 38
d. 39

Question 2
Question text
A bike moves at `24 km/h`. How long will it take to travel `72 km`?
Select one:
a. 2 hours
b. 3 hours
c. 4 hours
d. 2.5 hours

Question 3
Question text
If all iOS developers are programmers, and some programmers are designers, can we conclude that all iOS developers are designers?
Select one:
a. Yes, because iOS developers are a subset of programmers who are all designers.
b. No, because "some programmers are designers" does not guarantee that the subset of programmers who are iOS developers overlaps with designers.
c. Yes, because design is a fundamental requirement of iOS development.
d. No, because no iOS developers are designers.

Question 4
Question text
Number pattern: `2, 5, 10, 17, 26, ?`
Select one:
a. 35
b. 36
c. 37
d. 38

Question 5
Question text
A team finished `2/5` of a task on Day 1 and `1/4` of the task on Day 2. What fraction of the task is left?
Select one:
a. 13/20
b. 7/20
c. 3/10
d. 9/20

Question 6
Question text
Consider these statements:
- All prototypes are experiments.
- Some experiments fail.
- Therefore, some prototypes fail.

Is the conclusion logically valid?
Select one:
a. Yes, because prototypes are experiments, and since some experiments fail, some prototypes must fail.
b. No, because the experiments that fail do not necessarily have to be prototypes; all prototypes could be in the subset of experiments that succeed.
c. Yes, because failure is a natural part of the prototyping process.
d. No, because all prototypes are guaranteed to fail in the first iteration.

Question 7
Question text
Find the next value in the sequence: `1, 4, 9, 16, 25, 36, ?`
Select one:
a. 45
b. 47
c. 49
d. 50

Question 8
Question text
A train leaves City A at 08:00 at a speed of `60 km/h`. Another train leaves City B traveling toward City A at 09:00 at a speed of `90 km/h`. The distance between City A and City B is `390 km`. At what time do they meet?
Select one:
a. 11:00
b. 11:12
c. 11:20
d. 11:30

Question 9
Question text
You have 3 switches outside a closed room and 3 incandescent lamps inside. You can enter the room only once. How can you identify which switch controls which lamp?
Select one:
a. Turn on switch 1 for a few minutes, turn it off, turn on switch 2, and enter the room.
b. Turn on all three switches, then enter the room and trace the wires.
c. Turn on switch 1 and 2, enter the room, and guess which one controls the brighter lamp.
d. Enter the room first, then call a teammate to flip the switches one by one.

---

### Section B - Swift Fundamentals

Question 10
Question text
What is the output of the following Swift code?
```swift
let numbers = [1, 2, 3]
print(numbers.map { $0 + 1 })
```
Select one:
a. `[1, 2, 3]`
b. `[2, 3, 4]`
c. `[3, 4, 5]`
d. `2, 3, 4`

Question 11
Question text
Which implementation of the function correctly and efficiently returns only odd numbers from an array of integers?
Select one:
a.
```swift
func oddNumbers(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 % 2 != 0 }
}
```
b.
```swift
func oddNumbers(_ numbers: [Int]) -> [Int] {
    return numbers.map { $0 % 2 != 0 ? $0 : nil }.compactMap { $0 }
}
```
c.
```swift
func oddNumbers(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 / 2 != 0 }
}
```
d.
```swift
func oddNumbers(_ numbers: [Int]) -> [Int] {
    var result = [Int]()
    for n in numbers {
        if n % 2 == 0 { result.append(n) }
    }
    return result
}
```

Question 12
Question text
In Swift, what does the declaration `var username: String?` represent?
Select one:
a. A constant string that cannot be modified.
b. An optional variable that can hold either a `String` value or `nil`.
c. A pointer to a String object.
d. A non-optional string variable initialized to an empty string.

Question 13
Question text
What is the output of the following Swift code?
```swift
let values = [2, 4, 6, 8]
let result = values.filter { $0 > 4 }.map { $0 / 2 }
print(result)
```
Select one:
a. `[3, 4]`
b. `[1, 2, 3, 4]`
c. `[2, 3]`
d. `[4, 6, 8]`

Question 14
Question text
Which code snippet correctly completes the function `totalScore(_:)` to return the sum of all elements in the array?
```swift
func totalScore(_ scores: [Int]) -> Int {
    // missing code
}
```
Select one:
a. `return scores.map { $0 }.reduce(0, +)`
b. `return scores.reduce(0, +)`
c. `return scores.sum()`
d. `return scores.filter { $0 > 0 }`

Question 15
Question text
Which refactoring safely handles the optional to print the count of characters without a crash risk if `text` is `nil`?
```swift
var text: String? = nil
print(text!.count) // original unsafe code
```
Select one:
a. `print(text?.count ?? 0)`
b. `print(text!.count ?? 0)`
c. `if text != nil { print(text.count) }`
d. `print(text.count)`

Question 16
Question text
What is the output of the following Swift code?
```swift
let items = ["1", "two", "3", "four"]
let numbers = items.compactMap { Int($0) }
print(numbers.reduce(0, +))
```
Select one:
a. `8`
b. `4`
c. `0`
d. `13`

Question 17
Question text
Which Swift implementation receives `[Int]` and returns only even numbers, sorted descending, and each multiplied by 10?
Select one:
a.
```swift
func transform(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 % 2 == 0 }.sorted(by: >).map { $0 * 10 }
}
```
b.
```swift
func transform(_ numbers: [Int]) -> [Int] {
    return numbers.map { $0 * 10 }.filter { $0 % 2 == 0 }.sorted()
}
```
c.
```swift
func transform(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 % 2 != 0 }.sorted(by: >).map { $0 * 10 }
}
```
b.
```swift
func transform(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 % 2 == 0 }.map { $0 * 10 }.sorted()
}
```

Question 18
Question text
Which statement best illustrates when to use `map`, `filter`, and `compactMap` in Swift?
Select one:
a. Use `map` to remove nil values, `filter` to transform elements, and `compactMap` to select matching items.
b. Use `map` to transform every element, `filter` to keep elements matching a condition, and `compactMap` to transform and discard any resulting nil values.
c. Use `map` for loops, `filter` for if-else logic, and `compactMap` for optional unwrapping.
d. There is no technical difference between the three functions.

---

### Section C - OOP & Swift Concepts

Question 19
Question text
What is the fundamental difference between a `struct` and a `class` in Swift?
Select one:
a. Structs support inheritance, whereas classes do not.
b. Structs are value types (copied on assignment), whereas classes are reference types (shared instance).
c. Structs are reference types, whereas classes are value types.
d. Structs must always be declared with `let`, and classes must be declared with `var`.

Question 20
Question text
What is an `Optional` in Swift and why is it useful?
Select one:
a. It is a keyword used to designate functions that do not return a value.
b. It is a type representing a value that may or may not exist, forcing safe handling to prevent null pointer exceptions.
c. It is a config file used to specify compile-time optimization flags.
d. It is a variable that is optional to declare in classes.

Question 21
Question text
Which types in Swift support inheritance?
Select one:
a. Structs
b. Enums
c. Classes
d. Protocols

Question 22
Question text
Predict the output of the following code snippet:
```swift
struct Counter {
    var value: Int
}
var a = Counter(value: 1)
var b = a
b.value = 10
print(a.value, b.value)
```
Select one:
a. `1 1`
b. `10 10`
c. `1 10`
d. `10 1`

Question 23
Question text
Predict the output of the following code snippet:
```swift
class Box {
    var value: Int
    init(value: Int) { self.value = value }
}
let box1 = Box(value: 1)
let box2 = box1
box2.value = 10
print(box1.value, box2.value)
```
Select one:
a. `1 1`
b. `10 10`
c. `1 10`
d. `10 1`

Question 24
Question text
Which implementation defines a protocol `Payable` with a method `pay(amount:)` and shows a type conforming to it?
Select one:
a.
```swift
protocol Payable {
    func pay(amount: Double)
}
struct Wallet: Payable {
    func pay(amount: Double) {
        print("Paid \(amount)")
    }
}
```
b.
```swift
class Payable {
    func pay(amount: Double) {}
}
struct Wallet: Payable {}
```
c.
```swift
protocol Payable {
    var amount: Double { get }
}
```
d.
```swift
struct Payable {
    func pay(amount: Double) {}
}
```

Question 25
Question text
Which statement best describes the differences and tradeoffs between value semantics and reference semantics in Swift?
Select one:
a. Value semantics allow shared mutable states across the app which optimizes data sync.
b. Value semantics isolate state changes per copy (preventing unintended shared-state bugs), while reference semantics share instances (enabling shared mutable state, but introducing potential side effects).
c. Reference semantics copy data on write, making them safer than value semantics.
d. Structs use reference semantics, which helps prevent memory cycles.

Question 26
Question text
When should you choose to declare a class as a `final class` in Swift?
Select one:
a. When you want to allow subclasses to override only some methods.
b. When inheritance is not intended, which prevents subclassing, protects architecture intent, and enables compiler performance optimizations.
c. When the class has only structures inside.
d. When the class is in a protocol.

Question 27
Question text
If you need to share mutable state across multiple screens in an iOS application, which type should you choose?
Select one:
a. A `struct` because value types are thread-safe by default.
b. A `class` because it allows multiple parts of the app to point to and modify a single, shared instance.
c. An `enum` with associated values.
d. A protocol.

---

### Section D - Design & UX

Question 28
Question text
For a coworking booking app, which group of features represents the most appropriate MVP (V1) scope?
Select one:
a. AI chatbot, dark mode, social media sharing, animated stickers, custom fonts.
b. Location search, date/time selection, room availability view, booking confirmation, payment.
c. Interactive 3D maps, virtual reality tour, premium membership tiers, referral rewards, guest chat.
d. Advanced analytics, team check-in history, push reminders for reviews, dynamic pricing algorithms.

Question 29
Question text
Which 3 techniques are most effective to make navigation clearer for first-time app users?
Select one:
a. Use small font size, hide navigation tabs, and add decorative gestures.
b. Use clear labels, maintain a predictable tab structure, and ensure consistent back behavior.
c. Add modal popups for every button, implement custom back buttons, and use vertical tabs.
d. Replace text with abstract icons, use hidden swipe gestures, and add full-screen introductions.

Question 30
Question text
Why is consistency in mobile user interface (UI) design highly important?
Select one:
a. It prevents the developer from making changes.
b. It reduces cognitive load and learning time because users can transfer their knowledge from one part of the app to another.
c. It guarantees that the app will build faster.
d. It ensures that the app looks exactly like every other app on the market.

Question 31
Question text
You are told you must cut the development scope of an app by 40% before the launch. What is the best strategy?
Select one:
a. Remove testing and documentation to speed up development.
b. Focus only on the core user journey (e.g., discovery -> select -> book -> pay -> confirmation) and defer non-core extras.
c. Keep all features but implement them with lower quality.
d. Cut the payment integration and let users use the app for free.

Question 32
Question text
A user feedback report indicates that the onboarding flow is "confusing." Which three data points should you collect first to diagnose this?
Select one:
a. App store rating, download size, and competitor features.
b. Step-by-step funnel drop-off rates, time spent on each onboarding screen, and qualitative feedback from usability sessions.
c. Developer velocity, app crash logs, and storage usage.
d. Number of page shares, social logins, and notification opt-ins.

Question 33
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Make booking flow better"?
Select one:
a. "Improve booking UI aesthetics."
b. "Reduce median booking completion time from 4m30s to under 2m30s by removing one form step and enabling autofill."
c. "The booking flow should be extremely easy for everyone."
d. "Add more buttons to the booking screen."

Question 34
Question text
Critique this flow from a Human Interface Guidelines (HIG) perspective:
`Home -> 7-step booking form -> payment -> confirmation`
Select one:
a. The flow is perfect because more steps ensure data accuracy.
b. The flow creates high friction. It should be simplified by reducing booking to 3-4 steps, showing progress, prefilling data, delaying non-critical inputs, and enabling guest checkout.
c. The payment step should be moved to the beginning of the flow.
d. The form should be split into 10 separate screens to look cleaner.

Question 35
Question text
An e-commerce app has a high drop-off rate at the payment screen. Which hypothesis-driven test plan is most appropriate?
Select one:
a. Hypothesis A: unexpected fees cause exits; Hypothesis B: too many fields cause friction. Experiment A: show fees early; Experiment B: simplify forms. Measure payment completion rates.
b. Hypothesis A: users don't like the product; Hypothesis B: app is too fast. Experiment: change logo. Measure daily active users.
c. Hypothesis A: payment screen needs dark mode; Hypothesis B: payment should be free. Experiment: add dark mode. Measure downloads.
d. Hypothesis: people are busy. Experiment: send daily reminder emails. Measure open rates.

Question 36
Question text
How would you design accessibility support for users with visual and mobility constraints in a transit app?
Select one:
a. Focus on standard designs and ignore accessibility unless requested.
b. Implement screen-reader labels (VoiceOver), large touch targets with high contrast, step-free route indicators, and a feedback loop for accessibility updates.
c. Add complex gesture shortcuts and small text to save screen space.
d. Create a separate app specifically for disabled users.

---

### Section E - Motivation & Soft Skills

Question 37
Question text
Which response best explains why you want to join the Apple Developer Academy this year rather than later?
Select one:
a. "I have free time this year, and my friends are also applying, so it seemed like a fun thing to do."
b. "The Academy matches my immediate learning goals of transitioning to mobile development, collaborating in cross-functional teams, and building apps that solve real-world problems today."
c. "I am waiting to see if I get a better job offer first; if not, I will join."
d. "I think the Academy will make it easy to get a certification with minimum effort."

Question 38
Question text
You started a personal coding project but did not finish it. How do you reflect on this experience?
Select one:
a. "It was a waste of time, and I realized that coding is too hard for me."
b. "I analyzed why I stopped—which was lack of structured scope. I learned to scope projects into smaller, achievable milestones, a practice I now apply to ensure project completion."
c. "The project was perfect, but my teammates were lazy, so I abandoned it."
d. "I don't think about it; unfinished projects are normal and don't need explanation."

Question 39
Question text
During a project review, you receive critical feedback on your UI design. How should you respond?
Select one:
a. Defend your design choices immediately to prove the feedback is wrong.
b. Listen actively, acknowledge the feedback, ask clarifying questions to understand the underlying issues, and iterate on the design to address the concerns.
c. Agree with the feedback but ignore it in the next design iteration.
d. Report the feedback giver to the team lead for criticizing your work.

Question 40
Question text
What is your first move when a conflict arises within your project team, and why?
Select one:
a. Vote to remove the dissenting teammate to restore peace.
b. Listen to all perspectives empathetically to find the root cause, seeking common ground and collaborative alignment rather than enforcing individual opinions.
c. Avoid the conflict and let the team figure it out on their own.
d. Escalate the conflict to the instructors immediately without trying to resolve it.

Question 41
Question text
Which app idea description demonstrates the strongest user-centered, problem-first thinking?
Select one:
a. "An app that uses complex blockchain algorithms just because the technology is trending."
b. "An app that helps local farmers sell surplus produce directly to nearby households, reducing food waste and lowering grocery costs for families based on community interviews."
c. "A clone of a popular app with a different color scheme."
d. "An app designed to show ads to users so I can earn passive income quickly."

Question 42
Question text
If selected for the Apple Developer Academy, how will you contribute to the learning of your peers?
Select one:
a. By doing all the work myself to ensure the project gets a perfect score.
b. By actively sharing my technical knowledge, facilitating group learning, offering constructive feedback, and listening to peers with different backgrounds.
c. By focusing solely on my own projects and ignoring other students' issues.
d. By criticizing teammates when they make mistakes so they learn faster.
