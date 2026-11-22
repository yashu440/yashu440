<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,35:3D2F0A,60:D4AF37,100:0D0D0D&height=250&section=header&text=SAMPATHI%20YASWANTH&fontSize=46&fontColor=FFD700&animation=fadeIn&fontAlignY=38&desc=I%20don%27t%20play%20the%20game.%20I%20search%20the%20game%20tree.&descAlignY=58&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1100&color=FFD700&center=true&vCenter=true&width=780&lines=%24+.%2Fyaswanth+--uci;info+depth+12+score+cp+%2B340+pv+Minimax+AlphaBeta+GenAI;CSE+%40+Kalasalingam+Academy+(KARE);bestmove+ship_something_new" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/sampathi-yaswanth-a620ba37a/"><img src="https://img.shields.io/badge/LinkedIn-D4AF37?style=for-the-badge&logo=linkedin&logoColor=000"/></a>
<a href="mailto:yaswanthsampathi@gmail.com"><img src="https://img.shields.io/badge/Email-0D0D0D?style=for-the-badge&logo=gmail&logoColor=D4AF37"/></a>
<a href="https://www.instagram.com/_yashu.__07"><img src="https://img.shields.io/badge/Instagram-0D0D0D?style=for-the-badge&logo=instagram&logoColor=D4AF37"/></a>
<a href="https://yashuuuuuu.ai.studio"><img src="https://img.shields.io/badge/Live_Portfolio-FFD700?style=for-the-badge&logo=vercel&logoColor=000"/></a>
<img src="https://komarev.com/ghpvc/?username=yashu440&style=for-the-badge&color=D4AF37&labelColor=0D0D0D&abbreviated=true" alt="views"/>

</div>

<br/>

## > boot sequence

```text
$ ./yaswanth --uci

id name        Sampathi Yaswanth
id author      Kalasalingam Academy of Research and Education
option Role    type combo default "CSE student, AI/ML engineer-in-training"
option Search  type combo default "minimax + alpha-beta"
option Stack   type combo default "Python | Java | JavaScript | SQL"
option Peak    type string default "23:00 - 02:00"
option Fuel    type string default "coffee"
uciok

$ isready
readyok

$ go infinite
info string  building AI-integrated web apps
info string  sharpening ML fundamentals and competitive programming
info string  open to research, algorithmic collabs, AI engineering roles
```

<br/>

## > position on the board

```text
    a b c d e f g h
 8  r n b q k b n r     Opening book : Python, Java, DSA
 7  p p p p p p p p     Middlegame   : Search, ML, GenAI, Web
 6  . . . . . . . .     Endgame      : Applied ML research
 5  . . . . . . . .
 4  . . . . P . . .     Last move    : 1. e4  (new project started)
 3  . . . . . . . .     Evaluation   : +3.4  (and improving)
 2  P P P P . P P P
 1  R N B Q K B N R     Side to move : Yaswanth
```

<br/>

## > play a round

<div align="center">

<a href="https://yashu440.github.io/night-lane/"><img src="assets/night-lane.svg" alt="Night Lane: animated top-down driving game preview" width="100%"/></a>

<br/>

<a href="https://yashu440.github.io/night-lane/"><img src="https://img.shields.io/badge/PLAY_NIGHT_LANE-D4AF37?style=for-the-badge&logo=googlechrome&logoColor=000"/></a>
<a href="https://github.com/yashu440/night-lane"><img src="https://img.shields.io/badge/VIEW_SOURCE-0D0D0D?style=for-the-badge&logo=github&logoColor=D4AF37"/></a>

<sub>Arrow keys or A / D to steer. Dodge traffic, grab the gold. Works on phone too.</sub>

</div>

<br/>

## > featured projects

<table width="100%">
<tr>
<td width="33%" valign="top" align="center">

### Chess Engine

Move-evaluation engine built on **minimax with alpha-beta pruning**. Capture-first move ordering cuts the search space before it explodes.

`Python` `Game AI` `Algorithms`

