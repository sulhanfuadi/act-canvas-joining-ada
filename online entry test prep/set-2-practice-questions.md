Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 1 - Practice Set 2
 Self-assessment Quiz for Practice Set 2
Time limit: 90 minutes
Suggested split: A 20m, B 20m, C 15m, D 15m, E 20m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `4, 7, 12, 19, 28, ?`
Select one:
a. 37
b. 38
c. 39
d. 40

Question 2
Question text
A courier drives at `45 km/h`. How long will it take to cover `135 km`?
Select one:
a. 2 hours
b. 2.5 hours
c. 3 hours
d. 3.5 hours

Question 3
Question text
Consider these statements:
- All mentors are learners.
- Some learners are designers.
- Therefore, some mentors are designers.

Is the conclusion logically valid?
Select one:
a. Yes, because mentors are learners, and some learners are designers.
b. No, because the group of learners who are designers does not necessarily overlap with the group of learners who are mentors.
c. Yes, because all designers are mentors.
d. No, because no mentors can be designers.

Question 4
Question text
Number pattern: `1, 3, 7, 13, 21, ?`
Select one:
a. 29
b. 30
c. 31
d. 33

Question 5
Question text
A project is `3/8` completed on Monday and `1/4` completed on Tuesday. What fraction of the project remains to be done?
Select one:
a. 5/8
b. 3/8
c. 1/2
d. 1/8

Question 6
Question text
Evaluate the logical validity of the following argument:
- All Swift apps are software.
- Some software is open source.
- Therefore, some Swift apps are open source.

Select one:
a. Valid, because Swift apps are software, and some software is open source.
b. Not always valid, because the open-source software might not include any Swift apps.
c. Valid, because all Swift apps are open source.
d. Invalid, because no software is open source.

---

### Section B - Programming / Swift Basics

Question 7
Question text
What is the output of the following Swift code?
```swift
let arr = [2, 4, 6]
print(arr.map { $0 - 1 })
```
Select one:
a. `[2, 4, 6]`
b. `[1, 3, 5]`
c. `[1, 2, 3]`
d. `[3, 5, 7]`

Question 8
Question text
Which Swift implementation correctly and cleanly returns values greater than 10 from an array of integers?
Select one:
a.
```swift
func greaterThanTen(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 > 10 }
}
```
b.
```swift
func greaterThanTen(_ numbers: [Int]) -> [Int] {
    return numbers.map { $0 > 10 }
}
```
c.
```swift
func greaterThanTen(_ numbers: [Int]) -> [Int] {
    return numbers.filter { $0 >= 10 }
}
```
d.
```swift
func greaterThanTen(_ numbers: [Int]) -> [Int] {
    var result: [Int] = []
    for n in numbers {
        if n < 10 { result.append(n) }
    }
    return result
}
```

Question 9
Question text
In Swift, what does the declaration `let age: Int?` represent?
Select one:
a. An integer constant initialized to zero.
b. An optional integer constant that can hold either an `Int` value or `nil`.
c. A non-optional integer constant that is optional to specify.
d. A dynamic type variable.

Question 10
Question text
What is the output of the following Swift code?
```swift
let nums = [1, 2, 3, 4, 5]
let result = nums.filter { $0 % 2 == 1 }.map { $0 * 3 }
print(result)
```
Select one:
a. `[3, 9, 15]`
b. `[6, 12]`
c. `[3, 6, 9, 12, 15]`
d. `[1, 3, 5]`

Question 11
Question text
Which implementation correctly completes the function `maxValue(_:)` to return the maximum item, or `nil` if the array is empty?
Select one:
a.
```swift
func maxValue(_ items: [Int]) -> Int? {
    return items.max()
}
```
b.
```swift
func maxValue(_ items: [Int]) -> Int? {
    return items.sorted().first
}
```
c.
```swift
func maxValue(_ items: [Int]) -> Int? {
    return items[0]
}
```
d.
```swift
func maxValue(_ items: [Int]) -> Int? {
    return items.reduce(0, +)
}
```

