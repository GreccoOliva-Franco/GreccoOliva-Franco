# Welcome to my Github profile

### About me

```js
import { Dev } from "src/dev/index.ts";

const me: Dev = new Dev({
  fullname: "Grecco Oliva, Franco",
  education: [ "Mechanical engineer", "Backend (SSR)", "Frontend (JR)", "Cloud DevOps (Trainee)" ],
  codingSkills: {
    back: { 
      languages: [ "Javascript", "Typescript" ],
      frameworks: [ "Express.Js", "Nest.Js" ],
    },
    front: {
      frameworks: [ "React.Js" ]
    },
    databases: {
      relational: [ "MySQL" ],
      no_relational: [ "MongoDB" ],
    },
    testing: [
      {
        libraries: [ "Jest" ],
        languages: [ "Javascript", "Typescript" ],
      }
    ],
      
    dataAnalysis: {
      languages: [ "Python", "Matlab" ],
    },
  },
  tools: [ "Git", "Git Flow", "Github", "GitLab", "Postman" ],
  teamworkTools: [ "Jira" ],
  devOps: [ "AWS", "Azure", "Terraform", "Docker", "DockerComposer" ],
  residence: "Argentina",
  contact: { mail: "srgrecco93@gmail.com" }
})

me.addJob({
  company: "Repuestos Ya",
  description: "Full-time Backend Developer (SSR)",
  career: {
    start: "2021-12-01",
    end: undefined,
    currentlyWorking: true,
  },
})


// I ommited Dev definition
```

<br>

### Github stats

[![Franco's GitHub stats](https://github-readme-stats.vercel.app/api?username=GreccoOliva-Franco&count_private=true&show_icons=true&theme=monokai&hide_title=true&include_all_commits=true)](https://github.com/anuraghazra/github-readme-stats)

These stats are provided by [Anurag Hazra](https://github.com/anuraghazra/github-readme-stats#github-stats-card)
