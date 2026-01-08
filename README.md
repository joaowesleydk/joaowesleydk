/**
 * João Wesley Damas Kind
 * Software Developer in Progress
 */

const profile = {
  name: "João Wesley",
  role: "Student & Software Developer",
  location: "Brazil",
  focus: ["Web Development", "APIs", "Programming Logic"],
};

const stack = {
  languages: ["JavaScript", "Python"],
  frontend: ["React", "HTML", "CSS"],
  backend: ["Node.js", "FastAPI"],
  tools: ["Git", "GitHub", "VS Code"],
};

function currentStatus() {
  return {
    studying: "Full Stack Development",
    building: [
      "Web applications",
      "REST APIs",
      "Personal projects"
    ],
    goal: "Become a professional software developer",
  };
}

export default {
  profile,
  stack,
  currentStatus,
};
