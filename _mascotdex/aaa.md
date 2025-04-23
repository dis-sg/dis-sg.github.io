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
    body {
      font-family: Arial, sans-serif;
    }

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
    }

    select {
      width: 100%;
      padding: 4px;
    }

    a {
      color: #0066cc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
  <script>
    function filterTable(columnIndex) {
      const select = document.getElementById("filter-" + columnIndex);
      const filter = select.value.toLowerCase();
      const table = document.getElementById("mascotTable");
      const tr = table.getElementsByTagName("tr");

      for (let i = 2; i < tr.length; i++) {
        const td = tr[i].getElementsByTagName("td")[columnIndex];
        if (td) {
          const txtValue = td.textContent || td.innerText;
          tr[i].style.display = (filter === "all" || txtValue.toLowerCase() === filter) ? "" : "none";
        }
      }
    }
  </script>
</head>
<body>

<table id="mascotTable">
  <thead>
    <tr>
      <th>Name</th>
      <th>Birth Year</th>
      <th>Type</th>
      <th>Cause</th>
      <th>Status</th>
      <th>Mascot Family</th>
      <th>Owner</th>
    </tr>
    <tr>
      <th>
        <select id="filter-0" onchange="filterTable(0)">
          <option value="all">All</option>
          <option value="Merlion">Merlion</option>
          <option value="Water Wally">Water Wally</option>
          <option value="Water Sally">Water Sally</option>
          <option value="Captain Green">Captain Green</option>
          <option value="Dino">Dino</option>
          <option value="Camy">Camy</option>
          <option value="Hutsy">Hutsy</option>
          <option value="Zecky">Zecky</option>
          <option value="Rooky">Rooky</option>
          <option value="Phyll">Phyll</option>
        </select>
      </th>
      <th>
        <select id="filter-1" onchange="filterTable(1)">
          <option value="all">All</option>
          <option value="1964">1964</option>
