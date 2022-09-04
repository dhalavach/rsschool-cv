### Dmitry Halavach

---

#### Skills

- HTML
- CSS
- Javascript
- Automated Testing (Java)

#### Code Example

    //Function to sort an array of 32-bit integers
    //in ascending order of the number of on bits they have.

    function sortByBit(arr) {
    function bitCounter(n) {
        return n.toString(2).replace(/0/g, "").length;
    }

    function comparator(a, b) {
        return bitCounter(a) - bitCounter(b) == 0
        ? a - b
        : bitCounter(a) - bitCounter(b);
    }

    return arr.sort(comparator);
    }

#### English Level

C2

#### Further Code Examples.

[Drag and Drop Images](https://replit.com/@DmitryHalavach/drag-and-drop#index.html)

[Form Validation](https://replit.com/@DmitryHalavach/form-validation#index.html).

[Function to Check if String is a Palyndrom](https://replit.com/@DmitryHalavach/palindrom-no-recursion#script.js)

#### Education

Ph.D. in History (2019)
