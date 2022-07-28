# Kazachonok Anastasia
### Junior Frontend Developer

---

## Contact information:         

**Location:** Minsk, Belarus   
**Phone:** +375 (44) 725 91 41     
**E-mail:** anastasia-kaz@mail.ru     
**Telegram**  [https://t.me/anastasia_kaz1](https://t.me/anastasia_kaz1)    
**LinkedIn** [https://www.linkedin.com/in/anastasia-kaz](https://www.linkedin.com/in/anastasia-kaz)  
**GitHub** [https://github.com/anastasia-kaz](https://github.com/anastasia-kaz)

---

## About Myself:

I am 21 years old, at the moment I work as a software testing engineer and study frontend.I like to learn, develop     
and get better every day. I also continue to study English in order to travel and expand my horizons

## Personal qualities:

* Dependable
* Team player
* Learning agility 
* Quality-oriented
* Attentive
* Сommunicative

## Special skills:

* HTML5
* CSS3
* JavaScript Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
* Figma (for web development)

---

## Code Examples:

```
let jsonData = pm.response.json();

for (let i=0; i<jsonData.length; i++){
const req={
    url: 'http://162.55.220.72:5005/curr_byn',
    method: 'POST',
    header: {
        'Content-Type': 'multipart/form-data',
    },
        
    body: {
    mode:'formdata',
    formdata:[
        {key: "auth_token", value:  pm.environment.get("token")},
        {key: "curr_code", value:  pm.response.json()[i].Cur_ID}
    ]},
    };
pm.sendRequest (req, function (err, res) {  
if (res.code === 500) {return;}
else if (res.code === 200 && res.json().Cur_OfficialRate != undefined) {
console.log(res.json());
}});
};
```

---

## Work experience:

I have experience writing automated tests for the API in postman using JS. there is also experience in testing various web projects.

---

## Education:

* Belarusian State Academy of Communications   
Specialty: postal engineer

* Minsk State College of Services   
Specialty: postal communication technician

---

## Courses:

* V.Ksenzov's author's course on software testing   
Specialty: quality assurance engineer

* Сourse on test automation "automation for everyone"   
Specialty: automation quality assurance engineer

---

## Languages:

* Russian - native speaker
* English - A2 (improving to B1)
