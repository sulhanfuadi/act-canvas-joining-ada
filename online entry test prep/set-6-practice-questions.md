Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 5 - Practice Set 6
 Self-assessment Quiz for Practice Set 6
Time limit: 90 minutes
Suggested split: A 15m, B 40m, C 20m, D 10m, E 5m

---

### Section A - Logic & Reasoning

Question 1
Question text
Number pattern: `9, 13, 19, 27, ?`
Select one:
a. 35
b. 36
c. 37
d. 39

Question 2
Question text
A train covers `210 km` in `3.5 hours`. What is its average speed?
Select one:
a. 50 km/h
b. 55 km/h
c. 60 km/h
d. 65 km/h

Question 3
Question text
Consider these statements:
- All testers are detail-oriented.
- Some detail-oriented people are designers.
- Therefore, some testers are designers.

Is the conclusion logically valid?
Select one:
a. Yes, because testers are detail-oriented, and some detail-oriented people are designers.
b. No, because the group of detail-oriented people who are designers does not necessarily overlap with the subset who are testers.
c. Yes, because all designers are testers.
d. No, because testers can never be designers.

---

### Section B - Programming / Swift Basics

Question 4
Question text
What is the output of the following Swift code?
```swift
let numbers = [1, 2, 3, 4]
print(numbers.map { $0 * $0 })
```
Select one:
a. `[1, 2, 3, 4]`
b. `[1, 4, 9, 16]`
c. `[2, 4, 6, 8]`
d. `[0, 1, 4, 9]`

Question 5
Question text
What is the output of the following Swift code?
```swift
let nums = [10, 15, 20, 25]
let result = nums.filter { $0 % 10 == 0 }.map { $0 / 5 }
print(result)
```
Select one:
a. `[2, 4]`
b. `[2, 3, 4, 5]`
c. `[2, 3]`
d. `[4, 8]`

Question 6
Question text
Which Swift implementation correctly filters an array of strings, returning only non-empty strings with their leading/trailing whitespaces and newlines removed?
Select one:
a.
```swift
func nonEmptyTrimmed(_ values: [String]) -> [String] {
    return values
        .map { $0.trimmingCharacters(in: .whitespacesAndNewlines) }
        .filter { !$0.isEmpty }
}
```
b.
```swift
func nonEmptyTrimmed(_ values: [String]) -> [String] {
    return values.filter { !$0.isEmpty }
}
```
c.
```swift
func nonEmptyTrimmed(_ values: [String]) -> [String] {
    return values.map { $0.trimmingCharacters(in: .whitespaces) }
}
```
d.
```swift
func nonEmptyTrimmed(_ values: [String]) -> [String] {
    return values.compactMap { $0.isEmpty ? nil : $0 }
}
```

Question 7
Question text
Which statement best explains the purpose of the `compactMap` higher-order function in Swift?
Select one:
a. It aggregates numbers and returns a single summary value.
b. It transforms each element of a collection, discarding any resulting `nil` values, and returns a flat array of non-optional elements.
c. It sorts the array in descending order while removing duplicates.
d. It executes a block of code asynchronously on a background thread.

Question 8
Question text
Which code snippet correctly completes the function `safeInt(_:)` to parse an optional String into an optional Int safely?
```swift
func safeInt(_ text: String?) -> Int? {
    // missing code
}
```
Select one:
a.
```swift
    guard let text else { return nil }
    return Int(text)
```
b. `return Int(text!)`
c. `return text as? Int`
d. `if text != nil { return Int(text) } else { return 0 }`

Question 9
Question text
Which snippet safely refactors the following unsafe print statement?
```swift
let name: String? = nil
print(name!.count)
```
Select one:
a. `print(name?.count ?? 0)`
b. `print(name!.count ?? 0)`
c. `print(name.count)`
d. `if name != nil { print(name.count) }`

Question 10
Question text
What is the output of the following Swift code?
```swift
let values = ["1", "2", "x", "4"]
let total = values.compactMap(Int.init).reduce(0, +)
print(total)
```
Select one:
a. `7`
b. `6`
c. `0`
d. `x`

