<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/brand/svg/tictactoe-logo-on-dark.svg">
    <img src="docs/brand/svg/tictactoe-logo-on-light.svg" alt="Tic-Tac-Toe" width="260">
  </picture>
</p>

<h1 align="center">Three in a row. Pure Java, no libraries.</h1>

<p align="center">
  An archived Java Swing game from 2019.<br>
  <b>Two players. One window. A prompt to play again.</b>
</p>

<p align="center">
  <img alt="Status: archived" src="https://img.shields.io/badge/status-archived-B5573A?style=flat-square">
  <a href="LICENSE"><img alt="License: GPL-3.0" src="https://img.shields.io/badge/license-GPL--3.0-3b82f6?style=flat-square"></a>
  <img alt="Java" src="https://img.shields.io/badge/Java-runtime-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="Two players" src="https://img.shields.io/badge/players-2-1E2A38?style=flat-square">
  <a href="https://github.com/mertkayacs/TicTacToe-Game-GUI"><img alt="GitHub stars" src="https://img.shields.io/github/stars/mertkayacs/TicTacToe-Game-GUI?style=flat-square&logo=github&color=C4A772"></a>
</p>

<p align="center">
  <a href="#quick-start"><img alt="Play it" src="https://img.shields.io/badge/Play%20it-B5573A?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIiBkPSJNNSA1YTIgMiAwIDAgMSAzLjAwOC0xLjcyOGwxMS45OTcgNi45OThhMiAyIDAgMCAxIC4wMDMgMy40NThsLTEyIDdBMiAyIDAgMCAxIDUgMTl6Ii8%2BPC9zdmc%2B&logoColor=white"></a>
  <a href="TicTacToeGame/src/main/java/com/mertilovski/app/Game.java"><img alt="Source" src="https://img.shields.io/badge/Source-1E2A38?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48ZyBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIj48cGF0aCBkPSJtMTYgMTggNi02LTYtNiIvPjxwYXRoIGQ9Im04IDYtNiA2IDYgNiIvPjwvZz48L3N2Zz4%3D&logoColor=white"></a>
  <a href="https://mertkayacs.com/?utm_source=github&utm_medium=readme&utm_campaign=TicTacToe-Game-GUI-repo&utm_content=portfolio-badge"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-1E2A38?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48ZyBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIvPjxwYXRoIGQ9Ik0xMiAyYTE0LjUgMTQuNSAwIDAgMCAwIDIwYTE0LjUgMTQuNSAwIDAgMCAwLTIwTTIgMTJoMjAiLz48L2c%2BPC9zdmc%2B&logoColor=white"></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/hero-dark.webp">
    <img src="docs/assets/readme/hero-light.webp" alt="A Java Swing window showing a finished Tic-Tac-Toe round with X and O in a three by three grid, titled &quot;Its a TIE&quot;" width="960">
  </picture>
</p>

Tic-Tac-Toe is a two-player game in core Java with a Swing window. The first click places an X, the next an O, and so on. When a round ends, a dialog announces the result and asks whether to play again. The repository includes a prebuilt jar and a Maven project.

---

## Why Tic-Tac-Toe

The game is one source file and runs from a single jar.

|  |  |
|---|---|
| <img src="docs/assets/readme/icons/package.svg" width="18" height="18" alt=""> **No libraries** | The game is core Java and Swing. All of it lives in [Game.java](TicTacToeGame/src/main/java/com/mertilovski/app/Game.java). |
| <img src="docs/assets/readme/icons/play.svg" width="18" height="18" alt=""> **Run without building** | The committed jar starts the game with one command. Maven is only needed to build from source. |
| <img src="docs/assets/readme/icons/repeat.svg" width="18" height="18" alt=""> **Replay prompt** | When a round ends, a dialog asks whether to play again. The first launch also shows a short How To Play dialog. |

## A quick tour

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/howto-dark.webp">
        <img src="docs/assets/readme/tour/howto-light.webp" alt="The How To Play dialog above an empty Tic-Tac-Toe board">
      </picture>
      <h3>How to play</h3>
      The dialog shown at the first launch, over the empty board.
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/midgame-dark.webp">
        <img src="docs/assets/readme/tour/midgame-light.webp" alt="A Tic-Tac-Toe board with two X and two O placed">
      </picture>
      <h3>Mid-game</h3>
      X and O take turns on the same board, X first.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/win-dark.webp">
        <img src="docs/assets/readme/tour/win-light.webp" alt="The dialog &quot;X is the Winner!&quot; asking whether to play again, over a board with a row of X">
      </picture>
      <h3>A win</h3>
      A dialog names the winner and asks whether to play again.
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="docs/assets/readme/tour/tie-dark.webp">
        <img src="docs/assets/readme/tour/tie-light.webp" alt="The dialog &quot;Its a TIE&quot; asking whether to play again, over a full board">
      </picture>
      <h3>A tie</h3>
      A full board without a line ends in a tie, with the same replay prompt.
    </td>
  </tr>
</table>

<p align="center"><sub>Captured from the running game on a virtual display. The window frames are drawn by Swing because that display has no window manager.</sub></p>

## Features

**Gameplay**

- Two players take turns on the same screen, X first.
- A dialog names the result and offers another round.

**Project**

- Maven pom with the exec plugin set to the game class.
- A prebuilt jar and a Windows executable in src/main/executable.

## Quick start

```sh
java -jar TicTacToeGame/src/main/executable/TTTGame.jar
```

To build and run from source with Maven:

```sh
cd TicTacToeGame
mvn exec:java
```

### Requirements

- A Java runtime. The pom does not pin a version.
- Maven, only for building from source.

## FAQ

<details>
<summary><b>Is there a computer opponent?</b></summary>

No. Two players share one screen and the turn counter alternates X and O.
</details>

<details>
<summary><b>Do I need Maven?</b></summary>

No. The committed jar runs with java -jar.
</details>

<details>
<summary><b>Which Java version do I need?</b></summary>

Any Java runtime that can run the jar. The pom does not pin a version.
</details>

If Tic-Tac-Toe is useful to you, a ⭐ helps other people find it.

## License

[GPL-3.0](LICENSE). Photos behind the screenshots are credited in [docs/assets/readme/CREDITS.md](docs/assets/readme/CREDITS.md).

[![views](https://hits.sh/github.com/mertkayacs/TicTacToe-Game-GUI.svg?view=today-total&style=flat-square&label=views&color=B5573A&labelColor=1E2A38)](https://github.com/mertkayacs/TicTacToe-Game-GUI)
