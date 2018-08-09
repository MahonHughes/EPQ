# Coding Diary

## 8/8/18

I began by creating a new playground. This is a built in feature when coding apps for iPhone. A playground is where you can test pieces of code before you include them in the final product/app.
In the playground, I added three variables, The name of the person who owes the money, the amount that that person owes and a due date for the debt. 
```swift
var name = "Mark"
var debtOwed = 20.0
var dueDate = "27/5/2018"
```
Next, I added a structure. A structure is like a package you can put many variables into. I have learned about structures in my computer science A-Level course but for that course, we use C#, a different programming language. I found out how to use structures in *Swift* at swift.org. [https://docs.swift.org/swift-book/LanguageGuide/ClassesAndStructures.html] I found this website very useful. Inside the structure, I added each of the variables I created.
```swift
struct Debt {
    var name:String
    var debtOwed:Double
    var dueDate:String
}
```