Question 12
Question text
Which code snippet safely refactors the following unsafe force-unwrapped print statement to avoid crash risks?
```swift
var title: String? = nil
print(title!.uppercased())
```
Select one:
a. `print(title?.uppercased() ?? "")`
b. `print(title!.uppercased() ?? "")`
c. `print(title.uppercased())`
d. `if title == nil { print(title!) }`

---

### Section C - OOP & Swift Concepts

Question 13
Question text
What is one practical reason to prefer a `struct` over a `class` in Swift app development?
Select one:
a. Structs support multithreaded class inheritance.
b. Structs use value semantics, which copies the instance on assignment and reduces the risk of accidental shared-state mutation bugs.
c. Structs allow multiple parts of the app to share a single mutable reference.
d. Structs are always stored on the heap, making retrieval faster.

Question 14
Question text
Why are optionals considered safer than using placeholder defaults (like empty strings or negative numbers) to represent the absence of data?
Select one:
a. Optionals automatically clean up memory cycles.
b. Optionals explicitly model the absence of data at the type level, forcing developers to handle the `nil` state before accessing the value.
c. Optionals speed up execution time of functions.
d. Optionals prevent variables from being re-assigned.

Question 15
Question text
Does a `struct` support inheritance in Swift?
Select one:
a. Yes, structures support full single-inheritance similar to classes.
b. No, structs do not support inheritance.
c. Yes, but only if they conform to the `AnyObject` protocol.
d. Yes, but only from classes.

Question 16
Question text
Predict the output of the following code snippet:
```swift
struct Point {
    var x: Int
}
var p1 = Point(x: 5)
var p2 = p1
p2.x = 9
print(p1.x, p2.x)
```
Select one:
a. `5 5`
b. `9 9`
c. `5 9`
d. `9 5`

Question 17
Question text
Predict the output of the following Swift code:
```swift
class User {
    var name: String
    init(name: String) { self.name = name }
}
let u1 = User(name: "Ana")
let u2 = u1
u2.name = "Budi"
print(u1.name, u2.name)
```
Select one:
a. `Ana Ana`
b. `Budi Budi`
c. `Ana Budi`
d. `Budi Ana`

Question 18
Question text
Which snippet correctly defines a protocol `Readable` with a method `read() -> String` and a type conforming to it?
Select one:
a.
```swift
protocol Readable {
    func read() -> String
}
struct Note: Readable {
    func read() -> String {
        return "content"
    }
}
```
b.
```swift
class Readable {
    func read() -> String { return "" }
}
struct Note: Readable {}
```
c.
```swift
protocol Readable {
    var content: String { get }
}
```
d.
```swift
struct Readable {
    func read() -> String { return "content" }
}
```

---

### Section D - Design & UX

Question 19
Question text
Which set of features represents the most appropriate MVP (V1) scope for a mobile bus ticket booking app?
Select one:
a. Live driver chat, social media sharing, custom bus colors, weather forecast integration, premium animations.
b. Route search, schedule viewing, seat selection, checkout/payment, and digital ticket history.
c. Interactive 3D terminal maps, chatbot customer service, virtual reality seat preview, referral points system.
d. Background music, promotional banners, user review forum, developer credits screen.

Question 20
Question text
Which three design techniques are most effective at improving form usability on mobile screens?
Select one:
a. Small tap targets, multi-column layouts, and hidden error messages.
b. Clear labels, inline real-time validation, and large tap targets.
c. All-caps labels, removing placeholder hints, and hiding input fields.
d. High-contrast background animations, multi-step nested modals, and small fonts.

Question 21
Question text
Why should visual or haptic feedback be immediate after a user performs an action in a mobile application?
Select one:
a. It speeds up the processing time of the server.
b. It reduces user uncertainty, confirms that the action was registered, and prevents repeated accidental actions (like double-taps).
c. It ensures the app complies with strict App Store submission rules.
d. It decreases the battery consumption of the mobile device.