Question 11
Question text
Which Swift implementation receives an array of integers, filters for odd numbers, sorts them ascending, and returns them as a comma-separated String?
Select one:
a.
```swift
func oddSortedCSV(_ values: [Int]) -> String {
    return values
        .filter { $0 % 2 != 0 }
        .sorted()
        .map(String.init)
        .joined(separator: ",")
}
```
b.
```swift
func oddSortedCSV(_ values: [Int]) -> String {
    return values.filter { $0 % 2 == 0 }.map(String.init).joined(separator: ",")
}
```
c.
```swift
func oddSortedCSV(_ values: [Int]) -> String {
    return values.sorted().map { String($0) }.joined(separator: ",")
}
```
d.
```swift
func oddSortedCSV(_ values: [Int]) -> String {
    return values.filter { $0 % 2 != 0 }.map(String.init).joined()
}
```

Question 12
Question text
Why is early return with the `guard` statement often preferred over nested `if` statements in Swift?
Select one:
a. It runs faster because it bypasses safety checks.
b. It keeps the "happy path" (success flow) flat, reduces deep indentation nesting, and makes exit conditions explicit.
c. It forces class inheritance to be resolved at compile time.
d. It automatically releases memory of unused parameters.

Question 13
Question text
Which implementation correctly completes the generic function `firstTwo(_:)` to return an array containing at most the first two items of any type?
```swift
func firstTwo<T>(_ items: [T]) -> [T] {
    // missing code
}
```
Select one:
a. `return Array(items.prefix(2))`
b. `return [items[0], items[1]]`
c. `return items.filter { _ in true }`
d. `return Array(items.suffix(2))`

---

### Section C - OOP & Swift Concepts

Question 14
Question text
Predict the output of the following Swift code:
```swift
class Node {
    var v: Int
    init(_ v: Int) { self.v = v }
}
let n1 = Node(3)
let n2 = n1
n2.v = 9
print(n1.v, n2.v)
```
Select one:
a. `3 3`
b. `9 9`
c. `3 9`
d. `9 3`

Question 15
Question text
Predict the output of the following Swift code:
```swift
struct Box {
    var v: Int
}
var b1 = Box(v: 3)
var b2 = b1
b2.v = 9
print(b1.v, b2.v)
```
Select one:
a. `3 3`
b. `9 9`
c. `3 9`
d. `9 3`

Question 16
Question text
When is it beneficial to choose a protocol-oriented design over a class-based inheritance hierarchy?
Select one:
a. When you want to share mutable storage across screens.
b. When you need to define reusable behaviors across multiple unrelated types (including value types like structs and enums) without creating rigid class subclass coupling.
c. When you need to implement recursive structures.
d. When compiler performance is not important.

---

### Section D - Design & UX

Question 17
Question text
Why should loading states (e.g., activity indicators, skeleton screens) be explicit in mobile user interfaces?
Select one:
a. They speed up server API responses.
b. They inform the user that their request is being processed, reducing uncertainty and preventing repeated taps or screen exits.
c. They make the app compliant with dark mode requirements.
d. They force users to read advertisements.

Question 18
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Make profile screen better"?
Select one:
a. "Improve profile visual design."
b. "Increase profile completion rate from 54% to 70% by simplifying the editing flow and adding progress completion cues."
c. "The profile screen should load in less than 2 seconds."
d. "Add more input fields to the profile screen."

---

### Section E - Motivation & Soft Skills

Question 19
Question text
Which weekly strategy is most effective for practicing coding consistency and ensuring continuous skill progression?
Select one:
a. Study intensely for 10 hours once every two weeks when convenient.
b. Establish a consistent daily routine, set measurable targets, write code regularly, and maintain a feedback loop (e.g., peer reviews).
c. Rely solely on classroom tasks without personal projects.
d. Memorize code lines from textbooks.

Question 20
Question text
If selected for a cross-functional cohort at the Academy, how do you handle collaborative discussions?
Select one:
a. Enforce my own technical choices as the only way forward.
b. Listen actively to all team members, value non-technical feedback (design and business perspectives), and align choices with user-tested solutions.
c. Let others make all the decisions and focus only on coding.
d. Criticize designs that are difficult to program.
