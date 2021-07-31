### Hi there 👋

<!--
**henriquecrispim/henriquecrispim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently estudando
- 🌱 I’m currently learning

 <div>
  <a href="https://github.com/henriquecrispim">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=henriquecrispim&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=henriquecrispim&layout=compact&langs_count=7&theme=dracula"/>
</div>

nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * * / 12 * * * "
  workflow_dispatch :

empregos :
  construir :
    nome : Trabalhos para atualizar dados
    roda em : ubuntu-mais recente
    passos :
      # Animação de cobra
      - usa : Platane / snk @ master
        id : snake-gif
        com :
          github_user_name : rafaballerini
          svg_out_path : dist / github-Contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : output
          build_dir : dist
        env :
          GITHUB_TOKEN : $ {{secrets.GITHUB_TOKEN}}
