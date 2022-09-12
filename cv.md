# Alexandra Frolova

## Contact information:
* E-mail: afrolova923@gmail.com
* Discord: Alexandra(@meztizshura)

## Briefly About Myself:
I am an information technology software student in college.  I am currently working as an energy engineer. My goal is to start a career junior front-end developer and develop in this area.I have good analytical skills.

## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code, Visual Studio
* Microsoft Office

## Code example:
Write a makeItFunny() function that takes a string as input and returns a copy of it with every nth element converted to uppercase. n – is set at the input to the function.
```javascript
const makeItFunny = (str, n) => {
  let i = 0;
  let result = '';
  while (i < str.length) {
    const newstr = str[i];
    if ((i + 1) % n === 0) {
      result = `${result}${newstr.toUpperCase()}`;
    } else {
      result = `${result}${newstr}`;
    }
    i++;
  }

  return result;
};
```
## Languages:
* Russian - Native
* Ukrainian - Intermediate
* English - Pre-Intermediate