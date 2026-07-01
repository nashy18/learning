# JavaScript 30-Day Practice Plan
### 180 Questions | Beginner → Intermediate | 6 Questions per Day

Each day builds on the previous one. Try solving before checking against expected output. Difficulty increases gradually within each day (Q1 easiest → Q6 hardest).

---

## Day 1 — Variables & Data Types

**Q1.** Declare a variable `name` and assign it your name, then log it.
```
Input: name = "Alex"
Expected Output: "Alex"
```

**Q2.** Write `getType(value)` that returns the type of a value using `typeof`.
```
Input: getType(42)
Expected Output: "number"

Input: getType("hi")
Expected Output: "string"
```

**Q3.** Write `swapValues(a, b)` that returns an array with values swapped.
```
Input: swapValues(1, 2)
Expected Output: [2, 1]
```

**Q4.** Write `isNull(value)` that returns true if value is strictly `null`.
```
Input: isNull(null)
Expected Output: true

Input: isNull(undefined)
Expected Output: false
```

**Q5.** Write `toBoolean(value)` that converts a value to boolean using `Boolean()`.
```
Input: toBoolean(0)
Expected Output: false

Input: toBoolean("text")
Expected Output: true
```

**Q6.** Write `sumOfThree(a, b, c)` using `let` variables to store intermediate sums.
```
Input: sumOfThree(1, 2, 3)
Expected Output: 6
```

---

## Day 2 — Operators

**Q7.** Write `modOfTwo(a, b)` returning the remainder.
```
Input: modOfTwo(10, 3)
Expected Output: 1
```

**Q8.** Write `powerOf(base, exp)` using the `**` operator.
```
Input: powerOf(2, 5)
Expected Output: 32
```

**Q9.** Write `compareValues(a, b)` using strict equality `===`, returning true/false.
```
Input: compareValues(5, "5")
Expected Output: false
```

**Q10.** Write `logicalCheck(a, b)` that returns true if both `a` and `b` are truthy.
```
Input: logicalCheck(1, "text")
Expected Output: true

Input: logicalCheck(0, "text")
Expected Output: false
```

**Q11.** Write `ternaryCheck(age)` returning "Adult" if age >= 18 else "Minor" using a ternary operator.
```
Input: ternaryCheck(20)
Expected Output: "Adult"
```

**Q12.** Write `incrementValue(num)` using the `++` operator, returning the incremented value.
```
Input: incrementValue(9)
Expected Output: 10
```

---

## Day 3 — Conditionals

**Q13.** Write `checkSign(num)` returning "Positive", "Negative", or "Zero".
```
Input: checkSign(-5)
Expected Output: "Negative"
```

**Q14.** Write `gradeScore(score)` returning grade based on: 90+ "A", 80-89 "B", 70-79 "C", below 70 "F".
```
Input: gradeScore(85)
Expected Output: "B"
```

**Q15.** Write `isLeapYear(year)` using conditionals.
```
Input: isLeapYear(2024)
Expected Output: true

Input: isLeapYear(2023)
Expected Output: false
```

**Q16.** Write `switchDay(dayNum)` using a `switch` statement returning day name (1-7).
```
Input: switchDay(3)
Expected Output: "Wednesday"
```

**Q17.** Write `checkTriangleType(a, b, c)` returning "Equilateral", "Isosceles", or "Scalene".
```
Input: checkTriangleType(3, 3, 3)
Expected Output: "Equilateral"

Input: checkTriangleType(3, 3, 5)
Expected Output: "Isosceles"
```

**Q18.** Write `validateAge(age)` returning "Invalid" if negative or above 120, else "Valid".
```
Input: validateAge(150)
Expected Output: "Invalid"
```

---

## Day 4 — Loops

**Q19.** Write `printNumbers(n)` returning an array of numbers from 1 to n using a `for` loop.
```
Input: printNumbers(5)
Expected Output: [1, 2, 3, 4, 5]
```

**Q20.** Write `sumUpToN(n)` using a `while` loop.
```
Input: sumUpToN(5)
Expected Output: 15
```

**Q21.** Write `countDown(n)` returning an array counting down from n to 1.
```
Input: countDown(5)
Expected Output: [5, 4, 3, 2, 1]
```

**Q22.** Write `multiplicationTable(num)` returning an array of num × 1 through num × 5.
```
Input: multiplicationTable(3)
Expected Output: [3, 6, 9, 12, 15]
```

**Q23.** Write `sumOfEvens(n)` summing even numbers from 1 to n using `continue`.
```
Input: sumOfEvens(10)
Expected Output: 30
```

**Q24.** Write `nestedLoopPattern(n)` returning array of arrays representing a triangle count pattern.
```
Input: nestedLoopPattern(3)
Expected Output: [[1], [1, 2], [1, 2, 3]]
```

---

## Day 5 — Functions Basics

**Q25.** Write `greet(name)` returning `"Hello, <name>!"`.
```
Input: greet("Sam")
Expected Output: "Hello, Sam!"
```

