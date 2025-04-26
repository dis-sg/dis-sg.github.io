---
title: bbb
image: 
description: Everything you need to know about Apathetic Andy
layout: mascot
permalink: /mascotdex/b/
comments: false
birth-year: <a href="www.google.com" target="_blank">test</a>
mascot-type: <a href="www.google.com" target="_blank">test</a>
mascot-owner: <a href="www.google.com" target="_blank">test</a>
mascot-cause: [<a href="www.google.com" target="_blank">test</a>]
mascot-creator: <a href="www.google.com" target="_blank">test</a>
mascot-status: <a href="www.google.com" target="_blank">test</a>
mascot-family:
---



<!-- 1960s -->
<div class="mascot-details-table">
  <table id="mascotTable1960s">
    <thead>
      <tr>
        <th style="text-align: center;" onclick="sortTable1960s(0)">Name<span class="sort-arrow" id="arrow1960s0">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1960s(1)">Birth Year<span class="sort-arrow" id="arrow1960s1">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1960s(2)">Status<span class="sort-arrow" id="arrow1960s2">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1960s(3)">Owner<span class="sort-arrow" id="arrow1960s3">▲</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Jx9TK5n.png" alt="Merlion Thumbnail" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/merlion/">Merlion</a></div></td>
        <td>1964</td>
        <td>Active</td>
        <td>Singapore Tourism Board</td>
      </tr>
    </tbody>
  </table>
</div>

<script>
const sortState1960s = [true, true, true, true];
function sortTable1960s(colIndex) {
  const table = document.getElementById("mascotTable1960s");
  const tbody = table.tBodies[0];
  const rows = Array.from(tbody.rows);
  const asc = sortState1960s[colIndex];
  rows.sort((a, b) => {
    let valA, valB;
    if (colIndex === 0) {
      const nameA = a.querySelector('a').textContent.trim().toLowerCase();
      const nameB = b.querySelector('a').textContent.trim().toLowerCase();
      return asc ? nameA.localeCompare(nameB) : nameB.localeCompare(nameA);
    } else {
      valA = a.cells[colIndex].textContent.trim().toLowerCase();
      valB = b.cells[colIndex].textContent.trim().toLowerCase();
      return asc ? valA.localeCompare(valB) : valB.localeCompare(valA);
    }
  });
  rows.forEach(row => tbody.appendChild(row));
  sortState1960s[colIndex] = !asc;
  for (let i = 0; i < 4; i++) {
    document.getElementById(`arrow1960s${i}`).textContent = i === colIndex ? (sortState1960s[i] ? '▲' : '▼') : '▲';
  }
}
</script>

<!-- 1970s -->
<div class="mascot-details-table">
  <table id="mascotTable1970s">
    <thead>
      <tr>
        <th style="text-align: center;" onclick="sortTable1970s(0)">Name<span class="sort-arrow" id="arrow1970s0">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1970s(1)">Birth Year<span class="sort-arrow" id="arrow1970s1">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1970s(2)">Status<span class="sort-arrow" id="arrow1970s2">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1970s(3)">Owner<span class="sort-arrow" id="arrow1970s3">▲</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/bl7wqjS.png" alt="Bobo Thumbnail" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/bobo/">Bobo</a></div></td>
        <td>1973</td>
        <td>Retired</td>
        <td>Public Utilities Board</td>
      </tr>
    </tbody>
  </table>
</div>

<script>
const sortState1970s = [true, true, true, true];
function sortTable1970s(colIndex) {
  const table = document.getElementById("mascotTable1970s");
  const tbody = table.tBodies[0];
  const rows = Array.from(tbody.rows);
  const asc = sortState1970s[colIndex];
  rows.sort((a, b) => {
    let valA, valB;
    if (colIndex === 0) {
      const nameA = a.querySelector('a').textContent.trim().toLowerCase();
      const nameB = b.querySelector('a').textContent.trim().toLowerCase();
      return asc ? nameA.localeCompare(nameB) : nameB.localeCompare(nameA);
    } else {
      valA = a.cells[colIndex].textContent.trim().toLowerCase();
      valB = b.cells[colIndex].textContent.trim().toLowerCase();
      return asc ? valA.localeCompare(valB) : valB.localeCompare(valA);
    }
  });
  rows.forEach(row => tbody.appendChild(row));
  sortState1970s[colIndex] = !asc;
  for (let i = 0; i < 4; i++) {
    document.getElementById(`arrow1970s${i}`).textContent = i === colIndex ? (sortState1970s[i] ? '▲' : '▼') : '▲';
  }
}
</script>



<!-- 1980s -->
<div class="mascot-details-table">
  <table id="mascotTable1980s">
    <thead>
      <tr>
        <th style="text-align: center;" onclick="sortTable1980s(0)">Name<span class="sort-arrow" id="arrow1980s0">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1980s(1)">Birth Year<span class="sort-arrow" id="arrow1980s1">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1980s(2)">Status<span class="sort-arrow" id="arrow1980s2">▲</span></th>
        <th style="text-align: center;" onclick="sortTable1980s(3)">Owner<span class="sort-arrow" id="arrow1980s3">▲</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/MICOS.png" alt="MICOS Thumbnail" class="thumbnail-name"><a href="#">MICOS</a></div></td>
        <td>1982</td>
        <td>Retired</td>
        <td>Good Neighbour Campaign</td>
      </tr>
    </tbody>
  </table>
</div>

<script>
const sortState1980s = [true, true, true, true];
function sortTable1980s(colIndex) {
  const table = document.getElementById("mascotTable1980s");
  const tbody = table.tBodies[0];
  const rows = Array.from(tbody.rows);
  const asc = sortState1980s[colIndex];
  rows.sort((a, b) => {
    let valA, valB;
    if (colIndex === 0) {
      const nameA = a.querySelector('a').textContent.trim().toLowerCase();
      const nameB = b.querySelector('a').textContent.trim().toLowerCase();
      return asc ? nameA.localeCompare(nameB) : nameB.localeCompare(nameA);
    } else {
      valA = a.cells[colIndex].textContent.trim().toLowerCase();
      valB = b.cells[colIndex].textContent.trim().toLowerCase();
      return asc ? valA.localeCompare(valB) : valB.localeCompare(valA);
    }
  });
  rows.forEach(row => tbody.appendChild(row));
  sortState1980s[colIndex] = !asc;
  for (let i = 0; i < 4; i++) {
    document.getElementById(`arrow1980s${i}`).textContent = i === colIndex ? (sortState1980s[i] ? '▲' : '▼') : '▲';
  }
}
</script>

<!-- Similar blocks would continue for 1990s, 2000s, 2010s, 2020s -->

