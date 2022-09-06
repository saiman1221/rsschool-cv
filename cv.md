![My Photo](https://user-images.githubusercontent.com/82938600/188323498-595874f6-f02d-4606-b210-3142222e89cd.jpg)

# __Parubtsev Viacheslav__

## Junior Frontend Developer

### Contact information:

* Phone: +375 33 636 1227
* E-mail: slavaparybcev2003@gmail.com
* Telegram: @viacheslav_2003

---

### About Me:
I am a third-year student of BSUIR. I have been developing as a front-end developer for more than six months, but for the last three months I have been developing full-fledged web applications. I've worked with PHP and JS, but now I'm getting deeper and deeper into JavaScript development. I am a fast learner, work hard and develop my skills every day.

---

### My skills:

*	HTML5, CSS3, BOOTSTRAP
*	JavaScript, React.js Basics
*	GitHub, BitBucket
*	Figma

---

### Code example:

```
function rot13(str){
  let str1 = String(str);
  
  var alphabets = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'; 
  var alphabets13 = 'NOPQRSTUVWXYZABCDEFGHIJKLM';
  var sym = " !@#$%^&*()_+-=\"№;:|\/?.,<>{}[]\\\n\'~\`";
  var nums = "1234567890";
  var alphabetsMini = alphabets.toLowerCase();
  var alphabets13Mini = alphabets13.toLowerCase(); 
  
  var resultStr = "";
  for(let i=0; i<str1.length; i++){
      for(let j =0; j<50; j++){
          if(str1[i] === alphabets[j])
          {
            resultStr += alphabets13[j];
          }
        if(str1[i] === alphabetsMini[j])
          {
            resultStr += alphabets13Mini[j];
          }
        if(str1[i] === sym[j]){
          resultStr += sym[j];
        }
        if(str1[i] === nums[j]){
          resultStr += nums[j];
        }
      }
  }
  return resultStr;
}
``` 

### Languages:
*	Russian - Native
*	English – Pre-Intermediate (A2)