**Q26.** Write `defaultGreet(name = "Guest")` using default parameters.
```
Input: defaultGreet()
Expected Output: "Hello, Guest!"
```

**Q27.** Write an arrow function `square = (n) => n * n`.
```
Input: square(6)
Expected Output: 36
```

**Q28.** Write `sumAll(...nums)` using rest parameters.
```
Input: sumAll(1, 2, 3, 4)
Expected Output: 10
```

**Q29.** Write `applyOperation(a, b, operation)` where `operation` is a callback function.
```
Input: applyOperation(4, 5, (x, y) => x + y)
Expected Output: 9
```

**Q30.** Write an IIFE (Immediately Invoked Function Expression) that returns "IIFE executed".
```
Input: (function() { return "IIFE executed"; })()
Expected Output: "IIFE executed"
```

---

## Day 6 — Strings Basics

**Q31.** Write `toUpper(str)` using `.toUpperCase()`.
```
Input: toUpper("hello")
Expected Output: "HELLO"
```

**Q32.** Write `trimSpaces(str)` using `.trim()`.
```
Input: trimSpaces("  hi there  ")
Expected Output: "hi there"
```

**Q33.** Write `concatStrings(a, b)` using template literals.
```
Input: concatStrings("Java", "Script")
Expected Output: "JavaScript"
```

**Q34.** Write `getSubstring(str, start, end)` using `.slice()`.
```
Input: getSubstring("hello world", 0, 5)
Expected Output: "hello"
```

**Q35.** Write `replaceWord(str, oldWord, newWord)` using `.replace()`.
```
Input: replaceWord("I like cats", "cats", "dogs")
Expected Output: "I like dogs"
```

**Q36.** Write `splitToArray(str)` splitting a sentence into words.
```
Input: splitToArray("the quick brown fox")
Expected Output: ["the", "quick", "brown", "fox"]
```

---

## Day 7 — String Methods Advanced

**Q37.** Write `capitalizeFirst(str)` capitalizing only the first letter.
```
Input: capitalizeFirst("javascript")
Expected Output: "Javascript"
```

**Q38.** Write `capitalizeEachWord(str)` (title case).
```
Input: capitalizeEachWord("the quick fox")
Expected Output: "The Quick Fox"
```

**Q39.** Write `countWords(str)` returning the number of words.
```
Input: countWords("this is a test sentence")
Expected Output: 5
```

**Q40.** Write `isAnagram(str1, str2)`.
```
Input: isAnagram("listen", "silent")
Expected Output: true

Input: isAnagram("hello", "world")
Expected Output: false
```

**Q41.** Write `repeatString(str, times)` using `.repeat()`.
```
Input: repeatString("ab", 3)
Expected Output: "ababab"
```

**Q42.** Write `padNumber(num, length)` using `.padStart()`, returning a zero-padded string.
```
Input: padNumber(7, 3)
Expected Output: "007"
```

---

## Day 8 — Arrays Basics

**Q43.** Write `createArray()` returning `[10, 20, 30]` using array literal syntax.
```
Input: createArray()
Expected Output: [10, 20, 30]
```

**Q44.** Write `getFirstLast(arr)` returning an object with `first` and `last` elements.
```
Input: getFirstLast([1, 2, 3, 4])
Expected Output: { first: 1, last: 4 }
```

**Q45.** Write `addToEnd(arr, item)` using `.push()`.
```
Input: addToEnd([1, 2, 3], 4)
Expected Output: [1, 2, 3, 4]
```

**Q46.** Write `removeLast(arr)` using `.pop()`, returning the modified array.
```
Input: removeLast([1, 2, 3, 4])
Expected Output: [1, 2, 3]
```

**Q47.** Write `checkIncludes(arr, value)` using `.includes()`.
```
Input: checkIncludes([1, 2, 3], 2)
Expected Output: true
```

**Q48.** Write `findIndexOf(arr, value)` using `.indexOf()`.
```
Input: findIndexOf(["a", "b", "c"], "b")
Expected Output: 1
```

---

## Day 9 — Array Methods (map / filter / reduce)

**Q49.** Write `doubleArray(arr)` using `.map()`.
```
Input: doubleArray([1, 2, 3])
Expected Output: [2, 4, 6]
```

**Q50.** Write `filterEvens(arr)` using `.filter()`.
```
Input: filterEvens([1, 2, 3, 4, 5, 6])
Expected Output: [2, 4, 6]
```

**Q51.** Write `sumWithReduce(arr)` using `.reduce()`.
```
Input: sumWithReduce([1, 2, 3, 4])
Expected Output: 10
```

**Q52.** Write `getSquares(arr)` returning squares of only positive numbers.
```
Input: getSquares([-2, 3, -4, 5])
Expected Output: [9, 25]
```

**Q53.** Write `findMaxWithReduce(arr)` using `.reduce()` to find the maximum.
```
Input: findMaxWithReduce([3, 7, 2, 9, 4])
Expected Output: 9
```

