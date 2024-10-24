# Existential Random Number Generator
This repository was created in order to take part in Ukraine's Best Shitty Code Competition held by Robot Dreams 😎

### Documentation for the Existential Random Number Generator Code

---

**Title:** Existential Random Number Generator

**Description:**
This code prompts the user to generate a random number from 1 to 100 by asking them to input a number of their choice. After displaying this number, it answers the existential question of whether robots can defeat humankind.

**Language:** JavaScript

---

**Code:**

```javascript
var randomNumber = confirm("To generate a random number from 1 to 100, press OK") && (alert(`The random number is: ${prompt("Think of a number from 1 to 100, then input it below:")}`), alert("By the way, what was that question again? Could a robot defeat humankind? Hmm... I figure the answer is obvious now, peasant."));
```

---

**Usage:**

1. This code can be executed simply in a Web Browser Console.
2. When the code is executed, a confirmation dialog appears, asking the user to press "OK" to generate a random number.
3. If the user confirms, a prompt appears asking them to think of a number from 1 to 100 and enter it.
4. An alert displays the number that user entered as a random number the user wanted to generate.
5. A second alert answers the existential question about robots' ability to defeat humankind.

---

**Functionality:**
- **`confirm()`**: Displays a dialog with an OK and Cancel button to confirm whether the user wants to generate a random number.
- **`prompt()`**: Prompts the user to enter a number.
- **`alert()`**: Displays alerts to the user with messages about the random number and the answer to the question regarding robots' ability to defeat humanity.

---

**Notes:**
- This code is a solution to both number 1 and number 4 problems, presented by Robot Dreams in their Suggested Problems List for the Ukraine's Best Shitty Code Competition.
