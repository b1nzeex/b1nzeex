<p align="center">
  <img src="https://cbeachx.me/static/media/cbeachx.5452f4b9.png" />
</p>

<h1 align="center">Hello, I'm Connor!</h1>

###### Programming / Scripting / Markdown Languages I Know...
<p float="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" width="50px" />
</p>

###### Databases I Know...
<p float="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="50px" />
  <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="50px" />
  <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" width="50px" />
</p>

###### Frameworks I Know...
<p float="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="50px" />
  <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" width="50px" />
</p>

###### Other Useful Things I Know...
<p float="left">
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="50px" />
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="50px" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="50px" />
  <img src="https://i.imgur.com/3HOIP2w.png" width="50px" />
</p>

### About Me!

```ts
import { Person } from "../Person";

export class ConnorBeach extends Person {
  public name: string;
  public age: number;
  public county: string;
  public hobbies: string[];

  public constructor() {
    this.name = "Connor Beach";
    this.age = 22;
    this.county = "Herefordshire, UK";
    this.hobbies = ["Programming", "Gaming", "Maintenance"];
    
    this.introduce();
  }
  
  private introduce() {
    return console.log(`Hello, my name is ${this.name}, I am ${this.age} years old and live in ${this.county}. My hobbies are ${this.hobbies.join(", ")}!`);
  }
}
```
