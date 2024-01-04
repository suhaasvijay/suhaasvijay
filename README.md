# Hi there, I'm Suhaas V 👋

I am a budding Full Stack Developer at the exciting startup, **Codosphere**. As a beginner in this field, I am on a continuous journey, learning and growing every day. I have a keen interest in designing websites and am always thrilled to see well-thought-out visual designs and models come to life.

👨‍💻 **Passionate about Technology:** My interest lies in making life easier by developing utility tools and applications that solve everyday problems. I am constantly exploring new technologies and techniques in web development to enhance my skills.

🚀 **Current Focus:** I am currently engrossed in understanding and mastering Full Stack Development. While I am at the start of my journey, I am eager to delve deeper into front-end and back-end technologies, especially those that contribute to building sleek and efficient web applications.

💼 **Working Environment:** As a member of the vibrant team at Codosphere, I am immersed in a fast-paced, innovative environment where I can apply my skills and learn from the best.

👁️ **Design Enthusiast:** I have a special interest in website aesthetics and functionality. A well-designed website with excellent visual design elements and models not only appeals to me but also inspires my work.

🌱 **What I'm Learning:** Every day is a learning opportunity. Currently, I am focusing on enhancing my skills in various aspects of Full Stack Development, including new programming languages, frameworks, and design techniques.

---

I'm excited to be on this journey, constantly pushing the boundaries of my knowledge and skills in Full Stack Development and design. If you're interested in my work or collaborating on a project, feel free to reach out!



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

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=suhaasvijay&layout=compact&theme=dark&hide_border=true)

![Suhaas's github stats](https://github-readme-stats.vercel.app/api?username=suhaasvijay&show_icons=true&hide_border=true&theme=dark)
