### Olá eu sou Filipe Morais👋

<!--
**filipemorais78/Filipemorais78** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 Trabalho com Front-end / Designer
- 🌱 front end
- 😄 Ele/Dele

nome : Gerar Dados

em :
  schedule : # executa a cada 12 horas
-cron     : " * */12 * * * "
  workflow_dispatch :

empregos :
  construir :
    name : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : rafaballerini
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ secrets.GITHUB_TOKEN }}
