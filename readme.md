# Project Simulator-MarioKart - Node.Js

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

### Description

<b><p align="justify">Welcome, this is a simple and fun project about Mario Kart, its objective is to test your knowledge about node.js and javascript, bringing some of the most used tools today such as async/await and project refactoring. </p></b>

### Instructions
> [!IMPORTANT]  
> Crucial information necessary for users to succeed.
> - Clone repository or download it
> - after opening the code in your IDE
> - You need to have the node installed on your computer
> - You can create other ways to get character information through imports or json-server

  <table>
        <tr>
            <td>
                <img src="./docs/header.gif" alt="Mario Kart" width="200">
            </td>
            <td>
                <b>Objective:</b>
                <p>Mario Kart is a series of racing games developed and published by Nintendo. Our challenge will be to create the logic of a video game to simulate Mario Kart racing, taking into account the rules and mechanics below.</p>
            </td>
        </tr>
    </table>

<h2>Players</h2>
      <table style="border-collapse: collapse; width: 800px; margin: 0 auto;">
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Mario</p>
                <img src="./docs/mario.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 4</p>
                <p>Manobrabilidade: 3</p>
                <p>Poder: 3</p>
            </td>
             <td style="border: 1px solid black; text-align: center;">
                <p>Peach</p>
                <img src="./docs/peach.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 2</p>
            </td>
              <td style="border: 1px solid black; text-align: center;">
                <p>Yoshi</p>
                <img src="./docs/yoshi.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 3</p>
            </td>
        </tr>
        <tr>
            <td style="border: 1px solid black; text-align: center;">
                <p>Bowser</p>
                <img src="./docs/bowser.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 5</p>
                <p>Manobrabilidade: 2</p>
                <p>Poder: 5</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Luigi</p>
                <img src="./docs/luigi.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 3</p>
                <p>Manobrabilidade: 4</p>
                <p>Poder: 4</p>
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Donkey Kong</p>
                <img src="./docs/dk.gif" alt="Mario Kart" width="60" height="60">
            </td>
            <td style="border: 1px solid black; text-align: center;">
                <p>Velocidade: 2</p>
                <p>Manobrabilidade: 2</p>
                <p>Poder: 5</p>
            </td>
        </tr>
    </table>

<p></p>

<h3>🕹️🚨 Rules & mechanics: 🕹️🚨</h3>

<b>Players:</b>

<input type="checkbox" id="jogadores-item" />
<label for="jogadores-item">The Console must receive two characters to compete in the race on one object each</label>

<b>Lane:</b>

<ul>
  <li><input type="checkbox" id="pistas-1-item" /> <label for="pistas-1-item">
Characters will race on a random track for 5 rounds</label></li>
  <li><input type="checkbox" id="pistas-2-item" /> <label for="pistas-2-item">In each round, a block of the track will be drawn, which can be a straight, curve or confrontation.</label>
    <ul>
      <li><input type="checkbox" id="pistas-2-1-item" /> <label for="pistas-2-1-item">
        If the track block is a STRAIGHT, the player must roll a 6-sided die and add the SPEED attribute, whoever wins gets a point.o</label></li>
      <li><input type="checkbox" id="pistas-2-2-item" /> <label for="pistas-2-2-item">If the track block is a CURVE, the player must roll a 6-sided die and add the MANEUVERABILITY attribute, whoever wins gets a point</label></li>
      <li><input type="checkbox" id="pistas-2-3-item" /> <label for="pistas-2-3-item">If the track block is a CONFRONTATION, the player must roll a 6-sided die and add the POWER attribute, whoever loses, loses a point</label></li>
      <li><input type="checkbox" id="pistas-2-3-item" /> <label for="pistas-2-3-item">No player can have a negative score (values ​​below 0)</label></li>
    </ul>
  </li>
</ul>

<b>Win condition:</b>

<input type="checkbox" id="vitoria-item" />
<label for="vitoria-item">In the end, whoever has accumulated the most points wins.</label>
