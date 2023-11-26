# Dilshodbek Gulomov

## Contact information

- **Phone:** +998 944143475
- **E-mail:** [dilshodjongulomov53@gmail.com](mailto:dilshodjongulomov53@gmail.com)
- **Instagram:** [@dilshodbek_gulomov](https://www.instagram.com/dilshodbek_gulomov/)
- **Telegram:** [@junior_software_engineer](https://t.me/junior_software_engineer)
- **LinkedIn:** [Dilshodbek Gulomov](https://www.linkedin.com/in/dilshodbek-gulomov/)
- **GitHub:** [https://github.com/Dilshodjon2004](https://github.com/Dilshodjon2004)

## Summary

As a frontend web developer, I'm eager to advance in the field of software development. My passions include acquiring knowledge of emerging technologies, undertaking diverse web projects, and more. I excel in quickly grasping new concepts, resolving complex issues, and effectively communicating with others.

## Skills

- HTML
- CSS (TailwindCSS, Bootstrap, SASS, BEM methodology)
- JavaScript (Fundamentals, OOP, Asynchronous JavaScript, ES6+, DOM)
- React JS (basic knowledge)
- Version control: git (remote service GitHub)

## Code examples

```js
// 13. Roman to Integer
// https://leetcode.com/problems/roman-to-integer/
function romanToInt(string) {
  const values = new Map([
    ["I", 1],
    ["V", 5],
    ["X", 10],
    ["L", 50],
    ["C", 100],
    ["D", 500],
    ["M", 1000],
  ]);
  let result = 0,
    current,
    previous = 0;
  for (const char of string.split("").reverse()) {
    current = values.get(char);
    if (current >= previous) {
      result += current;
    } else {
      result -= current;
    }
    previous = current;
  }
  return result;
}

console.log(romanToInt("III")); 
console.log(romanToInt("LVIII"));
console.log(romanToInt("MCMXCIV"));
```
## Education

- **Bachelor, Ajou University in Tashkent**
  - Faculty of Eelectrical and Computer Engineering

## Experience

- Worked as a freelancer
- Worked as a ESL instructor at Learning Center
- Created small pet [projects](https://github.com/Dilshodjon2004?tab=repositories)
- Internship in [a1qa](https://www.linkedin.com/company/a1qa/)

## Languages

- Uzbek (native)
- English
- Korean