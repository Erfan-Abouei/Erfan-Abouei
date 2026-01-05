
```typescript
type User = {
  name: string;
  role: string;
  skills: string[];
  summary(): string;
};

const user: User = {
  name: "Erfan Abouei",
  role: "Backend Developer",
  skills: ["Node.js", "TypeScript", "Express", "NestJS", "PostgreSQL", "Redis", "..."],

  summary() {
    return `${this.name} — ${this.role}\nSkills: ${this.skills.join(", ")}`;
  }
};

console.log(user.summary());
```

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=javascript,typescript,nodejs,expressjs,nestjs,linux,docker,nginx,mysql,postgres,redis,sequelize,prisma,jest,postman"/>
  </a>
</div>

---

<div align="center">
    <img src="https://profile-readme-generator.com/assets/pacman.svg" style="width: 100%;">
</div>

---

<div align="center">
I started working with computers at an early age, which led me to pursue backend development. I focus on understanding systems, writing reliable code, and continuously improving—because in backend engineering, learning never stops.
</div>
