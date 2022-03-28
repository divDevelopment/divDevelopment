### Hi there 👋

![Kayra's GitHub stats](https://github-readme-stats.vercel.app/api?username=divDevelopment)
![trophy](https://github-profile-trophy.vercel.app/?username=divDevelopment)
![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=divDevelopment&theme=shades-of-purple&date_format=j%20M%5B%20Y%5D)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.5180c9b9-bdae-4305-b82e-7b0876c5239a}}
          GH_TOKEN: ${{ secrets.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}}
<!--END_SECTION:waka-->