**Q54.** Write `countOccurrences(arr)` using `.reduce()` returning an object with counts.
```
Input: countOccurrences(["a", "b", "a", "c", "b", "a"])
Expected Output: { a: 3, b: 2, c: 1 }
```

---

## Day 10 — More Array Methods

**Q55.** Write `sortNumbers(arr)` sorting in ascending order using `.sort()`.
```
Input: sortNumbers([5, 2, 9, 1, 7])
Expected Output: [1, 2, 5, 7, 9]
```

**Q56.** Write `sortDescending(arr)`.
```
Input: sortDescending([5, 2, 9, 1, 7])
Expected Output: [9, 7, 5, 2, 1]
```

**Q57.** Write `everyPositive(arr)` using `.every()`.
```
Input: everyPositive([1, 2, 3])
Expected Output: true

Input: everyPositive([1, -2, 3])
Expected Output: false
```

**Q58.** Write `someNegative(arr)` using `.some()`.
```
Input: someNegative([1, 2, -3])
Expected Output: true
```

**Q59.** Write `findFirstMatch(arr, condition)` using `.find()`.
```
Input: findFirstMatch([1, 4, 7, 10], n => n > 5)
Expected Output: 7
```

**Q60.** Write `chainedArrayOps(arr)` that filters evens, doubles them, and sums the result — using method chaining.
```
Input: chainedArrayOps([1, 2, 3, 4, 5, 6])
Expected Output: 24
```

---

## Day 11 — Objects Basics

**Q61.** Create an object `person` with `name`, `age`, `city` properties and log `person.name`.
```
Input: person = { name: "Sam", age: 25, city: "Delhi" }
Expected Output: "Sam"
```

**Q62.** Write `getKeys(obj)` using `Object.keys()`.
```
Input: getKeys({ a: 1, b: 2, c: 3 })
Expected Output: ["a", "b", "c"]
```

**Q63.** Write `getValues(obj)` using `Object.values()`.
```
Input: getValues({ a: 1, b: 2, c: 3 })
Expected Output: [1, 2, 3]
```

**Q64.** Write `addProperty(obj, key, value)` returning the updated object.
```
Input: addProperty({ name: "Sam" }, "age", 25)
Expected Output: { name: "Sam", age: 25 }
```

**Q65.** Write `deleteProperty(obj, key)` using `delete`, returning the updated object.
```
Input: deleteProperty({ name: "Sam", age: 25 }, "age")
Expected Output: { name: "Sam" }
```

**Q66.** Write `hasProperty(obj, key)` using `.hasOwnProperty()`.
```
Input: hasProperty({ name: "Sam" }, "name")
Expected Output: true
```

---

## Day 12 — Object Methods & Advanced

**Q67.** Write `mergeObjects(obj1, obj2)` using `Object.assign()`.
```
Input: mergeObjects({ a: 1 }, { b: 2 })
Expected Output: { a: 1, b: 2 }
```

**Q68.** Write `objectToEntries(obj)` using `Object.entries()`.
```
Input: objectToEntries({ a: 1, b: 2 })
Expected Output: [["a", 1], ["b", 2]]
```

**Q69.** Write `entriesToObject(entries)` using `Object.fromEntries()`.
```
Input: entriesToObject([["a", 1], ["b", 2]])
Expected Output: { a: 1, b: 2 }
```

**Q70.** Write `freezeObject(obj)` using `Object.freeze()` and return whether it's frozen using `Object.isFrozen()`.
```
Input: freezeObject({ a: 1 })
Expected Output: true
```

**Q71.** Write `nestedAccess(obj)` safely accessing `obj.address.city` using optional chaining `?.`.
```
Input: nestedAccess({ name: "Sam" })
Expected Output: undefined

Input: nestedAccess({ name: "Sam", address: { city: "Pune" } })
Expected Output: "Pune"
```

**Q72.** Write `objectValuesSum(obj)` summing all numeric values of an object.
```
Input: objectValuesSum({ a: 10, b: 20, c: 30 })
Expected Output: 60
```

---

## Day 13 — Recursion

**Q73.** Write `sumRecursive(n)` computing sum from 1 to n using recursion.
```
Input: sumRecursive(5)
Expected Output: 15
```

**Q74.** Write `fibonacci(n)` returning the nth Fibonacci number (0-indexed) using recursion.
```
Input: fibonacci(6)
Expected Output: 8
```

**Q75.** Write `reverseStringRecursive(str)` using recursion.
```
Input: reverseStringRecursive("abc")
Expected Output: "cba"
```

**Q76.** Write `sumArrayRecursive(arr)` summing array elements recursively.
```
Input: sumArrayRecursive([1, 2, 3, 4])
Expected Output: 10
```

**Q77.** Write `power(base, exp)` computing exponentiation recursively.
```
Input: power(3, 4)
Expected Output: 81
```

