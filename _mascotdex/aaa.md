---
title: aaa
image: 
description: Everything you need to know about Apathetic Andy
layout: mascot
permalink: /mascotdex/aaa/
comments: false
birth-year: 2021
mascot-type: Human
mascot-owner: REACH (Reaching Everyone for Active Citizenry @ Home)
mascot-cause: [Outreach]
mascot-creator: [Unknown]
mascot-status: Active
mascot-family:
---

<style>
  .mascot-details-table {
    margin: 20px 0;
    width: 100%;
    display: flex;
    justify-content: center;
  }

  .mascot-details-table table {
    width: 90%;
    max-width: 650px;
    border-collapse: collapse;
    background: #f9f9f9;
    border-radius: 10px;
    overflow: hidden;
  }

  .mascot-details-table th,
  .mascot-details-table td {
    padding: 12px 15px;
    text-align: left;
    border-bottom: 1px solid #ddd;
    cursor: default;
  }

  .mascot-details-table th {
    background: #005FEA;
    color: white;
    font-weight: bold;
    text-transform: uppercase;
    user-select: none;
    cursor: pointer;
  }

  .mascot-details-table td {
    color: #333;
  }

  .mascot-details-table tr:hover {
    background: #f1f1f1;
  }

  .mascot-details-table a {
    color: #005FEA;
    text-decoration: none;
    font-weight: bold;
  }

  .mascot-details-table a:hover {
    text-decoration: underline;
  }

  .sort-arrow {
    margin-left: 6px;
    font-size: 0.8em;
  }
</style>

<div class="mascot-details-table">
  <table id="mascotTable">
    <thead>
      <tr>
        <th onclick="sortTable(0)">Name<span class="sort-arrow" id="arrow0">▲</span></th>
        <th onclick="sortTable(1)">Birth Year<span class="sort-arrow" id="arrow1">▲</span></th>
        <th onclick="sortTable(2)">Type<span class="sort-arrow" id="arrow2">▲</span></th>
        <th onclick="sortTable(3)">Status<span class="sort-arrow" id="arrow3">▲</span></th>
        <th onclick="sortTable(4)">Owner<span class="sort-arrow" id="arrow4">▲</span></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/merlion/">Merlion</a></td>
        <td>1964</td>
        <td>Merlion</td>
        <td>Active</td>
        <td>Singapore Tourism Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/water-wally/">Water Wally</a></td>
        <td>2005</td>
        <td>Water Droplet</td>
        <td>Active</td>
        <td>PUB, Singapore’s National Water Agency</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/water-sally/">Water Sally</a></td>
        <td>2021</td>
        <td>Water Droplet</td>
        <td>Active</td>
        <td>PUB, Singapore’s National Water Agency</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/captain-green/">Captain Green</a></td>
        <td>1990</td>
        <td>Frog</td>
        <td>Active</td>
        <td>National Environment Agency</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/dino/">Dino</a></td>
        <td>2018</td>
        <td>Dinosaur</td>
        <td>Retired</td>
        <td>National Heritage Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/camy/">Camy</a></td>
        <td>2019</td>
        <td>Monster</td>
        <td>Active</td>
        <td>National Library Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/hutsy/">Hutsy</a></td>
        <td>2019</td>
        <td>Monster</td>
        <td>Active</td>
        <td>National Library Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/zecky/">Zecky</a></td>
        <td>2019</td>
        <td>Monster</td>
        <td>Active</td>
        <td>National Library Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/rooky/">Rooky</a></td>
        <td>2019</td>
        <td>Monster</td>
        <td>Active</td>
        <td>National Library Board</td>
      </tr>
      <tr>
        <td><a href="https://www.designinsingapore.com/mascotdex/phyll/">Phyll</a></td>
        <td>2022</td>
        <td>Leaf</td>
        <td>Active</td>
        <td>National Parks Board</td>
      </tr>
    </tbody>
  </table>
</div>

<script>
  const sortState = [true, true, true, true, true]; // true = ascending, false = descending

  function sortTable(colIndex) {
    const table = document.getElementById("mascotTable");
    const tbody = table.tBodies[0];
    const rows = Array.from(tbody.rows);
    const asc = sortState[colIndex];

    rows.sort((a, b) => {
      const valA = a.cells[colIndex].textContent.trim().toLowerCase();
      const valB = b.cells[colIndex].textContent.trim().toLowerCase();
      return asc ? valA.localeCompare(valB) : valB.localeCompare(valA);
    });

    rows.forEach(row => tbody.appendChild(row));
    sortState[colIndex] = !asc;

    // Update arrows
    for (let i = 0; i < 5; i++) {
      document.getElementById(`arrow${i}`).textContent = i === colIndex
        ? (sortState[colIndex] ? '▲' : '▼')
        : '▲';
    }
  }
</script>
