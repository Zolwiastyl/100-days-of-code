// The global variable
var globalTitle = "Winter Is Coming";

// Only change code below this line
function urlSlug(title) {
    const stringAsArrayOfLetters = title.split(/\W/).filter((obj) => obj!=="").join("-").toLowerCase()
    return stringAsArrayOfLetters
}
// Only change code above this line

var winterComing = urlSlug(globalTitle); // Should be "winter-is-coming"
