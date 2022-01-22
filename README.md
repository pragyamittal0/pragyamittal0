### Holaaaa!👋  I'm Pragya Mittal 
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=@pragyamittal0)](https://github.com/anuraghazra/github-readme-stats)
![Pragya's GitHub stats](https://github-readme-stats.vercel.app/api?username=pragyamittal0&show_icons=true&theme=dracula)
<!-- update -->
name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!--
**pragyamittal0/pragyamittal0** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
