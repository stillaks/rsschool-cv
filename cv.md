# Akerke Otarbayeva

Phone: +7(708) 175 71 21 

Email: <akerke.otarbayeva@gmail.com>

Telegram: @stillaks

Address: Nur-Sultan, Kazakhstan

### Summary
I am Akerke Otarbayeva. I am from Astana, Kazakhstan. I work as a Laboratory Assistant at the Physics Department of Nazarbayev University. I am quite experienced in setting up experiments, working with various experimental applications, analyzing data and writing manuals for experiments. In my free time, I like learning programming languages.

### Skills 
- Knowledge of languages:  
  - Kazakh – native 
  - Russian – fluent 
  - English – Upper Intermediate
- Computer skills (Python, JavaScript, HTML, CSS, LaTEX)
- Skills in conducting physics experiments and analyzing data.

### Code examples
```
function fridayTheThirteenths(start, end) {
  end = end || start;
  let date = new Date(start, 0, 13);
  let fridays13 = [];

  for (let year = start; year &lt;= end; year++) {
    date.setFullYear(year);
    for (let month = 0; month &lt; 12; month++) {
      date.setMonth(month);
      if (date.getDay() === 5) {
        const strDate = `${date.getMonth() + 1}/13/${date.getFullYear()}`;
        fridays13.push(strDate);
      }
    }
  }
  return fridays13.join(" ");
}
```

### Certificates
1. Python for Everybody Specialization, University of Michigan, Coursera.

2. JS/FE PRE-SCHOOL 2022 (JAVASCRIPT), The Rolling Scopes School.