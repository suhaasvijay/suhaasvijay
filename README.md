I'm a web developer, always learning and adapting to new technologies. My passion lies in creating websites that are both visually appealing and user-friendly. Staying updated with the latest trends in web technology is a commitment I've made to ensure continuous growth.

---

```javascript
import React, { useState } from "react";

const SoftwareEngineer = () => {
  const [state] = useState({
    name: "Suhaas V",
    role: "Full Stack Developer",
    languagesKnown: [
      { language: "JavaScript", status: "Moderate + Learning" },
      { language: "Html", status: "Proficient" },
      { language: "Css", status: "Proficient" },
      { language: "Java", status: "Beginner" },
      { language: "C", status: "Learning" },
    ],
  });

  const sayHi = () => {
    console.log("Thanks for dropping by, hope you find some of my work interesting.");
  };

  const renderLanguageSkills = () => {
    return state.languagesKnown.map((lang) => (
      <li key={lang.language}>
        {lang.language} - {lang.status}
      </li>
    ));
  };

  return (
    <div>
      <h1>Hello, I'm {state.name}!</h1>
      <p>I am a {state.role}.</p>
      <p>I know these programming languages:</p>
      <ul>{renderLanguageSkills()}</ul>
      <button onClick={sayHi}>Say Hi!</button>
    </div>
  );
};

export default SoftwareEngineer;
```
---

### Skills and Tools:
![NextJS](https://img.shields.io/badge/NextJS-black?style=for-the-badge&logo=next.js&logoColor=white)
![ReactJS](https://img.shields.io/badge/ReactJS-black?style=for-the-badge&logo=react&logoColor=#61DAFB)
![ReactJS](https://img.shields.io/badge/React-black?style=for-the-badge&logo=figma&logoColor=#F24E1E)
![ReactJS](https://img.shields.io/badge/VS_Code-black?style=for-the-badge&logo=visualstudiocode&logoColor=#007ACC)
![ReactJS](https://img.shields.io/badge/Android_Studio-black?style=for-the-badge&logo=androidstudio&logoColor=#3DDC84)
![ReactJS](https://img.shields.io/badge/HTML5-black?style=for-the-badge&logo=html5&logoColor=#E34F26)
![ReactJS](https://img.shields.io/badge/CSS3-black?style=for-the-badge&logo=css3&logoColor=#1572B6)
![ReactJS](https://img.shields.io/badge/JavaScript-black?style=for-the-badge&logo=javascript&logoColor=#F7DF1E)
![ReactJS](https://img.shields.io/badge/TypeScript-black?style=for-the-badge&logo=typescript&logoColor=#3178C6)
![ReactJS](https://img.shields.io/badge/NPM-black?style=for-the-badge&logo=npm&logoColor=#CB3837)
![ReactJS](https://img.shields.io/badge/Git-black?style=for-the-badge&logo=git&logoColor=#F05032)
![ReactJS](https://img.shields.io/badge/Github-black?style=for-the-badge&logo=github&logoColor=#181717)
![ReactJS](https://img.shields.io/badge/Vite-black?style=for-the-badge&logo=vite&logoColor=#646CFF)
![ReactJS](https://img.shields.io/badge/NodeJS-black?style=for-the-badge&logo=nodedotjs&logoColor=#339933)
![ReactJS](https://img.shields.io/badge/ExpressJS-black?style=for-the-badge&logo=express&logoColor=#000000)

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=suhaasvijay&layout=compact&theme=dark&hide_border=true)
---

![Suhaas's github stats](https://github-readme-stats.vercel.app/api?username=suhaasvijay&show_icons=true&hide_border=true&theme=dark)
---
### 📫 Reach me at 
[![Twitter Follow](https://img.shields.io/twitter/follow/suhaas_v10?style=social)](https://twitter.com/suhaas_v10)
[![Linkedin Badge](https://img.shields.io/badge/-suhaasv7-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/harshkumarkhatri/)](https://www.linkedin.com/in/suhaasv7/)
[![Gmail Badge](https://img.shields.io/badge/-suhaasvijay7@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:mailharshkhatri@gmail.com)](mailto:suhaasvijay7@gmail.com)
