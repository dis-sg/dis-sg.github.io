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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mascotdex Table</title>
  <style>
    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 1em;
    }

    th, td {
      border: 1px solid #ccc;
      text-align: left;
      padding: 8px;
    }

    th {
      background-color: #f4f4f4;
      cursor: pointer;
    }

    a {
      color: #0066cc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<table id="mascotTable">
  <thead>
    <tr>
      <th onclick="sortTable(0)">Name</th>
      <th onclick="sortTable(1)">Birth Year</th>
      <th onclick="sortTable(2)">Type</th>
      <th onclick="sortTable(3)">Cause</th>
      <th onclick="sortTable(4)">Status</th>
      <th onclick="sortTable(5)">Mascot Family</th>
      <th onclick="sortTable(6)">Owner</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/merlion/">Merlion</a></td>
      <td>1964</td>
      <td>Merlion</td>
      <td>Tourism</td>
      <td>Active</td>
      <td>-</td>
      <td>Singapore Tourism Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/water-wally/">Water Wally</a></td>
      <td>2005</td>
      <td>Water Droplet</td>
      <td>Environment</td>
      <td>Active</td>
      <td>-</td>
      <td>PUB, Singapore’s National Water Agency</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/water-sally/">Water Sally</a></td>
      <td>2021</td>
      <td>Water Droplet</td>
      <td>Environment</td>
      <td>Active</td>
      <td>-</td>
      <td>PUB, Singapore’s National Water Agency</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/captain-green/">Captain Green</a></td>
      <td>1990</td>
      <td>Frog</td>
      <td>Environment</td>
      <td>Active</td>
      <td>-</td>
      <td>National Environment Agency</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/dino/">Dino</a></td>
      <td>2018</td>
      <td>Dinosaur</td>
      <td>Culture</td>
      <td>Retired</td>
      <td>-</td>
      <td>National Heritage Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/camy/">Camy</a></td>
      <td>2019</td>
      <td>Monster</td>
      <td>Education, Children</td>
      <td>Active</td>
      <td>Monsters United</td>
      <td>National Library Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/hutsy/">Hutsy</a></td>
      <td>2019</td>
      <td>Monster</td>
      <td>Education, Children</td>
      <td>Active</td>
      <td>Monsters United</td>
      <td>National Library Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/zecky/">Zecky</a></td>
      <td>2019</td>
      <td>Monster</td>
      <td>Education, Children</td>
      <td>Active</td>
      <td>Monsters United</td>
      <td>National Library Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/rooky/">Rooky</a></td>
      <td>2019</td>
      <td>Monster</td>
      <td>Education, Children</td>
      <td>Active</td>
      <td>Monsters United</td>
      <td>National Library Board</td>
    </tr>
    <tr>
      <td><a href="https://www.designinsingapore.com/mascotdex/phyll/">Phyll</a></td>
      <td>2022</td>
      <td>Leaf</td>
      <td>Environment</td>
      <td>Active</td>
      <td>-</td>
      <td>National Parks Board</td>
    </tr>
  </tbody>
</table>

<script>
  let sortDirection = true;

  function sortTable(columnIndex) {
    const table = document.getElementById("mascotTable");
    const rows = Array.from(table.rows).slice(1); // Exclude header
    sortDirection = !sortDirection;

    rows.sort((a, b) => {
      const cellA = a.cells[columnIndex].textContent.trim().toLowerCase();
      const cellB = b.cells[columnIndex].textContent.trim().toLowerCase();

      if (!isNaN(cellA) && !isNaN(cellB)) {
        return sortDirection ? cellA - cellB : cellB - cellA;
      } else {
        return sortDirection ? cellA.localeCompare(cellB) : cellB.localeCompare(cellA);
      }
    });

    for (const row of rows) {
      table.tBodies[0].appendChild(row);
    }
  }
</script>

</body>
</html>
