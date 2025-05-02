# list-comprehension-generator-function-OOP
- ~ flips bits.
- In two's complement, flipping bits is equivalent to negating and subtracting 1.
- ~x is the same as -(x+1).

- The walrus operator := was introduced in Python 3.8.

- It allows assignment and evaluation in a single expression.

## 👍 When to use it?
Use it when:

You need to calculate something and use it right away

You want to avoid repeating code

You want your code to be cleaner and shorter

## String
- a string is a sequence of characters enclosed in quotes (either single, double, or triple quotes). 
- Strings are immutable, meaning they cannot be changed after they are created.

## Unicode Character
- print(r"\u0041 = ", "\u0041")
- r"\u0041" is a raw string — the r in front tells Python not to process escape sequences.
- "\u0041" is processed — Python sees \u0041 as a Unicode escape for the character 'A'.
- Show the literal text of escape characters like \n, \t, \u etc.
- Prevent Python from interpreting them.

index() → Finds substring, raises error if not found.
find() → Finds substring, returns -1 if not found (safer).


- The % operator is an older way of formatting strings in Python.
- Yes, order matters when using string formatting in Python,


**Interning** is a process where Python stores only one copy of certain strings in memory and reuses them whenever the same string is used again.
- Explicit interning: You can manually intern a string using the sys.intern() function.


String interning is also known as "string caching" or "string sharing".

**remove() method**:

The **remove()** method removes the specified item from the set.
If the item is not found in the set, it raises a KeyError.
This method is suitable when you are sure that the item exists in the set.

**discard() method:**

The **discard()** method also removes the specified item from the set.
However, if the item is not found in the set, it does not raise any error. It simply does nothing.
This method is suitable when you are not sure if the item exists in the set.

### 📊 What is Load Factor?
Load Factor = (number of items) ÷ (total available slots)

If this ratio gets too high (e.g., 0.66 or 66%), Python decides to rehash to avoid collisions and keep performance fast.


## set 
- Set har item ka hash banata hai.
- Is hash se item ki position decide hoti hai.
- Isi wajah se:
- Order fix nahi hota.
- Lookup, insert, remove — sab fast hote hain (O(1) time).
