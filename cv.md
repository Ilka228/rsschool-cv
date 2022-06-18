# Ilya Solonovich

## Junior Frontend Developer

## Contacts

+ **Phone:** +7-977-612-18-40
+ **Email:** ilyasolonovich20@gmail.com
+ **Telegram:** @M4xW3l11
+ **Discord:** M4xW3ll

## About me

I'm fourth grade student at MIPT. Learning programming for half a year. I can learn new things and absorb new information in a short period of time.
Currently keen on programming and spending all my free time learning that.

## Skills

+ HTML
+ CSS
+ JavaScript (Basic)
+ Git , GitHub
+ VS Code
+ Adobe Photoshop, Illustrator

## Code Example
```javascript
const format = (diffTree) => {
  const innerFormat = (diff, path) => {
    const callback = (obj) => {
      const { key, type } = obj;
      const property = path ? `${path}.${key}` : key;

      return mapping[type](property, obj, innerFormat);
    };

    return diff.map(callback).filter(removeEmptyStrings).join('\n');
  };

  return innerFormat(diffTree, '');
};
```
## Education

+ **University:** Moscow Institute of Physics and Technology, Department of Physical and Quantum Electronics
+ **Courses:**
    * [HTML Academy](https://htmlacademy.ru/)
    * [Hexlet](https://ru.hexlet.io/)
    * [LoftSchool](https://loftschool.com/)  

## Languages

+ English(B2)
+ Russian(Native)
+ Belorussian(Advanced)
