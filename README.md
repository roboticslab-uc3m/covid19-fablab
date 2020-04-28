# covid19-fablab | uc3m

<link rel="stylesheet" href="https://cdn.datatables.net/1.10.20/css/jquery.dataTables.min.css">

<script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/plug-ins/1.10.20/api/sum().js"></script>

<script type="text/javascript">
$(document).ready(function() {
    $('#pantallas').DataTable( {
        "paging": false,
        "searching": false,
        "info": false,
        "order": [[ 0, "desc" ]],
        drawCallback: function () {
            var api = this.api();
            $( api.table().footer() ).html( "<center><strong>Total: " + api.column( 0, {page:'current'} ).data().sum() + "</strong></center>");
        }
    });
} );
$(document).ready(function() {
    $('#sujetamask').DataTable( {
        "paging": false,
        "searching": false,
        "info": false,
        "order": [[ 0, "desc" ]],
        drawCallback: function () {
            var api = this.api();
            $( api.table().footer() ).html( "<center><strong>Total: " + api.column( 0, {page:'current'} ).data().sum() + "</strong></center>");
        }
    });
} );
</script>

<p></p>

- [Pantallas protectoras entregadas](#pantallas-protectoras-entregadas)
- [Correas mascarilla entregadas](#correas-mascarilla-entregadas)


## Pantallas protectoras entregadas

{: #pantallas .display}
| Cantidad | Ubicación | Fecha | RRSS |
| -------- | --------- | ----- | ---- |
| 140 | Hospital Severo Ochoa (Leganés) | 2020/03/27+29 y 2020/04/08+17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1243642850685997063) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1244325337829445643) [\[3\]](https://twitter.com/davidgmato/status/1247866579154604033) [\[4\]](https://twitter.com/nuria_imeq/status/1250047570409336833) |
| 25 | Protección Civil (Leganés) | 2020/03/31 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1245070018578190337) |
| 25 | Residencia Orpea (Villanueva de la Cañada) | 2020/03/31 | |
| 100 | Hospital Fundación San José | 2020/04/01 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1245422540006309889) [\[2\]](https://twitter.com/FISJ_Madrid/status/1246023461287452672) |
| 50 | Policía Municipal de (Leganés) | 2020/04/01 | |
| 50 | Hospital de Campaña (Leganés) | 2020/04/02 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1245778047082598402) |
| 230 | Hospital Ramón y Cajal | 2020/04/02+14 | [\[1\]](https://twitter.com/uc3m_aero/status/1246060229256716288) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1250881480739430407) [\[3\]](https://twitter.com/nuria_imeq/status/1250547777366523904) |
| 18 | Seguridad Universidad | 2020/04/02+23 | |
| 50 | Hospital de Aranjuez | 2020/04/03 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1246415631253213189) |
| 92 | Bomberos (Leganés) | 2020/04/02+04+17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1246483385826136065) |
| 52 | Hospital de Fuenlabrada | 2020/04/05+08 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247469587064590336) [\[2\]](https://twitter.com/nuria_imeq/status/1247245128307179520) |
| 10 | Correos Plaza Salvador (Leganés) | 2020/04/06 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247142950280163333) |
| 10 | Farmacia Av. Fuenlabrada (Leganés) | 2020/04/06 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247142950280163333) |
| 10 | Hospital Universitario de la Princesa | 2020/04/06 | [\[1\]](https://twitter.com/nuria_imeq/status/1248613575817453568) |
| 48 | Hospital Universitario 12 de Octubre | 2020/04/07+21 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253249057499348992) |
| 30 | Residencia Peñuelos Arganzuela | 2020/04/07+23 | |
| 10 | Hospital Clínico Universitario San Carlos | 2020/04/07 | [\[1\]](https://twitter.com/nuria_imeq/status/1250047570409336833) |
| 120 | Hospital Virgen de la Salud (Toledo) | 2020/04/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247835218192588800) [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Barber (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Torrijos (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Talavera (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Santa Casilda (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Hospital Gregorio Marañón (Rayos) | 2020/04/07 | [\[1\]](https://twitter.com/nuria_imeq/status/1247955733926367250) |
| 6 | Farmacia Povedano Del Yerro Jesús (Leganés) | 2020/04/07 | [\[1\]](https://twitter.com/davidgmato/status/1250796966021410817) |
| 50 | Sacyr Social (Servicio de Atención a Domicilio del Ayuntamiento, Getafe) | 2020/04/08 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248161731748278273) |
| 100 | Hospital Virgen de la Salud (Toledo) | 2020/04/10 | |
| 40 | UME | 2020/04/10 | [\[1\]](https://twitter.com/nuria_imeq/status/1250547777366523904) |
| 160 | Hospital Universitario Santa Cristina | 2020/04/10+17 | [\[1\]](https://twitter.com/nuria_imeq/status/1250547777366523904) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1250753574260412418) |
| 25 | Residencia de los Hermanos de la Salle (Griñón) | 2020/04/10 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1252144599084261376) |
| 25 | Hospital Universitario de Móstoles | 2020/04/12 | |
| 100 | Universidad Carlos III de Madrid | 2020/04/13 | |
| 15 | Hospital de Móstoles | 2020/04/13 | |
| 33 | Clece SA | 2020/04/14 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1251438739257204736) |
| 25 | Residencia San Juan de Dios (El Álamo) | 2020/04/15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1252076831873867776) |
| 25 | Residencia Edad de Oro (El Álamo) | 2020/04/15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1252218998982422530) |
| 25 | Residencia Los Jazmines (El Álamo) | 2020/04/15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1252249521813323778) |
| 25 | Residencia Benja (El Álamo) | 2020/04/15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1252312582242930691) |
| 100 | Hospital Virgen de la Salud (Toledo) | 2020/04/17 | |
| 30 | Centro Salud Arroyomolinos | 2020/04/17 | |
| 25 | Residencia de Usera | 2020/04/17 | |
| 10 | UVI San Martín de Valdeiglesias | 2020/04/17 | [\[1\]](https://twitter.com/nuria_imeq/status/1253308663927693313) |
| 30 | UCI Hospital Fuenlabrada | 2020/04/17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1251568352511889408) |
| 15 | Universidad Carlos III de Madrid (Limpieza) | 2020/04/17 | |
| 30 | IFEMA (Voluntarios) | 2020/04/17 | |
| 30 | Casa Sacerdotal (Toledo) | 2020/04/19 | |
| 11 | Residencia de Mayores Amavir (Arganzuela) | 2020/04/19 | |
| 5 | Ortopedia Iglesias Hermanos (Carabanchel) | 2020/04/20 | |
| 5 | Clínica Dental Atlanta (Las Rozas) | 2020/04/20 | |
| 5 | Clínica Dental Arco (Villanueva de la Cañada) | 2020/04/20 | |
| 40 | Residencias Yeles | 2020/04/21 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253968915446804482) |
| 2 | Limpieza Calle (Leganés) | 2020/04/21 | |
| 15 | Residencia Ballesol Olavide | 2020/04/23 | |
| 5 | Thyssenkrupp | 2020/04/23 | |
| 10 | Clínica Dental (Alcorcón) | 2020/04/23 | |
| 25 | Centro Médico Nenufar (Alcorcón) | 2020/04/23 | |
| 15 | Fisioterapia FisioVital (Getafe) | 2020/04/23 | |
| 200 | Mensajeros de la Paz: Residencia Monserrat Caballe | 2020/04/25 | |
| 10 | Clínica Dental Cruz | 2020/04/25 | |
| 20 | Asociación de Mayores (El Álamo) | 2020/04/26 | |
| 160 | Ministros Voluntarios | 2020/04/27 | |
| ======== | ========= | ===== | ==== |
| | | | |

<p></p>

## Correas mascarilla entregadas

{: #sujetamask .display}
| Cantidad | Ubicación | Fecha | RRSS |
| -------- | --------- | ----- | ---- |
| 200 | Hospital Universitario Fundación Jiménez Díaz | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/Larryancito/status/1248752387218722816) [\[3\]](https://twitter.com/nuria_imeq/status/1249647590297284608) |
| 125 | Hospital Universitario 12 de Octubre | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/ElenaVA70/status/1248579798571585537) [\[3\]](https://twitter.com/davidgmato/status/1248935754329403399) |
| 130 | Hospital Universitario de Móstoles | 2020/04/09+12 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 25 | Residencia Monte Hermoso | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/natxo88/status/1249746483248857088) |
| 100 | Hospital Clinico San Carlos | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 150 | Hospital La Paz | 2020/04/09+15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 200 | Hospital de Getafe | 2020/04/09+27 | |
| 100 | Hospital Virgen de la Salud (Toledo) | 2020/04/10 | |
| 30 | Hospital de Móstoles | 2020/04/10 | |
| 100 | Hospital Rey Juan Carlos (Móstoles) | 2020/04/10 | |
| 200 | Hospital Universitario Fundación Alcorcón | 2020/04/10 | |
| 4200 | Hospital Gregorio Marañón | 2020/04/14+16+17+21+27 | [\[1\]](https://twitter.com/3d_maranon/status/1250010760014630912) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1252582760893632513) |
| 50 | Hospital de Alcorcón | 2020/04/14 | |
| 250 | Residencia Personas Mayores de Villaviciosa de Odón | 2020/04/15 | |
| 100 | Hospital Virgen de la Salud (Toledo) | 2020/04/17 | |
| 40 | Centro Salud Arroyomolinos | 2020/04/17 | |
| 25 | Residencia de Usera | 2020/04/17 | |
| 100 | Hospital Universitario Santa Cristina | 2020/04/17 | |
| 100 | Hospital Carlos III | 2020/04/17 | |
| 200 | Hospital Gómez Ulla | 2020/04/17 | |
| 30 | Residencia Monte Hermoso | 2020/04/17 | |
| 100 | Instituto Psiquiátrico José Germain (Leganés) | 2020/04/17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1251497914653966336) |
| 30 | UVI 20 San Martín de Valdeiglesias | 2020/04/17 | |
| 100 | Hospital Universitario Fundación Jiménez Díaz | 2020/04/19 | [\[1\]](https://twitter.com/DrJCornago/status/1252533818449412096) |
| 20 | Hospital Puerta de Hierro (Majadahonda) | 2020/04/20 | [\[1\]](https://twitter.com/davidgmato/status/1253305572012765187) |
| 6 | Clínica Dental Atlanta (Las Rozas) | 2020/04/20 | |
| 6 | Clínica Dental Arco (Villanueva de la Cañada) | 2020/04/20 | |
| 600 | Hospital de Guadarrama | 2020/04/22 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253663113976610816) |
| 100 | Residencia Ballesol Olavide | 2020/04/23 | |
| 50 | Residencia Peñuelos Arganzuela | 2020/04/23 | |
| 10 | Clínica Dental (Alcorcón) | 2020/04/23 | |
| 75 | Transade Logística (Valdemoro) | 2020/04/23 | |
| 200 | Hospital Universitario Fundación Jiménez Díaz | 2020/04/26 | |
| 500 | Ministros Voluntarios | 2020/04/27 | |
| ======== | ========= | ===== | ==== |
| | | | |
