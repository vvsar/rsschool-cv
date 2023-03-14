# Victor Saraev  

![Photo](/img/mar0600.jpg) 

## Contacts  
E-mail: vvsar@mail.ru  
Skype: victor.saraev  
Telegram: Victor Saraev  
[LinkedIn](https://www.linkedin.com/in/victor-saraev-2aa72a62/) 

## About me  
A highly proficient and experienced chemist worked for EPAM Systems till 2022. Although lacking IT education and experience, I like the opportunity to receive new knowledge and skills necessary for IT specialists. Possessing good interpersonal and synthetic skills, I am on the point of boosting the personal growth that may turn my life upside down.

## IT hard skills  
Beginner

## Code example
[Human readable duration format - 4 kyu kata at Codewars:](https://www.codewars.com/kata/52742f58faf5485cae000b9a)

```
function formatDuration (seconds) {
  if (seconds == 0) return "now";
  let secs = seconds % 60;
  let mins = Math.floor(seconds /60) % 60;
  let hours = Math.floor(seconds / 3600) % 24;
  let days = Math.floor(seconds / (24 * 3600)) % 365;
  let years = Math.floor(seconds / (365 * 24 * 3600));
  let result = '';
  let arr = [];
  if (years != 0) {
    let y = (years > 1) ? `${years} years` : '1 year';
    arr.push(y);
  }
  if (days != 0) {
    let d = (days > 1) ? `${days} days` : '1 day';
    arr.push(d);
  }
  if (hours != 0) {
    let h = (hours > 1) ? `${hours} hours` : '1 hour';
    arr.push(h);
  }
  if (mins != 0) {
    let m = (mins > 1) ? `${mins} minutes` : '1 minute';
    arr.push(m);
  }
  if (secs != 0) {
    let s = (secs > 1) ? `${secs} seconds` : '1 second';
    arr.push(s);
  }
  if (arr.length == 1) {
    result += arr[0];
    return result;
  }
  if (arr.length == 2) {
    result = arr.join(' and ');
    return result;
  }
  let last = arr.pop();
  result = arr.join(', ') + ' and ' + last;
  return result;
}
```

## Last occupation  
scientific curation specialist (non-IT, contractor) since 2010 till 2022  
EPAM Systems (St. Petersburg branch)
  
## Education  
**1988-1993**  
engineering in chemical technology of organic compounds of nitrogen  
St. Petersburg State Institute of Technology  
*(interrupted by the military service)*  
**1993-1996**  
organic chemistry - post-graduate course  
St. Petersburg State Institute of Technology  
**1999**  
PhD in organic chemistry

## Languages
- Russian (native)
- English (B1)
- Swedish (beginner)