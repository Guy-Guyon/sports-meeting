# Routes sport's meeting

| URL              | HTTPMethod | Controller         | Method | Name     | Content                       | Comment                |
| ---------------- | ---------- | ------------------ | ------ | -------- | ----------------------------- | ---------------------- |
| /home            | GET        | HomeController     | read   | home     | Displayed the home page       | No connextion required |
| /register        | GET / POST | RegisterController | create | register | Displayed the register page   | No connection required |
| /research        | GET        | MainController     | read   | research | Displayed the research        | connection required    |
| /plan-site       | GET        | MainController     | read   | plan     | Displayed the site map        | No connection required |
| /mention-légales | GET        | MainController     | read   | mention  | Displayed the Legals mentions | No connexion required  |
| /contact         | GET        | MainController     | read   | contact  | Contact a manager             | No connection required |
