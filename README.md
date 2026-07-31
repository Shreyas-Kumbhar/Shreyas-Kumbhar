<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:4c1d95&height=200&section=header&text=Shreyas%20Kumbhar&fontSize=52&fontAlignY=38&fontColor=ffffff&desc=Java%20Backend%20Engineer&descAlignY=58&descAlign=50&descSize=20&animation=fadeIn" width="100%" alt="header" />

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-0f172a?style=flat-square&logo=vercel&logoColor=white)](https://shreyas-kumbhar.github.io/Personal-Portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shreyas-Kumbhar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/placeholder)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/ShreyasKumbhar09/)
[![Email](https://img.shields.io/badge/Email-4c1d95?style=flat-square&logo=gmail&logoColor=white)](mailto:shreyas.kumbhar@example.com)

</div>

<br>

## About

I build backend systems in **Java and Spring Boot** — REST APIs, authentication layers, and data models designed to hold up under real traffic and real edge cases, not just pass a demo.

My day-to-day centers on **Spring Security, Hibernate/JPA, and MySQL**, with a parallel focus on **Data Structures & Algorithms** and **System Design** — the fundamentals that inform every architecture decision above the framework level. I'm currently extending that into **microservices and cloud deployment**.

**Currently open to full-time Software Engineering roles** focused on backend systems.

<br>

## Tech Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=java,mysql,html,css" height="45" alt="languages" />

**Backend & Frameworks**
<br>
<img src="https://skillicons.dev/icons?i=spring,hibernate" height="45" alt="backend" />

**Security & Auth**
<br>
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Tools & DevOps**
<br>
<img src="https://skillicons.dev/icons?i=git,github,docker,postman,idea,maven" height="45" alt="tools" />

**Currently Learning**
<br>
![Microservices](https://img.shields.io/badge/Microservices-1e3a8a?style=flat-square)
![System Design](https://img.shields.io/badge/System_Design-1e3a8a?style=flat-square)
![Cloud](https://img.shields.io/badge/Cloud-1e3a8a?style=flat-square)
![Advanced DSA](https://img.shields.io/badge/Advanced_DSA-1e3a8a?style=flat-square)

<br>

## Featured Projects

<br>

**🏥 Hospital Management System**
Backend platform for managing hospital resources, patient records, and doctor workflows, with role-based access control.
`Java` `Spring Boot` `Spring Security` `Hibernate` `MySQL`
[Repository →](https://github.com/Shreyas-Kumbhar/Hospital-Management-System.git)

---

**🎓 Student Management System**
Secure student records and grading platform with JWT-based authentication and stateless session handling.
`Java` `Spring Boot` `JPA` `MySQL` `JWT`
[Repository →](https://github.com/Shreyas-Kumbhar/student-mngt.git)

---

**🛡️ Insurance Policy Optimizer**
Algorithmic engine that scores and recommends insurance policies based on customer profile inputs.
`Core Java` `Data Structures` `Algorithms`
[Repository →](https://github.com/Shreyas-Kumbhar/InsurancePolicyOptimizer.git)

---

**🌐 Personal Portfolio**
Static portfolio site showcasing projects, background, and resume.
`HTML` `CSS` `GitHub Pages`
[Live Site →](https://shreyas-kumbhar.github.io/Personal-Portfolio/)

<br>

## GitHub Overview

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shreyas-kumbhar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shreyas-kumbhar&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />

<br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shreyas-kumbhar&theme=tokyo-night&hide_border=true" width="97%" alt="Activity Graph" />

</div>

<br>

## Developer Snapshot

```java
public final class Engineer {

    private final String name;
    private final String role;
    private final Set<String> coreStack;
    private final Set<String> currentlyLearning;
    private final Status status;

    public enum Status {
        OPEN_TO_FULL_TIME_ROLES
    }

    private Engineer(Builder builder) {
        this.name = builder.name;
        this.role = builder.role;
        this.coreStack = Set.copyOf(builder.coreStack);
        this.currentlyLearning = Set.copyOf(builder.currentlyLearning);
        this.status = builder.status;
    }

    public static Builder builder() {
        return new Builder();
    }

    public static final class Builder {
        private String name;
        private String role;
        private Set<String> coreStack = new HashSet<>();
        private Set<String> currentlyLearning = new HashSet<>();
        private Status status;

        public Builder name(String name) { this.name = name; return this; }
        public Builder role(String role) { this.role = role; return this; }
        public Builder coreStack(Set<String> stack) { this.coreStack = stack; return this; }
        public Builder currentlyLearning(Set<String> stack) { this.currentlyLearning = stack; return this; }
        public Builder status(Status status) { this.status = status; return this; }
        public Engineer build() { return new Engineer(this); }
    }
}

Engineer shreyas = Engineer.builder()
    .name("Shreyas Kumbhar")
    .role("Java Backend Engineer")
    .coreStack(Set.of("Java", "Spring Boot", "Spring Security", "Hibernate", "MySQL"))
    .currentlyLearning(Set.of("Microservices", "System Design", "Cloud"))
    .status(Engineer.Status.OPEN_TO_FULL_TIME_ROLES)
    .build();
```

<br>

## Profile Metrics

<div align="center">

![Views](https://komarev.com/ghpvc/?username=shreyas-kumbhar&label=Profile+Views&color=4c1d95&style=flat-square)
![Followers](https://img.shields.io/github/followers/shreyas-kumbhar?label=Followers&style=flat-square&color=1e3a8a)
![Stars](https://img.shields.io/github/stars/shreyas-kumbhar?affiliations=OWNER&label=Stars&style=flat-square&color=0f172a)
![Repos](https://img.shields.io/github/repos/shreyas-kumbhar?label=Repositories&style=flat-square&color=4c1d95)

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,100:0f172a&height=100&section=footer" width="100%" alt="footer" />

</div>