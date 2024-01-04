# Greetings, I'm Suhaas V 👋

As an emerging Full Stack Developer at **Codosphere**, I am deeply involved in the world of web development. Eagerly learning and constantly enhancing my skills, I am particularly drawn to the aesthetics and functionality of website design.

👨‍💻 **Professional Pursuit:** Dedicated to the craft, I am constantly exploring and employing innovative technologies to solve complex problems and create impactful solutions.

🚀 **Current Role:** My current focus is mastering Full Stack Development at Codosphere. Each day is an opportunity for growth and advancement in this dynamic and challenging field.

👁️ **Design Enthusiast:** My special interest lies in the aesthetics and functionality of websites. A well-designed website with excellent visual design elements not only captivates me but also drives my passion for creating compelling and user-friendly digital experiences.

🌱 **Continuous Learning:** Committed to lifelong learning, I am continuously exploring new programming languages, frameworks, and design techniques to stay at the forefront of the ever-evolving web technology landscape.

---

```javascript
import React from "react";

class SoftwareEngineer extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      name: "Suhaas V",
      role: "Full Stack Developer",
      languagesKnown: [
        { language: "JavaScript", status: "Moderate + Learning" },
        { language: "Html", status: "Proficient" },
        { language: "Css", status: "Proficient" },
        { language: "Java", status: "Beginner" },
        { language: "C", status: "Learning" },
      ],
    };
  }

  sayHi = () => {
    console.log("Thanks for dropping by, hope you find some of my work interesting.");
  };

  renderLanguageSkills() {
    return this.state.languagesKnown.map((lang) => (
      <li key={lang.language}>
        {lang.language} - {lang.status}
      </li>
    ));
  }

  render() {
    return (
      <div>
        <h1>Hello, I'm {this.state.name}!</h1>
        <p>I am a {this.state.role}.</p>
        <p>I know these programming languages:</p>
        <ul>{this.renderLanguageSkills()}</ul>
        <button onClick={this.sayHi}>Say Hi!</button>
      </div>
    );
  }
}

export default SoftwareEngineer;
```
---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=suhaasvijay&layout=compact&theme=dark&hide_border=true)
---

![Suhaas's github stats](https://github-readme-stats.vercel.app/api?username=suhaasvijay&show_icons=true&hide_border=true&theme=dark)
---
### 📫 Reach me at 
![Twitter Follow](https://img.shields.io/twitter/follow/suhaas_v10?style=social)
