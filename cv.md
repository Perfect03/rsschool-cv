# **[rsschool-cv](https://github.com/Perfect03/rsschool-cv)**

# **Gleb Zlobin**

## **Contacts**

* **Location:** Karagandy, Kazakhstan
* **Phone:** +77754563123
* **Email:** zlobin_gg52926@mail.ru
* **GitHub:** [Perfect03](https://github.com/Perfect03)

## **About Me**

I am 19 years old, now I am a 3rd year student of Tomsk State University, specializing in Applied Mathematics and Computer Science. In the course of my studies I got good C++ and SQL skills, also I am mastering the frontend on my own.

## **Skills**

* C++
* HTML/CSS + SCSS
* SQL
* JS

## **Code Example**

```
function formatDuration (seconds) {
  if(seconds===0)  return "now";
let s=[];
  s[0]=seconds%60; seconds-=s[0];
  s[4]=Math.floor(seconds/31536000); seconds -=(s[4]*31536000);
  s[3]=Math.floor(seconds/86400); seconds -=(s[3]*86400);
  s[2]=Math.floor(seconds/3600); seconds -=(s[2]*3600);
  s[1]=Math.floor(seconds/60); seconds -=(s[1]*60);
  
  let f=[];
  f[0]=" seconds"; f[1]=" minutes"; f[2]=" hours"; f[3]=" days"; f[4]=" years";
  let count=0;
  for(let i=0;i<5;i++)
    {
      if(s[i] == 0) {s[i]="";f[i]=""; count++}
      if(s[i] == 1) f[i] = f[i].substring(0, f[i].length-1);
    }
  let answ="";
  let k=0;
  for(let j=0;j<5;j++)
    {
      if(s[j] !=0) {answ = s[j]+f[j]+answ;
      if (k==0 && count!=4) answ = " and " + answ;
     else if (4-count !=k) answ = ", " + answ;k++}
    }
  return answ;
}
```

## **Education**
* **Tomsk State University** (3rd course)
    + Institute of Applied Mathematics and Computer Science

## **Languages**

* **Russian:** Native
* **English:** A2