![Stars](https://img.shields.io/github/stars/yashu440/chess-engine?style=flat-square&color=D4AF37&labelColor=0D0D0D)
![Last Commit](https://img.shields.io/github/last-commit/yashu440/chess-engine?style=flat-square&color=FFD700&labelColor=0D0D0D)

<a href="https://github.com/yashu440/chess-engine"><img src="https://img.shields.io/badge/OPEN_REPOSITORY-D4AF37?style=for-the-badge&logo=github&logoColor=000"/></a>

</td>
<td width="33%" valign="top" align="center">

### GenAI Learning Platform

A **Flask** platform where generative AI shapes personalized, adaptive learning paths for students.

`Flask` `Python` `GenAI`

![Stars](https://img.shields.io/github/stars/yashu440/genai-learning-platform?style=flat-square&color=D4AF37&labelColor=0D0D0D)
![Last Commit](https://img.shields.io/github/last-commit/yashu440/genai-learning-platform?style=flat-square&color=FFD700&labelColor=0D0D0D)

<a href="https://github.com/yashu440/genai-learning-platform"><img src="https://img.shields.io/badge/OPEN_REPOSITORY-D4AF37?style=for-the-badge&logo=github&logoColor=000"/></a>

</td>
<td width="33%" valign="top" align="center">

### Task Manager

Desktop productivity app with full **CRUD**, persistent local storage and a clean Tkinter interface.

`Python` `SQLite` `Tkinter`

![Stars](https://img.shields.io/github/stars/yashu440/task-manager?style=flat-square&color=D4AF37&labelColor=0D0D0D)
![Last Commit](https://img.shields.io/github/last-commit/yashu440/task-manager?style=flat-square&color=FFD700&labelColor=0D0D0D)

<a href="https://github.com/yashu440/task-manager"><img src="https://img.shields.io/badge/OPEN_REPOSITORY-D4AF37?style=for-the-badge&logo=github&logoColor=000"/></a>

</td>
</tr>
</table>

<details>
<summary><b>How the engine thinks (expand the search tree)</b></summary>

<br/>

```mermaid
flowchart TD
    A[Board State] --> B{Depth limit reached?}
    B -- Yes --> K[Static Evaluation]
    K --> L[Return Score]
    B -- No --> C[Generate Legal Moves]
    C --> D[Order Moves: captures first]
    D --> E[Minimax Recursion]
    E --> F{Maximizing?}
    F -- Yes --> G[Update Alpha]
    F -- No --> H[Update Beta]
    G --> I{Alpha >= Beta?}
    H --> I
    I -- Yes --> J[Prune Branch]
    I -- No --> B

    style A fill:#D4AF37,stroke:#FFD700,color:#000
    style J fill:#0D0D0D,stroke:#FFD700,color:#FFD700
    style L fill:#0D0D0D,stroke:#D4AF37,color:#D4AF37
```

</details>

<br/>

## > evaluation function

How I score my own skills, the same way the engine scores a position. Higher is better, and it keeps being re-searched.

<div align="center">

| Component | Weight | Depth searched |
|:---|:---:|:---|
| Python | 0.85 | AI, backend, scripting, tooling |
| Algorithms and Search | 0.75 | Minimax, pruning, DSA, competitive programming |
| Flask / Django | 0.75 | Full-stack web, REST APIs |
| Java | 0.70 | OOP, data structures |
| SQL | 0.70 | Relational design, queries |
| Machine Learning | 0.65 | Fundamentals, PyTorch, NumPy, Pandas |

<br/>

<img src="https://skillicons.dev/icons?i=python,java,js,html,css,pytorch,flask,django,nodejs,flutter,firebase,supabase,vercel,git,github&theme=dark" />

<br/><br/>

<img width="50%" src="https://quickchart.io/chart?c={type:'radar',data:{labels:['Python','ML','Algorithms','Flask%2FDjango','Java','SQL'],datasets:[{label:'Proficiency',data:[85,65,75,75,70,70],backgroundColor:'rgba(212,175,55,0.35)',borderColor:'%23D4AF37',pointBackgroundColor:'%23FFD700'}]},options:{plugins:{legend:{display:false}},scales:{r:{angleLines:{color:'%233a3a3a'},grid:{color:'%232a2a2a'},pointLabels:{color:'%23D4AF37',font:{size:12}},ticks:{display:false,max:100,min:0}}}},backgroundColor:'transparent'}" alt="Skill radar"/>

</div>

<br/>

## > telemetry

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=yashu440&hide_border=true&bg_color=00000000&title_color=D4AF37&icon_color=FFD700&text_color=C9D1D9&rank_icon=percentile" />
<img width="48%" src="https://nirzak-streak-stats.vercel.app/?user=yashu440&hide_border=true&background=00000000&ring=D4AF37&fire=FFD700&currStreakLabel=D4AF37&sideLabels=D4AF37&dates=8B8B8B" />

<br/>

<img width="55%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yashu440&hide_border=true&layout=compact&bg_color=00000000&title_color=D4AF37&text_color=C9D1D9" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=yashu440&bg_color=00000000&color=D4AF37&line=FFD700&point=D4AF37&hide_border=true&area=true&area_color=D4AF37" width="95%" />

</div>

<br/>

## > game record (PGN)

```text
[Event   "Career"]
[Site    "Kalasalingam Academy, India"]
[White   "Sampathi Yaswanth"]
[Black   "The Unknown"]
[Result  "*"]

1. Python Java        { foundations, DSA, first line of competitive programming }
2. Minimax AlphaBeta  { chess engine, search pruning that finally clicked }
3. Tkinter SQLite     { task manager, a full CRUD app end to end }
4. Flask GenAI        { learning platform, AI wired into a real web app }
5. Placements ...     { 2026, the position is being calculated }
6. ML Research ...    { deeper applied machine learning }
7. AI Engineer #      { checkmate, still ahead on the clock }
```

<br/>

## > make your move

<div align="center">

> *"The best way to learn is to build, break, and rebuild, better."*

<a href="https://www.linkedin.com/in/sampathi-yaswanth-a620ba37a/"><img src="https://img.shields.io/badge/LinkedIn-D4AF37?style=for-the-badge&logo=linkedin&logoColor=000"/></a>
<a href="mailto:yaswanthsampathi@gmail.com"><img src="https://img.shields.io/badge/Email-0D0D0D?style=for-the-badge&logo=gmail&logoColor=D4AF37"/></a>
<a href="https://github.com/yashu440"><img src="https://img.shields.io/badge/GitHub-D4AF37?style=for-the-badge&logo=github&logoColor=000"/></a>
<a href="https://yashuuuuuu.ai.studio"><img src="https://img.shields.io/badge/Portfolio-FFD700?style=for-the-badge&logo=vercel&logoColor=000"/></a>

<br/><br/>

<a href="https://www.buymeacoffee.com/yashu440"><img src="https://img.shields.io/badge/Buy_Me_a_Coffee-D4AF37?style=flat-square&logo=buymeacoffee&logoColor=000"/></a>
<a href="https://github.com/sponsors/yashu440"><img src="https://img.shields.io/badge/GitHub_Sponsors-0D0D0D?style=flat-square&logo=githubsponsors&logoColor=D4AF37"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,50:D4AF37,100:0D0D0D&height=110&section=footer" width="100%"/>

</div>