**Q78.** Write `countDownRecursive(n)` returning array of a recursive countdown to 0.
```
Input: countDownRecursive(3)
Expected Output: [3, 2, 1, 0]
```

---

## Day 14 — Higher Order Functions

**Q79.** Write `createMultiplier(factor)` returning a function that multiplies input by factor.
```
Input: const triple = createMultiplier(3); triple(5)
Expected Output: 15
```

**Q80.** Write `applyTwice(fn, value)` applying a function twice to a value.
```
Input: applyTwice(x => x + 3, 5)
Expected Output: 11
```

**Q81.** Write `composeFunctions(f, g)` returning a new function `x => f(g(x))`.
```
Input: composeFunctions(x => x + 1, x => x * 2)(5)
Expected Output: 11
```

**Q82.** Write `customMap(arr, fn)` re-implementing `.map()` manually.
```
Input: customMap([1, 2, 3], x => x * 2)
Expected Output: [2, 4, 6]
```

**Q83.** Write `customFilter(arr, fn)` re-implementing `.filter()` manually.
```
Input: customFilter([1, 2, 3, 4], x => x % 2 === 0)
Expected Output: [2, 4]
```

**Q84.** Write `debounceCallCount(fn, arr)` that applies `fn` to each array element and returns results array.
```
Input: debounceCallCount(x => x * x, [1, 2, 3])
Expected Output: [1, 4, 9]
```

---

## Day 15 — Closures

**Q85.** Write `counter()` returning a function that increments and returns a count each call.
```
Input: const c = counter(); c(); c(); c()
Expected Output: 3
```

**Q86.** Write `createAccount(balance)` returning `deposit` and `withdraw` functions using closures.
```
Input: const acc = createAccount(100); acc.deposit(50); acc.withdraw(30); acc.getBalance()
Expected Output: 120
```

**Q87.** Write `once(fn)` returning a function that only allows `fn` to run once.
```
Input: const init = once(() => "initialized"); init(); init()
Expected Output: "initialized" (second call returns same cached result, fn body doesn't re-run)
```

**Q88.** Write `makeAdder(x)` returning a function that adds `x` to its argument.
```
Input: const add5 = makeAdder(5); add5(10)
Expected Output: 15
```

**Q89.** Write `privateVariable()` demonstrating data privacy — return object with `getValue` and `setValue` methods, initial value 0.
```
Input: const obj = privateVariable(); obj.setValue(42); obj.getValue()
Expected Output: 42
```

**Q90.** Write `memoize(fn)` caching results of a function based on its argument.
```
Input: const memoizedSquare = memoize(x => x * x); memoizedSquare(4); memoizedSquare(4)
Expected Output: 16 (second call served from cache)
```

---

## Day 16 — Destructuring, Spread & Rest

**Q91.** Destructure `{ name, age }` from an object and return them as an array.
```
Input: extractInfo({ name: "Sam", age: 25, city: "Pune" })
Expected Output: ["Sam", 25]
```

**Q92.** Destructure array values with `[a, b]` and swap them.
```
Input: swapWithDestructure([1, 2])
Expected Output: [2, 1]
```

**Q93.** Write `cloneArray(arr)` using the spread operator.
```
Input: cloneArray([1, 2, 3])
Expected Output: [1, 2, 3] (different reference)
```

**Q94.** Write `mergeArrays(arr1, arr2)` using the spread operator.
```
Input: mergeArrays([1, 2], [3, 4])
Expected Output: [1, 2, 3, 4]
```

**Q95.** Write `firstAndRest(arr)` using rest syntax in destructuring, returning `{ first, rest }`.
```
Input: firstAndRest([1, 2, 3, 4])
Expected Output: { first: 1, rest: [2, 3, 4] }
```

**Q96.** Write `cloneObjectWithUpdate(obj, updates)` using object spread to merge changes.
```
Input: cloneObjectWithUpdate({ name: "Sam", age: 25 }, { age: 26 })
Expected Output: { name: "Sam", age: 26 }
```

---

## Day 17 — Template Literals & Default Params

**Q97.** Write `formatPrice(item, price)` using template literals to return `"<item>: $<price>"`.
```
Input: formatPrice("Book", 15)
Expected Output: "Book: $15"
```

**Q98.** Write `multilineMessage(name)` returning a multi-line template string greeting.
```
Input: multilineMessage("Sam")
Expected Output: "Hello Sam,\nWelcome!"
```

**Q99.** Write `calcWithDefaults(a, b = 10)` returning `a + b`.
```
Input: calcWithDefaults(5)
Expected Output: 15
```

**Q100.** Write `describeUser(name, role = "user")` using template literals and default param.
```
Input: describeUser("Sam")
Expected Output: "Sam is a user"

Input: describeUser("Alex", "admin")
Expected Output: "Alex is a admin"
```

**Q101.** Write `expressionInTemplate(a, b)` returning `"Sum: <result>"` using an expression inside a template literal.
```
Input: expressionInTemplate(4, 5)
Expected Output: "Sum: 9"
```

