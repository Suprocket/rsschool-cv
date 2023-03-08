# Maxim Samokhvalov

## Junior frontend developer

### Contact information:

Phone: +79911083606
Telegram: [sa_max_valoff](https://t.me/sa_max_valoff)  
github: [suprocket](https://github.com/Suprocket)  

### Briefly about myself:

Hi! I like to create cool interactive websites that will profit to the business. Also, I like to learn something new from the IT world and implement it immediately. I think that the Front-end developing will help me to reach the goals for IT.

### Skills and Proficiency:

1. HTML (Emmet)
2. SASS (Tailwind, Bootstrap)
3. JS (Clear)
4. Git
5. Figma & Photoshop
6. VS Code
7. 1C-bitrix, Wordpress
8. PHP, Python, C++ (Base syntax)
9. Blender

### Work projects:

* [Create SPA for stmwater.ru](https://stmwater24.ru/)  
* [Pet-projects in my github](https://github.com/Suprocket)

### Code example:

My example of creating an aggregation with a reduce method:

```
const groupBy = (arrOfUsers, nameOfKey = '') => {
  let preacc = (acc, user) => {
    if (!Object.hasOwn(acc, user[nameOfKey])) {
      acc[user[nameOfKey]] = [];
    }
    acc[user[nameOfKey]].push(user);
    return acc;
  }
  let total = arrOfUsers.reduce(preacc, {});
  return total;
}
 
const students = [
  { name: 'Tirion', class: 'B', mark: 3 },
  { name: 'Keit', class: 'A', mark: 3 },
  { name: 'Ramsey', class: 'A', mark: 4 },
];
 
console.log(groupBy([], ''));
console.log(groupBy(students, 'mark'));
```

### Courses:

Result school (junior frontend dev, february 2022)  
Hexlet (junior frontend dev, october 2022)  

### Languages:

English B1,  
French A2.