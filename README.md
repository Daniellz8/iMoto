# iMotos

Um projeto apaixonante e divertido para entusiastas de motocicletas, desenvolvido para explorar e aprimorar conhecimentos em desenvolvimento web com HTML, CSS e JavaScript.

## Visão Geral do Projeto

`iMotos` é uma página web dedicada ao universo das duas rodas. O objetivo principal deste projeto é criar uma plataforma visualmente atraente e interativa, servindo como um espaço para compartilhar informações sobre diferentes tipos de motos, marcas icônicas, história e dicas para motociclistas.

Este projeto não é apenas uma vitrine para motos, mas também uma vitrine de aprendizado. Ele será construído de forma gradual, permitindo a aplicação prática de conceitos de front-end (HTML, CSS, JavaScript) e explorando, no futuro, aspectos de desenvolvimento Full-Stack.

## Tecnologias Utilizadas (Até o momento)

* **HTML5:** Para a estrutura e conteúdo da página.
* **CSS3:** Para a estilização e design responsivo.
* **JavaScript:** Para adicionar interatividade e funcionalidades dinâmicas.

## Estrutura de Pastas (Padrão de Organização)

Nossa estrutura de pastas segue uma abordagem limpa e funcional, sem enumeração numérica, priorizando nomes descritivos em `camelCase` (para JavaScript) e `kebab-case` (para HTML/CSS, quando aplicável) para maior clareza e manutenibilidade.


iMotos/
├── public/
│   ├── index.html
│   ├── assets/
│   │   ├── images/
│   │   ├── css/
│   │   │   └── main.css
│   │   └── js/
│   │       └── main.js
├── README.md
├── .gitignore
├── LICENSE
└── ... (outras pastas futuras como docs/, src/components/, etc.)

* `public/`: Contém os arquivos que serão servidos diretamente no navegador.
    * `index.html`: O arquivo principal da sua página.
    * `assets/`: Para todos os recursos estáticos.
        * `images/`: Imagens do projeto.
        * `css/`: Arquivos CSS.
            * `main.css`: O arquivo CSS principal.
        * `js/`: Arquivos JavaScript.
            * `main.js`: O arquivo JavaScript principal.

## Como Executar o Projeto Localmente (via Termux)

Para visualizar e trabalhar no projeto `iMotos` no seu dispositivo Android usando o Termux:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SeuUsuario/iMotos.git](https://github.com/SeuUsuario/iMotos.git)
    ```
    *Substitua `SeuUsuario` pelo seu nome de usuário do GitHub.*
    *Lembre-se de que, ao clonar, você precisará usar um Personal Access Token (PAT) como senha, devido às políticas de segurança do GitHub.*

2.  **Navegue para a pasta do projeto:**
    ```bash
    cd iMotos
    ```

3.  **Abra o arquivo HTML:** Como se trata de um projeto front-end estático, você pode simplesmente abrir o arquivo `public/index.html` em qualquer navegador do seu dispositivo.

    *Você também pode configurar um servidor HTTP simples no Termux (ex: `pkg install python && python -m http.server`) na pasta `public` para acessá-lo via `localhost`.*

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---