**Q102.** Write `tagPrices(prices)` returning an array of formatted strings using `.map()` and template literals.
```
Input: tagPrices([10, 20, 30])
Expected Output: ["$10", "$20", "$30"]
```

---

## Day 18 — Sets & Maps

**Q103.** Write `uniqueValues(arr)` using a `Set` to remove duplicates.
```
Input: uniqueValues([1, 2, 2, 3, 3, 4])
Expected Output: [1, 2, 3, 4]
```

**Q104.** Write `setHasValue(arr, value)` using `Set.has()`.
```
Input: setHasValue([1, 2, 3], 2)
Expected Output: true
```

**Q105.** Write `setSize(arr)` returning the size of the Set created from the array.
```
Input: setSize([1, 1, 2, 2, 3])
Expected Output: 3
```

**Q106.** Write `createMap()` returning a `Map` with keys `"a"`, `"b"` mapped to `1`, `2`.
```
Input: createMap()
Expected Output: Map(2) { "a" => 1, "b" => 2 }
```

**Q107.** Write `mapToObject(map)` converting a `Map` to a plain object.
```
Input: mapToObject(new Map([["a", 1], ["b", 2]]))
Expected Output: { a: 1, b: 2 }
```

**Q108.** Write `countCharsWithMap(str)` using a `Map` to count character frequency.
```
Input: countCharsWithMap("aab")
Expected Output: Map(2) { "a" => 2, "b" => 1 }
```

---

## Day 19 — Classes Basics

**Q109.** Write a `Person` class with `name` and `age` properties set in the constructor, and a `greet()` method.
```
Input: new Person("Sam", 25).greet()
Expected Output: "Hi, I'm Sam and I'm 25 years old."
```

**Q110.** Add a method `Person.isAdult()` returning true if age >= 18.
```
Input: new Person("Sam", 16).isAdult()
Expected Output: false
```

**Q111.** Write a `Rectangle` class with `width`, `height`, and a method `area()`.
```
Input: new Rectangle(4, 5).area()
Expected Output: 20
```

**Q112.** Add a static method `Rectangle.compare(r1, r2)` returning the rectangle with larger area.
```
Input: Rectangle.compare(new Rectangle(2,3), new Rectangle(4,4))
Expected Output: Rectangle { width: 4, height: 4 }
```

**Q113.** Write a `Counter` class with `count = 0`, and methods `increment()` and `getCount()`.
```
Input: const c = new Counter(); c.increment(); c.increment(); c.getCount()
Expected Output: 2
```

**Q114.** Add a getter `Counter.doubled` that returns `count * 2`.
```
Input: const c = new Counter(); c.increment(); c.increment(); c.doubled
Expected Output: 4
```

---

## Day 20 — Classes Advanced & Inheritance

**Q115.** Write an `Animal` class with `name` and `speak()` returning `"<name> makes a sound."`
```
Input: new Animal("Generic").speak()
Expected Output: "Generic makes a sound."
```

**Q116.** Write a `Dog` class extending `Animal`, overriding `speak()` to return `"<name> barks."`
```
Input: new Dog("Rex").speak()
Expected Output: "Rex barks."
```

**Q117.** Use `super()` in `Dog`'s constructor to call `Animal`'s constructor, adding a `breed` property.
```
Input: new Dog("Rex", "Labrador").breed
Expected Output: "Labrador"
```

**Q118.** Write a `Shape` base class with method `area()` returning 0, and `Circle` class extending it with its own `area()`.
```
Input: new Circle(3).area()
Expected Output: 28.27 (approx, radius=3, π×r²)
```

**Q119.** Write a class `BankAccount` using a private field `#balance` with `deposit()` and `getBalance()` methods.
```
Input: const acc = new BankAccount(100); acc.deposit(50); acc.getBalance()
Expected Output: 150
```

**Q120.** Write `instanceCheck(obj)` returning true if `obj instanceof Dog`.
```
Input: instanceCheck(new Dog("Rex"))
Expected Output: true
```

---

## Day 21 — Error Handling

**Q121.** Write `safeDivide(a, b)` that throws an error if `b === 0`, caught and returns `"Error: Division by zero"`.
```
Input: safeDivide(10, 0)
Expected Output: "Error: Division by zero"

Input: safeDivide(10, 2)
Expected Output: 5
```

**Q122.** Write `parseJSONSafely(str)` using try/catch, returning `null` on invalid JSON.
```
Input: parseJSONSafely('{"a":1}')
Expected Output: { a: 1 }

Input: parseJSONSafely('invalid')
Expected Output: null
```

**Q123.** Write `validateAge(age)` throwing a custom error `"Invalid age"` if negative, caught and logged.
```
Input: validateAge(-5)
Expected Output: "Caught error: Invalid age"
```

**Q124.** Write `finallyExample(value)` using try/catch/finally, always logging `"Cleanup done"` regardless of outcome.
```
Input: finallyExample(5)
Expected Output: "Cleanup done" (logged regardless of try/catch path)
```

