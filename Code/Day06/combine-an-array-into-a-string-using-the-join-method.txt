function sentensify(str) {
  // Only change code below this line
  const strAsArray = str.split(/\W/)
  const strAsSentence = strAsArray.join(" ")
  return strAsSentence
  // Only change code above this line
}
sentensify("May-the-force-be-with-you");
