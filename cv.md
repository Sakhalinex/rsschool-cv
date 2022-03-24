# Dmitriy An

![my photo](https://ibb.co/P6RK8rd)

---

#### Contact information:

**Phone:** +7 (914) 311-62-28
**E-mail:**  dmitrii.7774@gmail.com
**Vk:** vk.com/jseer
**NickName discord:** @sakhalinex

---

#### Briefly About Myself:

I am 22 years old, I am a 5th year student at the University of the Pacific National University with a degree in Economic Security. In the process of studying at the university, an interest in the IT field arose, and at the same time I began to study Front-end development. Signed up for a course to master the profession of Front-end developer

---

#### Skills and Proficiency:

1. HTML/CSS
2. Sass
3. JavaScript
4. Git
5. Github
6. figma
7. VS code

---

#### Code example:
**Kata from codewars:**
The objective is to return all pairs of integers from a given array of integers that have a difference of 2.
The result array should be sorted in ascending order of values. Assume there are no duplicate integers in the array.
The order of the integers in the input array should not matter.

**Solution:**
```
const twosDifference = input => {
  let result = [];
  for (let i = 0; i < input.length; i++) {
    for (let j = i + 1; j < input.length; j++) {
      if (input[i] - input[j] === 2 || input[i] - input[j] === -2) {
        result.push([input[i], input[j]].sort((a, b) => a - b))
      }
    }
  }
  return result.sort((a, b) => a[0] - b[0])
}
```

---