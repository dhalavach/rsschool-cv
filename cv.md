### Dmitry Halavach

---

#### Skills

- HTML
- CSS
- Javascript
- Automated Testing (Java)

#### Code Example

    //Function returning human readable date

    function formatDuration(seconds) {
    var secondsNumber = { year: 31536000, day: 86400, hour: 3600, minute: 60, second: 1 },
        result = [];

    if (seconds === 0) return "now";

    for (var key in secondsNumber) {
        if (seconds >= secondsNumber[key]) {
        var val = Math.floor(seconds / secondsNumber[key]);
        result.push((val += val > 1 ? " " + key + "s" : " " + key));
        seconds = seconds % secondsNumber[key];
        }
    }

    return result.length > 1
        ? result.join(", ").replace(/,([^,]*)$/, " and" + "$1")
        : result[0];
    }

#### English Level

C2

#### Further Code Examples.

[Drag and Drop Images](https://replit.com/@DmitryHalavach/drag-and-drop#index.html)

[Form Validation](https://replit.com/@DmitryHalavach/form-validation#index.html).

[Function to Check if String is a Palyndrom](https://replit.com/@DmitryHalavach/palindrom-no-recursion#script.js)

#### Education

Ph.D. in History (2019)
