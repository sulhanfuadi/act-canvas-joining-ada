Developer Academy - Exam Preparation 2026-2027
Home
My courses
 Exam_prep_26-27
 SECTION 5 - Practice Set 6 - ANSWER KEY
 Self-assessment Quiz for Practice Set 6 - Answer Key
Started on	Monday, 15 June 2026, 7:00 PM
State	Finished
Completed on	Monday, 15 June 2026, 8:30 PM
Time taken	1 hour 30 mins
Grade	20 out of 20 (100%)
Feedback	
Well done! This is the answer key and feedback for Practice Set 6.

---

### Section A - Logic & Reasoning

Question 1
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Number pattern: `9, 13, 19, 27, ?`
Select one:
a. 35
b. 36
c. 37 Correct! The differences between consecutive terms are consecutive even numbers starting from +4: +4, +6, +8. The next difference is +10, yielding 27 + 10 = 37.
d. 39
Feedback
The correct answer is: 37

Question 2
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
A train covers `210 km` in `3.5 hours`. What is its average speed?
Select one:
a. 50 km/h
b. 55 km/h
c. 60 km/h Correct! Speed equals distance / time: 210 km / 3.5 hours = 60 km/h.
d. 65 km/h
Feedback
The correct answer is: 60 km/h

Question 3
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Consider these statements:
- All testers are detail-oriented.
- Some detail-oriented people are designers.
- Therefore, some testers are designers.

Is the conclusion logically valid?
Select one:
a. Yes, because testers are detail-oriented, and some detail-oriented people are designers.
b. No, because the group of detail-oriented people who are designers does not necessarily overlap with the subset who are testers. Correct! Testers and designers might be disjoint subgroups within the broader class of detail-oriented people.
c. Yes, because all designers are testers.
d. No, because testers can never be designers.
Feedback
The correct answer is: No, because the group of detail-oriented people who are designers does not necessarily overlap with the subset who are testers.

---

### Section B - Programming / Swift Basics

Question 4
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let numbers = [1, 2, 3, 4]
print(numbers.map { $0 * $0 })
```
Select one:
a. `[1, 2, 3, 4]`
b. `[1, 4, 9, 16]` Correct! The `map` function transforms each element by squaring it.
c. `[2, 4, 6, 8]`
d. `[0, 1, 4, 9]`
Feedback
The correct answer is: `[1, 4, 9, 16]`

Question 5
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let nums = [10, 15, 20, 25]
let result = nums.filter { $0 % 10 == 0 }.map { $0 / 5 }
print(result)
```
Select one:
a. `[2, 4]` Correct! Filtering elements divisible by 10 yields `[10, 20]`. Mapping them to divide by 5 yields `[2, 4]`.
b. `[2, 3, 4, 5]`
c. `[2, 3]`
d. `[4, 8]`
Feedback
The correct answer is: `[2, 4]`

Question 6
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This correctly trims whitespace and newlines from all elements first, and then filters out any empty strings.
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
Feedback
The correct answer is:
```swift
func nonEmptyTrimmed(_ values: [String]) -> [String] {
    return values
        .map { $0.trimmingCharacters(in: .whitespacesAndNewlines) }
        .filter { !$0.isEmpty }
}
```

Question 7
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which statement best explains the purpose of the `compactMap` higher-order function in Swift?
Select one:
a. It aggregates numbers and returns a single summary value.
b. It transforms each element of a collection, discarding any resulting `nil` values, and returns a flat array of non-optional elements. Correct! This defines the core purpose of `compactMap`.
c. It sorts the array in descending order while removing duplicates.
d. It executes a block of code asynchronously on a background thread.
Feedback
The correct answer is: It transforms each element of a collection, discarding any resulting `nil` values, and returns a flat array of non-optional elements.

Question 8
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This safely unwraps the optional string and then returns the result of the `Int` initializer (which is itself an optional `Int`).
b. `return Int(text!)`
c. `return text as? Int`
d. `if text != nil { return Int(text) } else { return 0 }`
Feedback
The correct answer is:
```swift
    guard let text else { return nil }
    return Int(text)
```

Question 9
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which snippet safely refactors the following unsafe print statement?
```swift
let name: String? = nil
print(name!.count)
```
Select one:
a. `print(name?.count ?? 0)` Correct! This uses optional chaining and nil-coalescing to provide a safe fallback of 0 if `name` is nil, preventing crashes.
b. `print(name!.count ?? 0)`
c. `print(name.count)`
d. `if name != nil { print(name.count) }`
Feedback
The correct answer is: `print(name?.count ?? 0)`

Question 10
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
What is the output of the following Swift code?
```swift
let values = ["1", "2", "x", "4"]
let total = values.compactMap(Int.init).reduce(0, +)
print(total)
```
Select one:
a. `7` Correct! `compactMap` parses `"1"`, `"2"`, and `"4"` to Ints `[1, 2, 4]`, discarding `"x"`. The sum is 1 + 2 + 4 = 7.
b. `6`
c. `0`
d. `x`
Feedback
The correct answer is: `7`

