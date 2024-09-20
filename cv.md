# First and Last Name
Kachanau Aliaksandr

# My Contact Info
- Email: aleksandr.kachanov33@gmail.com
- Телефон: +375255230087
- LinkedIn: (https://www.linkedin.com/in/aleksandr-kachanov-b34aa1317/)
- GitHub: [github.com/ZLOBArio](https://github.com/ZLOBArio)

# Summary
I am a young and ever-motivated Junior JS Developer/Frontend Developer. I like to work on interesting projects. I communicate well. I am always ready to develop and also quickly grasp information. I am also eager to learn. I will always be glad to gain experience. 

### Skills
- Programming languages: C#, JavaScipt, CSS3, HTML5
- Frameworks: In the process of learning React
- Version control systems: Git
- Development tools: VS Code, WebStorm

### Code examples
```js
filterBtns.forEach((btn) => {
    btn.addEventListener('click', () => {
        changeFilterBtn();
        btn.classList.add('btn-active');
        let filterID = btn.id;

        filterImgs.forEach((img) => {
            if (img.classList.contains(filterID)) {
                img.style.display = "block";
                window.setTimeout(() => {
                    img.style.opacity = '1';
                    img.style.transform = 'scale(1)';
                }, 0);
            } else {
                img.style.opacity = '0';
                img.style.transform = 'scale(0)';
                window.setTimeout(() => {
                    img.style.display = "none";
                }, 0);
            }
        });
    });
```
Examples are available on the my Git page
- green-corp-lending from the layout training course. Simple layout using CSS
- The W2UP project developed for the Modsen Hackathon. The idea is a revolutionary solution for educational institutions: Converting grades into a points system for which it will be possible to receive rewards.
- Course work. Still in development. At the moment there is a template with working sliders.
- Also some projects lying on the PC such as: registration menu mail e.t.c.

### Education 
- GSU F. Skarynia 3nd year - CF (Computer Physics)

### Languages
- English
- Russia
- Belarusia

  <br>
[<img align="center" alt="rsschool" width="100px"  src="rs_school_js.svg" />](https://rs.school/courses/javascript-ru)
