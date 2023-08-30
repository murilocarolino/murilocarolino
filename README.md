## Olá pessoal 👋

Sou o **Murilo Carolino,** e estou no curso de _Desenvolvimento de Sistemas._

- 🔭 Estudo na instituição **SESI-SP**
- 🌱 Atualmente estou aprendendo a programar _Banco de Dados,_ _JavaScript_, _Programação Orientada a Objeto_ e _Java_.

<img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Firefox_logo%2C_2017.svg/800px-Firefox_logo%2C_2017.svg.png" width="40" height="40"/> <img loading="linux" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" height="40"/> 

## Contatos:

<div>
  <a href="https://www.instagram.com/https.mu/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/murilo-carolino-455b1228a/" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>

<div>
  <a href="https://github.com/murilocarolino">
  <img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?murilocarolino&layout=compact&langs_count=7&theme=dracula"/>
  <img loading="lazy" height="180em" src="https://github-readme-stats.vercel.app/api?murilocarolino&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
