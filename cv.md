## Dmitriy An
---
#### Contacts

* **Location:** Vladivostok, Russia
* **Phone:** +7(914)-311-6228
* **Email:** dmitrii.7774@gmail.com
* **GitHub:** [sakhalinex](https://github.com/Sakhalinex)

---
#### About me

I love programming and study at RS-School to get practical skills, as well as to improve my level in the field of programming, in addition to programming, I go in for sports, read books. Purposefulness and patience will help me achieve the desired level in the IT field and find a job.

---
#### Skills

* HTML
* CSS/SCSS
* JavaScript
* Git
* React

---
#### Code Example

**Condition:**
*Let us consider this example (array written in general format):*

*ls = [0, 1, 3, 6, 10]*

*Its following parts:*

*ls = [0, 1, 3, 6, 10]*
*ls = [1, 3, 6, 10]*
*ls = [3, 6, 10]*
*ls = [6, 10]*
*ls = [10]*
*ls = []*
*The corresponding sums are (put together in a list): [20, 20, 19, 16, 10, 0]*
*The function parts_sums (or its variants in other languages) will take as* *parameter a list ls and return a list of the sums of its parts as defined above.*

```
const partsSums = (ls) => {
	let sum = ls.length ? ls.reduce((acc, cur) => acc += cur) : 0,
		result = [sum],
		temp = 0;

	while (result.length != ls.length + 1) {
		for (let i = 0; i < ls.length; i++) {
			temp += ls[i]
			result.push(sum - temp)
		}
	}
		
	return result
}
```
---
#### Expirience

* [portfolio site](https://github.com/Sakhalinex/portfolio_site) (html, scss, git, BAM)
* [createx construction](https://github.com/Sakhalinex/createx_construction) (html, scss, js, BAM)

---
#### Education

**Courses:**
* rs school
* course by Vladilen Minin
* course by Ivan Petrichenko
* course by Archakov Blog
* HTML Academy

---
#### English
Level: *A1*