**Q125.** Write a custom error class `NegativeNumberError extends Error` and use it in `checkPositive(num)`.
```
Input: checkPositive(-3)
Expected Output: "NegativeNumberError: Number cannot be negative"
```

**Q126.** Write `retryOperation(fn, attempts)` that retries a function up to `attempts` times if it throws.
```
Input: let tries = 0; retryOperation(() => { tries++; if (tries < 3) throw "fail"; return "success"; }, 5)
Expected Output: "success"
```

---

## Day 22 — JSON

**Q127.** Write `objectToJSON(obj)` using `JSON.stringify()`.
```
Input: objectToJSON({ name: "Sam", age: 25 })
Expected Output: '{"name":"Sam","age":25}'
```

**Q128.** Write `jsonToObject(jsonStr)` using `JSON.parse()`.
```
Input: jsonToObject('{"a":1,"b":2}')
Expected Output: { a: 1, b: 2 }
```

**Q129.** Write `prettyPrintJSON(obj)` using `JSON.stringify(obj, null, 2)`.
```
Input: prettyPrintJSON({ a: 1 })
Expected Output: '{\n  "a": 1\n}'
```

**Q130.** Write `deepCloneWithJSON(obj)` using `JSON.parse(JSON.stringify(obj))`.
```
Input: deepCloneWithJSON({ a: { b: 1 } })
Expected Output: { a: { b: 1 } } (different reference)
```

**Q131.** Write `filterJSONArray(jsonStr, key, value)` parsing a JSON array string and filtering by key/value.
```
Input: filterJSONArray('[{"type":"fruit"},{"type":"veg"}]', "type", "fruit")
Expected Output: [{ type: "fruit" }]
```

**Q132.** Write `jsonArrayToCSV(jsonArr)` converting an array of flat objects to a CSV string.
```
Input: jsonArrayToCSV([{ name: "Sam", age: 25 }])
Expected Output: "name,age\nSam,25"
```

---

## Day 23 — Date & Time

**Q133.** Write `getCurrentYear()` using `new Date().getFullYear()`.
```
Input: getCurrentYear()
Expected Output: 2026 (or current year at runtime)
```

**Q134.** Write `createDate(year, month, day)` returning a formatted date string `"YYYY-MM-DD"`.
```
Input: createDate(2026, 6, 15)
Expected Output: "2026-06-15"
```

**Q135.** Write `daysBetween(date1, date2)` returning the number of days between two dates.
```
Input: daysBetween("2026-01-01", "2026-01-10")
Expected Output: 9
```

**Q136.** Write `addDays(date, days)` returning a new date string after adding days.
```
Input: addDays("2026-01-01", 10)
Expected Output: "2026-01-11"
```

**Q137.** Write `getDayName(date)` returning the weekday name.
```
Input: getDayName("2026-07-01")
Expected Output: "Wednesday"
```

**Q138.** Write `isFutureDate(date)` returning true if the date is after today.
```
Input: isFutureDate("2030-01-01")
Expected Output: true
```

---

## Day 24 — Regex Basics

**Q139.** Write `testEmail(str)` using regex `.test()` to check for a basic email pattern.
```
Input: testEmail("test@example.com")
Expected Output: true

Input: testEmail("not-an-email")
Expected Output: false
```

**Q140.** Write `extractNumbers(str)` using `.match()` to pull all numbers out of a string.
```
Input: extractNumbers("I have 2 cats and 3 dogs")
Expected Output: ["2", "3"]
```

**Q141.** Write `replaceDigits(str)` replacing all digits with `"#"` using regex.
```
Input: replaceDigits("abc123def456")
Expected Output: "abc###def###"
```

**Q142.** Write `isAlphaOnly(str)` checking if a string contains only letters.
```
Input: isAlphaOnly("Hello")
Expected Output: true

Input: isAlphaOnly("Hello123")
Expected Output: false
```

**Q143.** Write `removeSpecialChars(str)` stripping all non-alphanumeric characters.
```
Input: removeSpecialChars("Hi! How-are_you?")
Expected Output: "HiHowareyou"
```

**Q144.** Write `validatePhoneNumber(str)` checking format `XXX-XXX-XXXX`.
```
Input: validatePhoneNumber("123-456-7890")
Expected Output: true

Input: validatePhoneNumber("1234567890")
Expected Output: false
```

---

## Day 25 — Arrays of Objects

**Q145.** Given an array of student objects, write `getNames(students)` returning just the names using `.map()`.
```
Input: getNames([{ name: "Sam", score: 90 }, { name: "Alex", score: 75 }])
Expected Output: ["Sam", "Alex"]
```

**Q146.** Write `getPassingStudents(students)` filtering students with score >= 60.
```
Input: getPassingStudents([{ name: "Sam", score: 90 }, { name: "Alex", score: 40 }])
Expected Output: [{ name: "Sam", score: 90 }]
```

