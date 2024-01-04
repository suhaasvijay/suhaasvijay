### Hi there 👋

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

![Ghazi's github stats]([https://github-readme-stats.vercel.app/api?username=suhaasvjiay&show_icons=true&hide_border=true&theme=dark](https://github-readme-stats.vercel.app/api?username=suhaasvijay&show_icons=true&hide_border=true&theme=dark)https://github-readme-stats.vercel.app/api?username=suhaasvijay&show_icons=true&hide_border=true&theme=dark)
