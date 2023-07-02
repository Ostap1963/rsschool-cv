# Ostap Hrytsyk

## **Contacts**

- **Location:** Lviv, Ukraine
- **Phone:** +380631487868
- **Email:** hrytsykostap@gmail.com
- **LinkedIn:** [Ostap Hrytsyk](https://www.linkedin.com/in/ostap-hrytsyk/)

## **About Me**

Front-end developer with 1+ year of experience who is comfortable working with Javascript, HTML/CSS, and responsive web \
design to deliver exceptional customer experience. I have proven experience in creating and designing software in a test-driven environment.

## **Skills**

- HTML5, CSS3
- JavaScript Basics
- Git, GitHub
- VS Code, IntelliJ IDEA
- Adobe Photoshop, Illustrator

### Code example:

**Shortest Word:**
_Simple, given a string of words, return the length of the shortest word(s). String will never be empty and you do not need to account for different data types._

```javascript
function findShort(str) {
  // Split the string into an array of words
  const words = str.split(" ");

  // Find the shortest length using the reduce method
  const shortestLength = words.reduce((acc, word) => {
    const length = word.length;
    return length < acc ? length : acc;
  }, Infinity);

  return shortestLength;
}
```

## **Education**

- **University:** Lviv Polytechnic National University, Computer Science (Artificial Intelligence department)
- **Courses:**
  - [CS50 lectures](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA)
  - [FreeCodeCamp](https://www.freecodecamp.org)

## **Languages**

- English \- Upper-Intermediate
- Ukrainian \- Native