**Q147.** Write `averageScore(students)` computing the average score using `.reduce()`.
```
Input: averageScore([{ score: 80 }, { score: 90 }, { score: 70 }])
Expected Output: 80
```

**Q148.** Write `sortByScore(students)` sorting descending by score.
```
Input: sortByScore([{ name: "A", score: 70 }, { name: "B", score: 95 }])
Expected Output: [{ name: "B", score: 95 }, { name: "A", score: 70 }]
```

**Q149.** Write `findStudentByName(students, name)` using `.find()`.
```
Input: findStudentByName([{ name: "Sam" }, { name: "Alex" }], "Alex")
Expected Output: { name: "Alex" }
```

**Q150.** Write `groupByGrade(students)` grouping students into "Pass"/"Fail" arrays based on score >= 60.
```
Input: groupByGrade([{ name: "Sam", score: 90 }, { name: "Alex", score: 40 }])
Expected Output: { Pass: [{ name: "Sam", score: 90 }], Fail: [{ name: "Alex", score: 40 }] }
```

---

## Day 26 — Promises Basics

**Q151.** Write `createResolvedPromise(value)` returning a Promise that resolves with `value`.
```
Input: createResolvedPromise(42).then(v => v)
Expected Output: 42
```

**Q152.** Write `createRejectedPromise(reason)` returning a Promise that rejects, caught with `.catch()`.
```
Input: createRejectedPromise("failed").catch(e => e)
Expected Output: "failed"
```

**Q153.** Write `delayedValue(value, ms)` returning a Promise resolving with `value` after `ms` milliseconds using `setTimeout`.
```
Input: delayedValue("done", 1000).then(v => v)
Expected Output: "done" (after ~1000ms)
```

**Q154.** Write `chainPromises()` chaining two `.then()` calls: first doubles a number, second adds 1.
```
Input: chainPromises(5)
Expected Output: 11
```

**Q155.** Write `allPromisesExample()` using `Promise.all()` to resolve 3 promises and return their combined array.
```
Input: allPromisesExample([Promise.resolve(1), Promise.resolve(2), Promise.resolve(3)])
Expected Output: [1, 2, 3]
```

**Q156.** Write `raceExample()` using `Promise.race()` returning the first settled promise's value.
```
Input: raceExample([delayedValue("slow", 500), delayedValue("fast", 100)])
Expected Output: "fast"
```

---

## Day 27 — Async / Await

**Q157.** Write `asyncGreet(name)` as an `async` function returning `"Hello, <name>"`.
```
Input: await asyncGreet("Sam")
Expected Output: "Hello, Sam"
```

**Q158.** Write `fetchDataSimulated()` using `async/await` with a simulated delayed value.
```
Input: await fetchDataSimulated()
Expected Output: "data loaded"
```

**Q159.** Write `asyncTryCatch(shouldFail)` using try/catch inside an async function.
```
Input: await asyncTryCatch(true)
Expected Output: "Caught: Something went wrong"

Input: await asyncTryCatch(false)
Expected Output: "Success"
```

**Q160.** Write `sequentialAwaits()` awaiting two async operations one after another and summing results.
```
Input: await sequentialAwaits()
Expected Output: 30 (e.g., 10 + 20)
```

**Q161.** Write `parallelAwaits()` using `Promise.all()` with `await` to run operations concurrently.
```
Input: await parallelAwaits()
Expected Output: [10, 20, 30]
```

**Q162.** Write `asyncMapArray(arr, asyncFn)` applying an async function to each array element and awaiting all results.
```
Input: await asyncMapArray([1, 2, 3], async x => x * 2)
Expected Output: [2, 4, 6]
```

---

## Day 28 — Algorithm Practice I

**Q163.** Write `isPrime(num)` checking if a number is prime.
```
Input: isPrime(17)
Expected Output: true

Input: isPrime(15)
Expected Output: false
```

**Q164.** Write `bubbleSort(arr)` implementing bubble sort manually.
```
Input: bubbleSort([5, 2, 9, 1, 7])
Expected Output: [1, 2, 5, 7, 9]
```

**Q165.** Write `binarySearch(sortedArr, target)` returning the index or -1.
```
Input: binarySearch([1, 3, 5, 7, 9, 11], 7)
Expected Output: 3
```

**Q166.** Write `gcd(a, b)` computing the greatest common divisor.
```
Input: gcd(48, 18)
Expected Output: 6
```

**Q167.** Write `isPalindromeNumber(num)` checking if a number reads the same backward.
```
Input: isPalindromeNumber(12321)
Expected Output: true
```

**Q168.** Write `mostFrequentElement(arr)` returning the most frequently occurring element.
```
Input: mostFrequentElement([1, 2, 2, 3, 2, 4])
Expected Output: 2
```

---

## Day 29 — Algorithm Practice II

**Q169.** Write `twoSum(arr, target)` returning indices of two numbers that add up to target.
```
Input: twoSum([2, 7, 11, 15], 9)
Expected Output: [0, 1]
```

