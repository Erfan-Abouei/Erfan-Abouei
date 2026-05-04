
```typescript
type User = {
  name: string;
  role: string;
  focus: string[];
  summary(): string;
};

const user: User = {
  name: "Erfan Abouei",
  role: "CEO @ Kara | 17",
  focus: [
    "Backend Architecture", 
    "Clean Code", 
    "System Design"
  ],
  summary() {
    return `${this.name} — ${this.role}\nFocus: ${this.focus.join(" • ")}`;
  }
};

console.log(user.summary());
```

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=typescript,nodejs,expressjs,nestjs,linux,docker,nginx,rabbitmq,kafka,mysql,postgres,redis,sequelize,prisma,jest"/>
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
