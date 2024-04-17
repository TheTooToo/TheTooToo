### Hi there 👋

<!--
**TheTooToo/TheTooToo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<h2> 🚀 &nbsp;Some Tools I Have Used and Learned</h2>
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="bash" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="php" width="45" height="45"/>
</p>
<svg viewBox="-16 -32 48 96" width="48" height="96" xmlns="http://www.w3.org/2000/svg"><desc>Generated with https://github.com/Platane/snk</desc><style>@keyframes s0{0%{transform:translate(0,-16px)}}@keyframes s1{0%{transform:translate(16px,-16px)}}@keyframes s2{0%{transform:translate(32px,-16px)}}@keyframes s3{0%{transform:translate(48px,-16px)}}:root{--cb:#1b1f230a;--cs:purple;--ce:#ebedf0;--c0:#ebedf0;--c1:#9be9a8;--c2:#40c463;--c3:#30a14e;--c4:#216e39}@media (prefers-color-scheme:dark){:root{--cb:#1b1f230a;--cs:purple;--ce:#161b22;--c1:#01311f;--c2:#034525;--c3:#0f6d31;--c4:#00c647}}.c{shape-rendering:geometricPrecision;fill:var(--ce);stroke-width:1px;stroke:var(--cb);animation:none 100ms linear infinite}.s,.u{animation:none linear 100ms infinite}.u{transform-origin:0 0;transform:scale(0,1)}.s{shape-rendering:geometricPrecision;fill:var(--cs)}.s.s0{transform:translate(0,-16px);animation-name:s0}.s.s1{transform:translate(16px,-16px);animation-name:s1}.s.s2{transform:translate(32px,-16px);animation-name:s2}.s.s3{transform:translate(48px,-16px);animation-name:s3}</style><rect class="s s0" x="0.8" y="0.8" width="14.4" height="14.4" rx="4.5" ry="4.5"/><rect class="s s1" x="1.8" y="1.8" width="12.3" height="12.3" rx="4.1" ry="4.1"/><rect class="s s2" x="2.6" y="2.6" width="10.8" height="10.8" rx="3.6" ry="3.6"/><rect class="s s3" x="3.0" y="3.0" width="9.9" height="9.9" rx="3.3" ry="3.3"/></svg>
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

         
          
  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
