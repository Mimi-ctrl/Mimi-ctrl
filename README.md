# Hello World! <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="100">

```javascript
const levelOptions = ["Beginner", "Intermediate", "Good", "Very Good", "Excellent"];
const interestOptions = ["Low", "Medium", "High", "Very High"];

const laura = {
  name: "Laura",
  pronouns: ["she", "her"],
  skills: {
    programmingLanguages: [
      { name: "Python", level: levelOptions[4], currentlyLearning: false },
      { name: "JavaScript", level: levelOptions[2], currentlyLearning: true  },
      { name: "TypeScript", level: levelOptions[0], currentlyLearning: true },
      { name: "HTML", level: levelOptions[3], currentlyLearning: false },
      { name: "CSS", level: levelOptions[3], currentlyLearning: false },
      { name: "Node.js", level: levelOptions[2], currentlyLearning: true },
    ],
    toolsAndTechnologies: [
      { name: "React", level: levelOptions[2], currentlyLearning: true },
      { name: "Redux", level: levelOptions[0], currentlyLearning: true },
      { name: "MongoDB", level: levelOptions[2], currentlyLearning: true },
      { name: "PostgreSQL", level: levelOptions[2], currentlyLearning: false },
      { name: "GraphQL", level: levelOptions[1], currentlyLearning: true },
      { name: "Docker", level: levelOptions[0], currentlyLearning: true },
      { name: "Jest", level: levelOptions[0], currentlyLearning: true },
      { name: "Robot Framework", level: levelOptions[1], currentlyLearning: true },
      { name: "Jenkins", level: levelOptions[1], currentlyLearning: true },
      { name: "Groovy", level: levelOptions[1], currentlyLearning: true },
      { name: "VS Code", level: levelOptions[4], currentlyLearning: false },
      { name: "Linux", level: levelOptions[3], currentlyLearning: false },
      { name: "Git", level: levelOptions[4], currentlyLearning: false },
    ],
  },
  experience: [
    {
      role: "L1 Integration Automation Trainee",
      company: "Nokia",
    }
  ],
  education: {
    degree: "Bachelor of Science in Computer Science",
    university: "University of Helsinki",
  },
  languageSkills: {
    Finnish: "Native language",
    English: "Fluent"
  },
  interests: ["Coding", "Reading", "Traveling", "Running", "Cooking"],
  iWantToExplore: [
    { name: "Go", interest: interestOptions[1] },
    { name: "Kotlin", interest: interestOptions[2] },
  ],
};
```
