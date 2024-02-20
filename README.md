name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## Olá! eu sou Wanderson Martins 👋

![Wanderson GitHub stats](https://github-readme-stats.vercel.app/api?username=Wanderson-Martins&show_icons=true&theme=radical)

### Tecnologia Usandas

<div style="display: inline_block"></br>
<img align="center" alt="python" src= "https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
<img align="center" alt="python" src= "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
<img align="center" alt="python" src= "https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</div></br>

### Estudent Science Computer