Question 22
Question text
If you are forced to reduce the development scope of an app by 30% close to launch, how should you determine which features to keep in V1?
Select one:
a. Keep only the easiest features to program, regardless of value.
b. Keep the core journey that directly solves the main user problem (e.g., find route -> select seat -> pay -> ticket issued) and defer supplementary features.
c. Cut the security and login features first.
d. Keep the features proposed by the most senior developer.

Question 23
Question text
A transit app exhibits a low onboarding completion rate. Which three signals should you inspect first to identify the source of friction?
Select one:
a. CPU usage, app download size, and compiler warnings.
b. Cohort drop-off rate by step, time spent on each onboarding screen, and first-error rates in input fields.
c. Daily active users, total downloads, and server request count.
d. Customer reviews on competitor apps, marketing click-throughs, and code line count.

Question 24
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Users should book faster"?
Select one:
a. "Improve booking speed."
b. "Increase booking completion rate from 58% to 72% by reducing checkout steps from 5 to 3."
c. "The booking page should load in less than 5 seconds."
d. "Remove the checkout page completely."

---

### Section E - Motivation & Soft Skills

Question 25
Question text
Which application statement best illustrates your motivation to join the Apple Developer Academy this year?
Select one:
a. "I want to apply because my parents suggested I do it to fill my gap year."
b. "I am applying this year to gain hands-on experience in mobile app development, learn how to collaborate effectively in diverse teams under the challenge-based learning framework, and build impactful solutions for local communities."
c. "I am applying because I want to get access to Apple devices and workspace resources for my personal projects."
d. "I hope to join because I want a certificate that helps me skip university courses."

Question 26
Question text
You are asked to describe a time you learned a new technical concept quickly. Which response best demonstrates an active learning mindset?
Select one:
a. "I learned it quickly by copying code templates from GitHub without reading the documentation."
b. "I needed to implement data persistence in a project. I studied SwiftData fundamentals, built a mini-prototype to test basic CRUD operations, noted my errors, and integrated the learned patterns into our team project within 3 days."
c. "I attended a lecture and understood everything instantly without needing to practice."
d. "I asked a senior teammate to write the code for me and explain it later."

Question 27
Question text
You experience a conflict with a teammate regarding a design choice. Which response shows the most collaborative conflict resolution?
Select one:
a. "I insisted on my choice because I have more design experience than they do."
b. "I listened to their perspective, proposed that we test both designs with target users to collect objective feedback, and agreed to proceed with the option that yielded the best usability results."
c. "I complained to the mentor so they would force the teammate to accept my design."
d. "I stepped back and stopped contributing to the design process entirely."

Question 28
Question text
What does collaboration mean to you in product development?
Select one:
a. Dividing tasks strictly so that developers don't have to talk to designers.
b. Leveraging the diverse strengths, backgrounds, and perspectives of team members to solve user problems collectively, keeping communication open, and aligning towards a shared vision.
c. Enforcing a single leader's opinion to ensure fast execution.
d. Simply sharing a code repository without coordinating features.

Question 29
Question text
Which description of a social problem and app-based solution shows the highest user empathy?
Select one:
a. "The elderly don't use technology. I want to build a complex banking app with artificial intelligence to show them how to do it."
b. "Elderly users struggle to book medical appointments due to small fonts and complex flows. I want to build a simplified appointment scheduler with large targets, VoiceOver support, and direct contact options based on user interviews."
c. "I want to build a game to help kids stay quiet during dinners."
d. "I want to build a social app for elite fitness enthusiasts."

Question 30
Question text
How do you react when your team rejects an idea you proposed?
Select one:
a. I feel defensive and stop contributing to team discussions.
b. I listen to the team's reasons, seek to understand their concerns, and work with them to find a better alternative, recognizing that team alignment is more important than my personal ideas.
c. I keep bringing up the same idea until they agree just to stop the debate.
d. I work on the idea in secret and implement it anyway.
