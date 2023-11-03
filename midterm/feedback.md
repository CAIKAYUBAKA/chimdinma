# Midterm Feedback
The midterm feedback will be very similar to what you receive on a weekly basis for the homework, but more specific for each problem in this case.

## Final Score: 38/50


### Step 1: Priest Score Calculation
* **5pts** - Your code computed the correct probability and returned it
* **2pts** - You had a docstring that described what the function was for
* **(-3pts)** - No doctests

### Step 2: Find a Hospital
* **5pts** - Your code correctly fetched the correct hospital given the inputs using requests
  * **(-1pts) - This function was only supposed to return the hospital name.  It looks like yours returns the whole JSON string.  That JSON is what MY web service gives you.**
* **2pts** - You had a docstring that described what the function was for
* **(-3pts)** - No doctests

### Step 3: Get the Hospital Address
* **5pts** - Your code correctly fetched the JSON file, parsed it, and looked up the hospital
  * **(-1 pts) - Your code didn't handle input that didn't match the ga_hospitals.json file**
* **(-2pts)** - No docstring
* **(-3pts)** - No doctests

### Step 4: Process List of Patients
* **10pts** - Your code correctly fetched the psv file, looped through it, and ran your other functions
  * **(-8pts) - You properly parsed the file, but did not calculate priest score, lookup hospital, or get addresses**
* **2pts** - You had a docstring that described what the function was for

### Step 5: Compare Results
* **5pts** - Your code looped through all the results and compared them to the provided key

### Extra Credit
* Up to 15 pts based on correctness and quality of the extra credit step
  * **(+10 pts) Your code does the right kind of thing, but doesn't use the format being provided by the previous parts of the midterm.**

### Coding Best Practices:
**3 pts** - Was your code readable, efficient, and in line with what we learned in class?
* Good variable names?
* Code written into functions where appropriate?
* Appropriate comments with your code?
* Generally easy to follow and undersand?
