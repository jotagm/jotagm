
```typescript
type Dev = {
  nome: string;
  cargo: string;
  stackPrincipal: string[];
  stackEmAprendizado: string[];
  interesses: string[];
};

class PerfilDev {
  constructor(private readonly desenvolvedor: Dev) {}

  mostrarPerfil() {
    const formatarLista = (itens: string[]) =>
      itens.map(item => `- ${item}`).join("\n");

    console.log(`
Nome: ${this.desenvolvedor.nome}
Cargo: ${this.desenvolvedor.cargo}

Stack Principal:
${formatarLista(this.desenvolvedor.stackPrincipal)}

Tecnologias em Aprendizado:
${formatarLista(this.desenvolvedor.stackEmAprendizado)}

Interesses:
${formatarLista(this.desenvolvedor.interesses)}
    `);
  }
}

const meuPerfil = new PerfilDev({
  nome: "João Pedro Machado",
  cargo: "Desenvolvedor Back-end",
  stackPrincipal: [
    "Java",
    "Spring Boot",
    "Microsserviços",
    "APIs REST",
    "PostgreSQL",
    "MySQL"
  ],
  stackEmAprendizado: [
    "Golang",
    "Desenvolvimento de CLI",
    "Estruturas de Dados e Algoritmos"
  ],
  interesses: [
    "Arquitetura de Software",
    "Sistemas Distribuídos",
    "Ferramentas para Desenvolvedores",
    "Aprender construindo projetos desafiadores"
  ]
});

meuPerfil.mostrarPerfil();

```
---

## **Contato:** jotadev4@gmail.com

---


## 🛠️ Tecnologias que utilizo

### **Linguagens**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### **Front-end**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### **Back-end & Banco de Dados**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### **Ferramentas**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## 🌐 Redes Sociais

<div align="center">
  <a href="https://www.linkedin.com/in/joão-pedro-machado-85714226a/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

---

<div align="center">
  <a href="https://github.com/jotagm" style="display: flex; justify-content: center; gap: 10px;">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=jotagm&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jotagm&layout=compact&langs_count=7&theme=dracula"/>
  </a>
</div>

---


