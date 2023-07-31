---
layout: post
title: NFC-Trace
description: Lorem ipsum dolor est
image: assets/images/nfc_Trace.jpg
nav-menu: true
---

Donec eget ex magna. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque venenatis dolor imperdiet dolor mattis sagittis. Praesent rutrum sem diam, vitae egestas enim auctor sit amet. Pellentesque leo mauris, consectetur id ipsum sit amet, fergiat. Pellentesque in mi eu massa lacinia malesuada et a elit. Donec urna ex, lacinia in purus ac, pretium pulvinar mauris. Curabitur sapien risus, commodo eget turpis at, elementum convallis elit. Pellentesque enim turpis, hendrerit.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis dapibus rutrum facilisis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Etiam tristique libero eu nibh porttitor fermentum. Nullam venenatis erat id vehicula viverra. Nunc ultrices eros ut ultricies condimentum. Mauris risus lacus, blandit sit amet venenatis non, bibendum vitae dolor. Nunc lorem mauris, fringilla in aliquam at, euismod in lectus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. In non lorem sit amet elit placerat maximus. Pellentesque aliquam maximus risus, vel sed vehicula.

Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque venenatis dolor imperdiet dolor mattis sagittis. Praesent rutrum sem diam, vitae egestas enim auctor sit amet. Pellentesque leo mauris, consectetur id ipsum sit amet, fersapien risus, commodo eget turpis at, elementum convallis elit. Pellentesque enim turpis, hendrerit tristique lorem ipsum dolor.
<head>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th,
        td {
            border: 1px solid black;
            padding: px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        td.task {
            background-color: #57BB8A;
        }
        td.day {
            padding: 4px;
        }
        td {
            border: 1px solid #1b1b1b;
        }
        .scroll {
            width: 800px;
            overflow: scroll;
        }
        ::-webkit-scrollbar {
            height: 4px;
            width: 4px;
            border: 1px solid #d5d5d5;
        }
    </style>
</head>

<body>
    <h1>Diagramme de Gantt</h1>
    <div class="scroll">
        <table>
            <tr>
                <th></th>
                <th colspan="5" class="week">Semaine 1</th>
                <th colspan="5" class="week">Semaine 2</th>
                <th colspan="5" class="week">Semaine 3</th>
                <th colspan="5" class="week">Semaine 4</th>
                <th colspan="5" class="week">Semaine 5</th>
                <th colspan="5" class="week">Semaine 6</th>
                <th colspan="5" class="week">Semaine 7</th>
                <th colspan="5" class="week">Semaine 8</th>
                <th colspan="5" class="week">Semaine 9</th>
                <!-- Ajoutez d'autres semaines ici -->
            </tr>
            <tr>
                <td>NFC-Trace</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
                <td class="day">L</td>
                <td class="day">M</td>
                <td class="day">M</td>
                <td class="day">J</td>
                <td class="day">V</td>
            </tr>
            <!-- Ligne pour chaque tâche -->
            <tr>
                <td>Étude du matériel</td>
                <td colspan="7" class="task"></td>
                <td colspan="40"></td>
            </tr>
            <tr>
                <td>Définir le format de lecture</td>
                <td colspan="7"></td>
                <td colspan="3" class="task"></td>
                <td colspan="40"></td>
            </tr>
            <tr>
                <td>Configurer les Raspberry Pi</td>
                <td colspan="15"></td>
                <td colspan="5" class="task"></td>
                <td colspan="40"></td>
            </tr>
            <tr>
                <td>Implémentation de la lecture d'un Tag NFC</td>
                <td colspan="20"></td>
                <td colspan="8" class="task"></td>
                <td colspan="40"></td>
            </tr>
            <tr>
                <td>Implémentation de l'ecriture d'un Tag NFC</td>
                <td colspan="28"></td>
                <td colspan="8" class="task"></td>
                <td colspan="40"></td>
            </tr>
            <tr>
                <td>Rendu projet (livrable)</td>
                <td colspan="40"></td>
                <td colspan="1" class="task"></td>
                <td colspan="40"></td>
            </tr>
        </table>
    </div>
</body>