Question 11
Correct
Mark 1 out of 1
Not flaggedFlag question
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
``` Correct! This correctly filters for odd numbers (`$0 % 2 != 0`), sorts them ascending (default `sorted()`), maps them to String, and joins them using a comma separator.
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
Feedback
The correct answer is:
```swift
func oddSortedCSV(_ values: [Int]) -> String {
    return values
        .filter { $0 % 2 != 0 }
        .sorted()
        .map(String.init)
        .joined(separator: ",")
}
```

Question 12
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Why is early return with the `guard` statement often preferred over nested `if` statements in Swift?
Select one:
a. It runs faster because it bypasses safety checks.
b. It keeps the "happy path" (success flow) flat, reduces deep indentation nesting, and makes exit conditions explicit. Correct! This improves overall code readability and maintainability.
c. It forces class inheritance to be resolved at compile time.
d. It automatically releases memory of unused parameters.
Feedback
The correct answer is: It keeps the "happy path" (success flow) flat, reduces deep indentation nesting, and makes exit conditions explicit.

Question 13
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which implementation correctly completes the generic function `firstTwo(_:)` to return an array containing at most the first two items of any type?
```swift
func firstTwo<T>(_ items: [T]) -> [T] {
    // missing code
}
```
Select one:
a. `return Array(items.prefix(2))` Correct! Using `prefix(2)` yields a slice of up to the first 2 items of type `T`, and `Array()` converts it back to `[T]`.
b. `return [items[0], items[1]]`
c. `return items.filter { _ in true }`
d. `return Array(items.suffix(2))`
Feedback
The correct answer is: `return Array(items.prefix(2))`

---

### Section C - OOP & Swift Concepts

Question 14
Correct
Mark 1 out of 1
Not flaggedFlag question
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
b. `9 9` Correct! `Node` is a class (reference type). Both `n1` and `n2` reference the same memory instance, so modifications update both.
c. `3 9`
d. `9 3`
Feedback
The correct answer is: `9 9`

Question 15
Correct
Mark 1 out of 1
Not flaggedFlag question
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
c. `3 9` Correct! `Box` is a struct (value type), copying data on assignment. Modifying `b2.v` leaves `b1.v` unchanged.
d. `9 3`
Feedback
The correct answer is: `3 9`

Question 16
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
When is it beneficial to choose a protocol-oriented design over a class-based inheritance hierarchy?
Select one:
a. When you want to share mutable storage across screens.
b. When you need to define reusable behaviors across multiple unrelated types (including value types like structs and enums) without creating rigid class subclass coupling. Correct! Protocols provide flexible, horizontal design decoupling.
c. When you need to implement recursive structures.
d. When compiler performance is not important.
Feedback
The correct answer is: When you need to define reusable behaviors across multiple unrelated types (including value types like structs and enums) without creating rigid class subclass coupling.

---

### Section D - Design & UX

Question 17
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Why should loading states (e.g., activity indicators, skeleton screens) be explicit in mobile user interfaces?
Select one:
a. They speed up server API responses.
b. They inform the user that their request is being processed, reducing uncertainty and preventing repeated taps or screen exits. Correct! Visual indicators of loading reduce friction and manage user expectations.
c. They make the app compliant with dark mode requirements.
d. They force users to read advertisements.
Feedback
The correct answer is: They inform the user that their request is being processed, reducing uncertainty and preventing repeated taps or screen exits.

Question 18
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which of the following represents the most effective rewrite of the weak requirement: "Make profile screen better"?
Select one:
a. "Improve profile visual design."
b. "Increase profile completion rate from 54% to 70% by simplifying the editing flow and adding progress completion cues." Correct! This is a specific, measurable target tied to clear user actions.
c. "The profile screen should load in less than 2 seconds."
d. "Add more input fields to the profile screen."
Feedback
The correct answer is: "Increase profile completion rate from 54% to 70% by simplifying the editing flow and adding progress completion cues."

---

### Section E - Motivation & Soft Skills

Question 19
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
Which weekly strategy is most effective for practicing coding consistency and ensuring continuous skill progression?
Select one:
a. Study intensely for 10 hours once every two weeks when convenient.
b. Establish a consistent daily routine, set measurable targets, write code regularly, and maintain a feedback loop (e.g., peer reviews). Correct! Consistency is built through regular, structured habits and iterative loops.
c. Rely solely on classroom tasks without personal projects.
d. Memorize code lines from textbooks.
Feedback
The correct answer is: Establish a consistent daily routine, set measurable targets, write code regularly, and maintain a feedback loop (e.g., peer reviews).

Question 20
Correct
Mark 1 out of 1
Not flaggedFlag question
Question text
If selected for a cross-functional cohort at the Academy, how do you handle collaborative discussions?
Select one:
a. Enforce my own technical choices as the only way forward.
b. Listen actively to all team members, value non-technical feedback (design and business perspectives), and align choices with user-tested solutions. Correct! Collaborative team dynamics require empathy, active listening, and user-centered alignment.
c. Let others make all the decisions and focus only on coding.
d. Criticize designs that are difficult to program.
Feedback
The correct answer is: Listen actively to all team members, value non-technical feedback (design and business perspectives), and align choices with user-tested solutions.
