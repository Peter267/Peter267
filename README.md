![Hello World](https://github.com/user-attachments/assets/f3eb217e-8977-4dc4-9b0a-364f35fab4b8)

<h3 align="center">𝐇𝐞𝐥𝐥𝐨, 𝐟𝐞𝐥𝐥𝐨𝐰 <𝚌𝚘𝚍𝚎𝚛𝚜></𝚌𝚘𝚍𝚎𝚛𝚜>!

## 👋 Hi there! I'm Peter267
Students | Bloggers | Developers | UPmasters

Welcome to my blog!  [Click here](https://peter267.github.io)

[More about me ...](https://peter267.github.io/about/)

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

![MoeCounter](https://count.getloli.com/@peter267-profile?name=peter267-profile&theme=gelbooru&padding=7&offset=0&align=top&scale=1&pixelated=1&darkmode=auto)

[![Peter's GitHub stats](https://github-readme-stats.vercel.app/api?username=Peter267)](https://github.com/anuraghazra/github-readme-stats)
