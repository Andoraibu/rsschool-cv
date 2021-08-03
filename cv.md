# Andrey Khlybov

mobile: `+7 909-848-25-03` | e-mail: `elbroandrew@gmail.com`

## About me

My name is Andrey Khlybov. I'm a self-taught Junior JavaScript developer. I was majoring Mechanical Engineering in Komsomolsk-on-Amur State Technical University in 2010 and graduated with Master degree. For a long time up now I've been interested in computer technology and 3D graphics. Also I love learning English and learn it by myself. I studied it for two years in the university when I was taking a part-time course the in Sakhalin English Training center for a year. After that I did not quit learning English and still practicing it.

Few years ago I decided to change my life and become a JavaScript developer. I have tried some courses on `Udemy` , `Codecademy` and others. Also when I have a spare time I'm practicing coding at `codewars.com`, I love algorithms and data structures.

I would describe myself as a open-minded, easy-going person with good soft skills. 

My goals are to land a job in the IT field and grow up to a Team lead or Senior position. It's pushing me to do all my best to achieve this. 

## Education
- `Komsomolsk-on-Amur State Technical University`, `2010`, `Master degree` in `Mechanical Engineering`.
- English course at `Sakhalin English training center`. 
- `Udemy` -`JavaScript Algorithms and data structures` by Colt Steele.
- `Web Developer Bootcamp`, [see it here](https://andoraibu.github.io/yelpcamp/).
- `HTML Academy` - `Professional HTML course`.
- `Otus` - `Javascript Basics`.

## Technical skills
Basics of `HTML`, `CSS`, `Javascript`, `GIT`.

## Code examples
from my self-taught [repo](https://github.com/Andoraibu/js-algorithms-and-data-structures/blob/master/)
```javascript
//функция принимает имя и фамилию строкой и возвращает инициалы с точками
//пример: 'elon musk' -> E.M.

function getInitials(str){
    
    return str.split(' ').map(el => `${el[0].toUpperCase()}.` ).join('');

}

console.log(getInitials('elon musk junior'));

//get anagrams example
function getAnagrams(input) {
  let obj = {};
  input.split(" ").forEach(el => {
    let sortedEl = el.split('').sort().join('');
    obj[sortedEl] ? obj[sortedEl].push(el) : obj[sortedEl] = [el];
    });
  for(let key of Object.keys(obj)){
    if(obj[key].length <= 1){
      delete obj[key];
    }
  }

  return Object.values(obj);
}
```

## Work experience
Not related to the IT field. Mainly oil and gas industry.

## Projects

## English skills
In `2019` passed English `TOEIC` exam at `B2` level. Use it on a regular daily basis at my current job, writing buisness correspondes, discussing something with expats and so on.