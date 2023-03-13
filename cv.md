# Begench Dovletov

## Contacts

- Location: Orel, Russia
- Phone: +79586558584
- Email: begench.dev@gamil.com
- GitHub: https://github.com/DAB-IT-28

## About Me

I am Begench Dovletov. I am studying at a technical university in the 4th
year. I am actively studying front-end development. Sometimes I work
as a freelancer. I want to learn new technologies and develop in the
IT.

## Skills

- HTML
- CSS/SASS
- JavaScript
- Git
- C#

## Code example

      function queueTime(customers, n) {
        let i = 0,
            tills = [];
        for(i; i < n; i++){
          tills[i] = 0;
        }

        customers.forEach((min) => {
          tills.fill((getMin(tills)['min'] + min), getMin(tills)['index'],
                     getMin(tills)['index'] + 1);
        });
        return Math.max(...tills);
      }

      function getMin(tills) {
        let min = tills[0],
            index = 0;
        tills.forEach((till, key) => {
          if(till < min) {
            min = till;
            index = key;
          }
        });
        return {'index': index, 'min': min};
      }

## Education

Tver State Technical University (Specialty “Computer Science and
Computer Engineering”)

## Language

- Turkmen
- Turkish
- Russian

## English

A2. I try to learn English in every possible way. I use application in smartphone: Duolingo and I use google translate a lot.