**Q170.** Write `chunkArray(arr, size)` splitting an array into chunks of given size.
```
Input: chunkArray([1, 2, 3, 4, 5], 2)
Expected Output: [[1, 2], [3, 4], [5]]
```

**Q171.** Write `flattenDeep(arr)` fully flattening a deeply nested array.
```
Input: flattenDeep([1, [2, [3, [4, 5]]], 6])
Expected Output: [1, 2, 3, 4, 5, 6]
```

**Q172.** Write `rotateArray(arr, k)` rotating array elements to the right by `k` positions.
```
Input: rotateArray([1, 2, 3, 4, 5], 2)
Expected Output: [4, 5, 1, 2, 3]
```

**Q173.** Write `matrixTranspose(matrix)` transposing a 2D array.
```
Input: matrixTranspose([[1, 2], [3, 4], [5, 6]])
Expected Output: [[1, 3, 5], [2, 4, 6]]
```

**Q174.** Write `longestWord(str)` returning the longest word in a sentence.
```
Input: longestWord("the quick brown fox jumps")
Expected Output: "quick"
```

---

## Day 30 — Final Mixed Challenge

**Q175.** Write `wordFrequencyCounter(str)` returning an object of word counts, case-insensitive.
```
Input: wordFrequencyCounter("The cat sat on the mat the cat ran")
Expected Output: { the: 3, cat: 2, sat: 1, on: 1, mat: 1, ran: 1 }
```

**Q176.** Write `validateForm(data)` checking required fields (`name`, `email`) exist and are non-empty, returning array of errors.
```
Input: validateForm({ name: "", email: "test@test.com" })
Expected Output: ["name is required"]
```

**Q177.** Write `shoppingCartTotal(cart)` where cart is an array of `{ price, qty }`, returning total cost.
```
Input: shoppingCartTotal([{ price: 10, qty: 2 }, { price: 5, qty: 3 }])
Expected Output: 35
```

**Q178.** Write `buildURLQuery(params)` converting an object into a query string.
```
Input: buildURLQuery({ search: "js", page: 2 })
Expected Output: "search=js&page=2"
```

**Q179.** Write `debounce(fn, delay)` implementing a debounce function (returns a function; conceptually delays execution until calls stop for `delay` ms).
```
Input: const log = debounce(() => "executed", 300); log(); log(); log();
Expected Output: "executed" (only runs once, after the last call + 300ms)
```

**Q180.** Combine concepts: Write `processOrders(orders)` that takes an array of `{ item, qty, price, status }`, filters only `"completed"` orders, calculates total revenue, and returns `{ totalRevenue, itemCount }`.
```
Input: processOrders([
  { item: "Pen", qty: 2, price: 5, status: "completed" },
  { item: "Book", qty: 1, price: 20, status: "pending" },
  { item: "Bag", qty: 1, price: 30, status: "completed" }
])
Expected Output: { totalRevenue: 40, itemCount: 2 }
```

---

## How to Use This Plan

- Spend **20–40 minutes/day** on each day's set — don't rush ahead even if it feels easy.
- Try to solve without looking anything up first; struggle is part of learning.
- Re-attempt any day's questions after a week to test retention.
- Days 1–10: Core fundamentals | Days 11–20: Objects, classes, closures | Days 21–30: Real-world patterns (errors, JSON, async, algorithms).

**Progress Tracker:**

| Day | Topic | Done? |
|-----|-------|-------|
| 1 | Variables & Data Types | ☐ |
| 2 | Operators | ☐ |
| 3 | Conditionals | ☐ |
| 4 | Loops | ☐ |
| 5 | Functions Basics | ☐ |
| 6 | Strings Basics | ☐ |
| 7 | String Methods Advanced | ☐ |
| 8 | Arrays Basics | ☐ |
| 9 | Array Methods (map/filter/reduce) | ☐ |
| 10 | More Array Methods | ☐ |
| 11 | Objects Basics | ☐ |
| 12 | Object Methods & Advanced | ☐ |
| 13 | Recursion | ☐ |
| 14 | Higher Order Functions | ☐ |
| 15 | Closures | ☐ |
| 16 | Destructuring, Spread & Rest | ☐ |
| 17 | Template Literals & Default Params | ☐ |
| 18 | Sets & Maps | ☐ |
| 19 | Classes Basics | ☐ |
| 20 | Classes Advanced & Inheritance | ☐ |
| 21 | Error Handling | ☐ |
| 22 | JSON | ☐ |
| 23 | Date & Time | ☐ |
| 24 | Regex Basics | ☐ |
| 25 | Arrays of Objects | ☐ |
| 26 | Promises Basics | ☐ |
| 27 | Async / Await | ☐ |
| 28 | Algorithm Practice I | ☐ |
| 29 | Algorithm Practice II | ☐ |
| 30 | Final Mixed Challenge | ☐ |
