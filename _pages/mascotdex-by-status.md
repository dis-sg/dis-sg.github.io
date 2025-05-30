---
layout: page 
title: "Mascotdex: Singapore's Mascots by Status"
image: https://i.imgur.com/JrRjUog.png
permalink: /mascotdex-by-status/
comments: false
description: Mascotdex is the definitive repository of Singapore's mascots
published: false
---
<head> 
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

  .mascot-details-table {
    margin: 20px 0;
    width: 100%;
    overflow-x: auto; /* Enable horizontal scrolling */
    -webkit-overflow-scrolling: touch; /* Smooth scrolling on iOS */
  }

  .table-wrapper {
    display: block; /* Ensure proper block-level layout */
    width: 100%; /* Full width for responsiveness */
    max-width: none; /* Remove artificial width restrictions */
    background: #f9f9f9;
    border-radius: 10px;
    overflow: hidden; /* Prevent content overflow */
  }

  .table-wrapper table {
    border-collapse: collapse;
    white-space: nowrap; /* Prevent wrapping */
    width: 100%; /* Ensure table fits container */
    max-width: none; /* Remove width restrictions */
  }

  .mascot-details-table th,
  .mascot-details-table td {
    padding: 12px 15px;
    text-align: left;
    border-bottom: 1px solid #ddd;
    color: #333;
  }

  .mascot-details-table th {
    background: #005FEA;
    color: white;
    font-weight: bold;
    text-transform: uppercase;
    text-align: center;
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

  .thumbnail-name-container {
    display: flex;
    align-items: center; /* Align thumbnail and name */
  }

  .thumbnail-name {
    width: 70px;
    height: 70px;
    object-fit: contain;
    margin-right: 10px;
  }



    
tbody td:nth-child(1) {
    display: block !important;
    overflow: hidden !important;
    white-space: normal !important;
}
tbody td:nth-child(1) .thumbnail-name-container {
    display: flex !important;
    align-items: center !important;
    width: 100% !important;
    height: auto !important;
    overflow: hidden !important;
}
tbody td:nth-child(1) .thumbnail-name-container img {
    margin-right: 5px !important;
}
tbody td:nth-child(1) .thumbnail-name-container span {
    overflow-wrap: break-word !important;
    overflow: hidden !important;
    text-overflow: ellipsis !important;
}
tbody td:nth-child(4) {
    white-space: normal !important;
}
  </style>
</head>

<body>

As we celebrate 60 years of nation-building, take a trip down memory lane with the Mascotdex — a growing repository dedicated to Singapore’s beloved characters, past and present. Mascots are grouped according to their status (active or retired) on this page.

<div style="text-align: center; margin-top: 15px; margin-bottom: 15px;">
  <a href="https://www.designinsingapore.com/mascotdex/" style="text-decoration: none;">
    <button style="background-color: #005FEA; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; font-size: 1em;">
      ← Back to Main Mascotdex
    </button>
  </a>
</div>

  
    <h3>Active</h3>
<div class="mascot-details-table">
      <div class="table-wrapper">
        <table id="mascotTableActive" class="fixed-layout-table">

            <thead>
                <tr>
                    <th style="text-align: center;" onclick="sortTable(0, 'mascotTableActive')">Name<span class="sort-arrow" id="arrow0_Active">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(1, 'mascotTableActive')">Birth Year<span class="sort-arrow" id="arrow1_ Active">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(2, 'mascotTableActive')">Status<span class="sort-arrow" id="arrow2_ Active">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(3, 'mascotTableActive')">Owner<span class="sort-arrow" id="arrow3_ Active">▲</span></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Jx9TK5n.png" alt="Merlion" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/merlion/">Merlion</a></div></td>
                    <td>1964</td>
                    <td>Active</td>
                    <td>Singapore Tourism Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/NKfAKKr.png" alt="Singa the Kindness Lion" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/singa/">Singa the Kindness Lion</a></div></td>
                    <td>1982</td>
                    <td>Active</td>
                    <td>Singapore Kindness Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/BXz69z3.png" alt="Smiley" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/smiley/">Smiley</a></div></td>
                    <td>1983</td>
                    <td>Active</td>
                    <td>POSB Bank</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/LQSHhU0.png" alt="Sharity" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/sharity/">Sharity</a></div></td>
                    <td>1984</td>
                    <td>Active</td>
                    <td>Community Chest</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/vBk33BZ.png" alt="Suzy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/suzy/">Suzy</a></div></td>
                    <td>1984</td>
                    <td>Active</td>
                    <td>Cerebral Palsy Alliance Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ENH6WNO.png" alt="Captain Green" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/captain-green/">Captain Green</a></div></td>
                    <td>1990</td>
                    <td>Active</td>
                    <td>National Environment Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2Hd50M2.png" alt="Oscar" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/oscar/">Oscar</a></div></td>
                    <td>2002</td>
                    <td>Active</td>
                    <td>Singapore Food Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/V7ZYTBP.png" alt="Blood Buddy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/blood-buddy/">Blood Buddy</a></div></td>
                    <td>2005</td>
                    <td>Active</td>
                    <td>Singapore Red Cross</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/A5bPV0K.png" alt="Water Wally" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/water-wally/">Water Wally</a></div></td>
                    <td>2005</td>
                    <td>Active</td>
                    <td>PUB, Singapore’s National Water Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/GMm3eq0.png" alt="CPT Ted" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/cpt-ted/">CPT Ted</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>The Republic of Singapore Air Force</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/xTv56cu.png" alt="Kalle" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/kalle/">Kalle</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>Singapore Kindness Movement</td>
                </tr>
                 <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/GNpSrHt.png" alt="Sher" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/sher/">Sher</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>Singapore Kindness Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/gPWrj2B.png" alt="Tomeo" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/tomeo/">Tomeo</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>Singapore Kindness Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/mkcMSf4.png" alt="Tosh" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/tosh/">Tosh</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>Singapore Kindness Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/lckamLq.png" alt="Mr Zebra" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/mr-zebra/">Mr Zebra</a></div></td>
                    <td>2011</td>
                    <td>Active</td>
                    <td>Singapore Road Safety Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/oyF1L2o.png" alt="Leo" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/leo/">Leo</a></div></td>
                    <td>2013</td>
                    <td>Active</td>
                    <td>Singapore Airshow</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/eVBv2yk.png" alt="Bag-Down Benny" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/bag-down-benny/">Bag-Down Benny</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>Land Transport Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/diYTS2C.png" alt="Give-Way Glenda" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/give-way-glenda/">Give-Way Glenda</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>Land Transport Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/8JMbZi9.png" alt="Hush-Hush Hannah" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/hush-hush-hannah/">Hush-Hush Hannah</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>Land Transport Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/sZE3jTa.png" alt="Move-In Martin" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/move-in-martin/">Move-In Martin</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>Land Transport Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/9EKOyPw.png" alt="Stand-Up Stacey" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/stand-up-stacey/">Stand-Up Stacey</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>Land Transport Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/FPCg870.png" alt="Ottie" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ottie/">Ottie</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/TmsxyDr.png" alt="Bobby" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/bobby/">Bobby</a></div></td>
                    <td>2014</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/xOlIIiA.png" alt="Nila" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/nila/">Nila</a></div></td>
                    <td>2015</td>
                    <td>Active</td>
                    <td>Sport Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/632gOeK.png" alt="Pi" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/pi/">Pi</a></div></td>
                    <td>2015</td>
                    <td>Active</td>
                    <td>National Deaf Games</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/5nDutF2.png" alt="Zippy Maree" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/zippy-maree/">Zippy Maree</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Sustainable Singapore Gallery</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/WUH3tma.png" alt="Caring Cora" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/caring-cora/">Caring Cora</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Sustainable Singapore Gallery</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/l53FXtY.png" alt="Ken" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ken/">Ken</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/XirFZsA.png" alt="Eco Eva" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/eco-eva/">Eco Eva</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Sustainable Singapore Gallery</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/WhpSgaC.png" alt="Leonette" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/leonette/">Leonette</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Singapore Airshow</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2uIxNVy.png" alt="SingaPaw" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/singapaw/">SingaPaw</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Singapore Discovery Centre</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/z4ZJhEM.png" alt="Smart Eddie" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/smart-eddie/">Smart Eddie</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Sustainable Singapore Gallery</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/r9lri7Y.png" alt="Smiley Ray" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/smiley-ray/">Smiley Ray</a></div></td>
                    <td>2016</td>
                    <td>Active</td>
                    <td>Sustainable Singapore Gallery</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/bm42q3Q.png" alt="Kopi Lim" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/kopi-lim/">Kopi Lim</a></div></td>
                    <td>2017</td>
                    <td>Active</td>
                    <td>Corrupt Practices Investigation Bureau</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/r5DVpOC.png" alt="Dr Maxine" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dr-maxine/">Dr Maxine</a></div></td>
                    <td>2018</td>
                    <td>Active</td>
                    <td>Singapore Cancer Society</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/fYx7jJ3.png" alt="Parley" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/parley/">Parley</a></div></td>
                    <td>2018</td>
                    <td>Active</td>
                    <td>Parliament of Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/eK5wJ5G.png" alt="Merli" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/merli/">Merli</a></div></td>
                    <td>2018</td>
                    <td>Active</td>
                    <td>Singapore Tourism Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/fwsg42u.png" alt="Ally" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ally/">Ally</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Rn8i9OZ.png" alt="Pan" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/pan/">Pan</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Bq7zH6W.png" alt="Giffy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/giffy/">Giffy</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Dementia-Friendly Singapore Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Jm2SabP.png" alt="Jaga" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/jaga/">Jaga</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/we0egOO.png" alt="Inspector Clif" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/inspector-clif/">Inspector Clif</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Singapore Police Force</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/1D9Jey9.png" alt="Ray" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ray/">Ray</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Singapore Police Force</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/W04lAn2.png" alt="Camy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/camy/">Camy</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>National Library Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/QGCXjuB.png" alt="Hutsy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/hutsy/">Hutsy</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>National Library Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/4l3LPtl.png" alt="Rooky" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/rooky/">Rooky</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>National Library Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/HWAcsg7.png" alt="Zecky" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/zecky/">Zecky</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>National Library Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/86YMJVK.png" alt="Ka" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ka/">Ka</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Consumers Association of Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/fRlqonq.png" alt="Ki" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ki/">Ki</a></div></td>
                    <td>2019</td>
                    <td>Active</td>
                    <td>Consumers Association of Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/WREb2xW.png" alt="K.D." class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/kd/">K.D.</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>People’s Association</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2fAPrr5.png" alt="Dome Bot" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dome-bot/">Dome Bot</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>National Museum of Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/LLV4IBd.png" alt="Gayle" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/gayle/">Gayle</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/1KCurEr.png" alt="Agile" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/agile/">Agile</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/RIH5YRu.png" alt="Bold" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/bold/">Bold</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/9yQdAVx.png" alt="Collaborative" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/collaborative/">Collaborative</a></div></td>
                    <td>2020</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/N7YEbT1.png" alt="Apathetic Andy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/apathetic-andy/">Apathetic Andy</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/nX8afuS.png" alt="Inquisitive Ivan" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/inquisitive-ivan/">Inquisitive Ivan</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/bn08ufk.png" alt="Skeptical Susan" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/skeptical-susan/">Skeptical Susan</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/WOWFa04.png" alt="Ivan" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ivan/">Ivan</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ujBl9OR.png" alt="Kaki" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/kaki/">Kaki</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>OneService</td>
                </tr>
<tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/jlv9iST.png" alt="August" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/august/">August</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>National Day Parade</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/9vgBLbZ.png" alt="Becky Bunny" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/becky-bunny/">Becky Bunny</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>Families for Life</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/XaaWHou.png" alt="Rachel REACH" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/rachel-reach/">Rachel REACH</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/oVHWRaK.png" alt="STEMlings" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/stemlings/">STEMlings</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>Science Centre Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/3XQ32X6.png" alt="Water Sally" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/water-sally/">Water Sally</a></div></td>
                    <td>2021</td>
                    <td>Active</td>
                    <td>PUB, Singapore’s National Water Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/b1ldZ74.png" alt="SUN-Bear" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/sun-bear/">SUN-Bear</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Sun-dac</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/IYU00CU.png" alt="Bloobin" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/bloobin/">Bloobin</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Clean &amp; Green Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ei4fiQ2.png" alt="BRAVE" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/brave/">BRAVE</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Beyond the Label Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Nrg2EhV.png" alt="Ray (Club Rainbow)" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ray-club-rainbow/">Ray (Club Rainbow)</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Club Rainbow</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/P1Bfatm.png" alt="Seabasstian Water" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/seabasstian-water/">Seabasstian Water</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Singapore Food Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/7viPga0.png" alt="Eggs Benedette C" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/eggs-benedette-c/">Eggs Benedette C</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Singapore Food Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/yQvspLT.png" alt="Compassionate Cassie" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/compassionate-cassie/">Compassionate Cassie</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/fjPrEpj.png" alt="Creative Cory" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/creative-cory/">Creative Cory</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ZJBUTgJ.png" alt="Fearless Farah" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/fearless-farah/">Fearless Farah</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Q2htDpH.png" alt="Kiasu Kitty" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/kiasu-kitty/">Kiasu Kitty</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/qruAEmC.png" alt="Patriotic Paige" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/patriotic-paige/">Patriotic Paige</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>REACH</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/g7lWrKj.png" alt="Phyll" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/phyll/">Phyll</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>National Parks Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/7cfjFMP.png" alt="Ollie" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ollie/">Ollie</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Government Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2X1DpLv.png" alt="WonderBot" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/wonderbot/">WonderBot</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Children's Museum Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/SKdPtKF.png" alt="Dastan" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dastan/">Dastan</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Defence Science and Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Xv4HUo6.png" alt="Spark" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/spark/">Spark</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Youthtopia</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/hToEeMV.png" alt="Toilemon" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/toilemon/">Toilemon</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Public Hygiene Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/iAaqPSD.png" alt="Trashemon" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/trashemon/">Trashemon</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Public Hygiene Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/3JmGkhl.png" alt="Trayremon" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/trayremon/">Trayremon</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Public Hygiene Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Vf958vw.png" alt="PIP" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/pip/">PIP</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Esplanade – Theatres on the Bay</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/kGnNXGZ.png" alt="Caixinderella" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/caixinderella/">Caixinderella</a></div></td>
                    <td>2022</td>
                    <td>Active</td>
                    <td>Singapore Food Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/zJhZfig.png" alt="X" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/x/">X</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Home Team Science and Technology Agency</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/zvbQo0P.png" alt="Charlie" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/charlie/">Charlie</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Singapore Co-operative Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/MVCCrry.png" alt="Mia" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/mia/">Mia</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Singapore Co-operative Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/heG93Ak.png" alt="Shane" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/shane/">Shane</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Singapore Co-operative Movement</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/9CWkAKf.png" alt="COLin" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/colin/">COLin</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Singapore Prison Service</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/27pBsmF.png" alt="Nano" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/nano/">Nano</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Science Centre Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Nvor18W.png" alt="Pico" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/pico/">Pico</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Science Centre Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/KMM0TgV.png" alt="TICA" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/tica/">TICA</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>Immigration and Checkpoints Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/jZUUdZB.png" alt="wiTTy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/witty/">wiTTy</a></div></td>
                    <td>2023</td>
                    <td>Active</td>
                    <td>SG Translate Together</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/AQanEbT.png" alt="Canny" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/canny/">Canny</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>The Association of Banks in Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/1babVBl.png" alt="Guardian Gabe" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/guardian-gabe/">Guardian Gabe</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>Insurance and Financial Practitioners Association of Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/eJKMVXt.png" alt="Mr Red Box" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/mr-red-box/">Mr Red Box</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>Youth Corps Singapore</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/gNKuNhD.png" alt="Roary" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/roary/">Roary</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>Singapore National Paralympic Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/plxBydS.png" alt="Finley" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/finley/">Finley</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>Singapore Disability Sports Council</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/apbiNgj.png" alt="Tembi" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/tembi/">Tembi</a></div></td>
                    <td>2024</td>
                    <td>Active</td>
                    <td>Silver Generation Office</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/L13P4dN.png" alt="Ah Dot" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ah-dot/">Ah Dot</a></div></td>
                    <td>2025</td>
                    <td>Active</td>
                    <td>13th World Para Swimming Championships 2025</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/sv02jf2.png" alt="Dewey" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dewey/">Dewey</a></div></td>
                    <td>2025</td>
                    <td>Active</td>
                    <td>22nd World Aquatics Championships 2025</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ZaqDM1D.png" alt="Ollie (World Aquatics Championships 2025)" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/ollie-world-aquatics-championships-2025/">Ollie (World Aquatics Championships 2025)</a></div></td>
                    <td>2025</td>
                    <td>Active</td>
                    <td>22nd World Aquatics Championships 2025</td>
                </tr>
            </tbody>
        </table>
    </div>

<br>
            
<h3>Retired</h3>
    <div class="mascot-details-table">
              <div class="table-wrapper">

        <table id="mascotTableRetired" class="fixed-layout-table">
            <thead>
                <tr>
                    <th style="text-align: center;" onclick="sortTable(0, 'mascotTableRetired')">Name<span class="sort-arrow" id="arrow0_Retired">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(1, 'mascotTableRetired')">Birth Year<span class="sort-arrow" id="arrow1_Retired">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(2, 'mascotTableRetired')">Status<span class="sort-arrow" id="arrow2_Retired">▲</span></th>
                    <th style="text-align: center;" onclick="sortTable(3, 'mascotTableRetired')">Owner<span class="sort-arrow" id="arrow3_Retired">▲</span></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Xr0vWeq.png" alt="Netalia" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/netalia/">Netalia</a></div></td>
                    <td>2011</td>
                    <td>Retired</td>
                    <td>13th World Netball Championships 2011</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/8cLGehQ.png" alt="Sean the Lion" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/sean/">Sean the Lion</a></div></td>
                    <td>2011</td>
                    <td>Retired</td>
                    <td>3rd ASEAN School Games 2011</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/unpXt3k.png" alt="Dotz" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dotz/">Dotz</a></div></td>
                    <td>2013</td>
                    <td>Retired</td>
                    <td>Building and Construction Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/gStEVOD.png" alt="Hexa" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/hexa/">Hexa</a></div></td>
                    <td>2013</td>
                    <td>Retired</td>
                    <td>Building and Construction Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/pzqILuu.png" alt="Beco" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/beco/">Beco</a></div></td>
                    <td>2014</td>
                    <td>Retired</td>
                    <td>Building and Construction Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/0l0K1Et.png" alt="Greco" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/greco/">Greco</a></div></td>
                    <td>2014</td>
                    <td>Retired</td>
                    <td>Building and Construction Authority</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/SShz92o.png" alt="TD Defenders" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/td-defenders/">TD Defenders</a></div></td>
                    <td>2016</td>
                    <td>Retired</td>
                    <td>Singapore Discovery Centre</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/wxRLpF2.png" alt="Blo.belina" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/blo-belina/">Blo.belina</a></div></td>
                    <td>2018</td>
                    <td>Retired</td>
                    <td>Singapore Red Cross</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/T9BOokZ.png" alt="Dino" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dino/">Dino</a></div></td>
                    <td>2018</td>
                    <td>Retired</td>
                    <td>National Heritage Board</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/DlbeZLD.png" alt="Care-leh Dee" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/care-leh-dee/">Care-leh Dee</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Communications and Information</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/ARxvaIP.png" alt="Circuit Breaker" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/circuit-breaker/">Circuit Breaker</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Communications and Information</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/rQOoDTP.png" alt="Dr. Disinfector" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/dr-disinfector/">Dr. Disinfector</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Communications and Information</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2FlBy1Z.png" alt="Fake News Buster" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/fake-news-buster/">Fake News Buster</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Communications and Information</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/WtbVxIK.png" alt="MAWA Man (Must Always Walk Alone Man)" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/mawa-man/">MAWA Man (Must Always Walk Alone Man)</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Communications and Information</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/KIyrkqj.png" alt="Hands Down Hana" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/hands-down-hana/">Hands Down Hana</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Education</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/LP4GK0A.png" alt="Mask Up Mei Mei" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/mask-up-mei-mei/">Mask Up Mei Mei</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Education</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/51ud9fL.png" alt="Super Soaper Soffy" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/super-soaper-soffy/">Super Soaper Soffy</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Education</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/2l6xgXI.png" alt="Virus Screener Varun" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/virus-screener-varun/">Virus Screener Varun</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Education</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/Kd3FTYJ.png" alt="Wipe Up Wilson" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/wipe-up-wilson/">Wipe Up Wilson</a></div></td>
                    <td>2020</td>
                    <td>Retired</td>
                    <td>Ministry of Education</td>
                </tr>
                <tr>
                    <td><div class="thumbnail-name-container"><img src="https://i.imgur.com/vIU90r5.png" alt="OTTer" class="thumbnail-name"><a href="https://www.designinsingapore.com/mascotdex/otter/">OTTer</a></div></td>
                    <td>2021</td>
                    <td>Retired</td>
                    <td>Government Technology Agency</td>
                </tr>
            </tbody>
        </table>
    </div>




    <script>

document.addEventListener('DOMContentLoaded', function() {
  const headers = document.querySelectorAll('h3');
  headers.forEach(function(header) {
    const text = header.textContent.toLowerCase().replace(/\s+/g, '-').replace(/[^\w-]+/g, '');
    header.setAttribute('id', text);

    // Optionally, make the header text a direct link
    const anchor = document.createElement('a');
    anchor.setAttribute('href', '#' + text);
    anchor.style.textDecoration = 'none'; // Remove default link underline
    anchor.style.color = 'inherit';      // Keep the header's color
    anchor.textContent = header.textContent;
    header.textContent = ''; // Clear original text
    header.appendChild(anchor);
  });
});    
        function sortTable(colIndex, tableId) {
    const table = document.getElementById(tableId);
    const tbody = table.tBodies[0];
    const rows = Array.from(tbody.rows);
    // Correctly access the sort state for the specific table and column
    const asc = sortState[tableId][colIndex];

    rows.sort((a, b) => {
        let valA, valB;
        if (colIndex === 0) {
            // Handle the Name column, extract text from the anchor
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
    // Correctly update the sort state for the specific table and column
    sortState[tableId][colIndex] = !asc;

    // Update arrow icons, IMPORTANT: Now uses the tableId to target correctly.
    const arrowIcons = document.querySelectorAll(`#${tableId} .sort-arrow`);
    arrowIcons.forEach((arrow, index) => {
        if (index === colIndex) {
            arrow.textContent = asc ? '▲' : '▼';
        } else {
             // Reset other arrows to a default state (e.g., unsorted or initial sort direction)
             // You might want to consider a neutral state like '↕' or reset to the default '▲'
            arrow.textContent = '▲';
        }
    });
}

// Keep track of sort state for each table. Use an object.
const sortState = {
    mascotTableActive: [true, true, true, true],
    mascotTableRetired: [true, true, true, true],
};





const birthYearHeader = document.querySelector('th:nth-child(2)');
if (birthYearHeader) {
  const spans = birthYearHeader.querySelectorAll('span');
  spans.forEach(span => span.remove());
  birthYearHeader.textContent = "Birth Year";
  const triangle = document.createElement('span');
  triangle.className = 'sort-arrow';
  triangle.id = 'arrow1';
  triangle.textContent = '▲';
  birthYearHeader.appendChild(triangle);

  const textContent = birthYearHeader.textContent.trim();
  birthYearHeader.innerHTML = '';
  const firstDiv = document.createElement('div');
  firstDiv.textContent = "Birth";
  const secondDiv = document.createElement('div');
  secondDiv.textContent = "Year";
  secondDiv.appendChild(triangle);

  birthYearHeader.appendChild(firstDiv);
  birthYearHeader.appendChild(secondDiv);
  birthYearHeader.style.display = 'flex';
  birthYearHeader.style.flexDirection = 'column';
  birthYearHeader.style.whiteSpace = '';
  birthYearHeader.style.lineHeight = '';
  secondDiv.style.display = 'flex';
  secondDiv.style.flexDirection = 'row';
  secondDiv.style.marginLeft = '5px'
}
    </script>

