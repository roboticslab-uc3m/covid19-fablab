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
| 50 | Policía Municipal (Leganés) | 2020/04/01 | |
| 50 | Hospital de Campaña (Leganés) | 2020/04/02 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1245778047082598402) |
| 230 | Hospital Ramón y Cajal | 2020/04/02+14 | [\[1\]](https://twitter.com/uc3m_aero/status/1246060229256716288) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1250881480739430407) [\[3\]](https://twitter.com/nuria_imeq/status/1250547777366523904) |
| 18 | Seguridad Universidad | 2020/04/02+23 | |
| 50 | Hospital de Aranjuez | 2020/04/03 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1246415631253213189) |
| 92 | Bomberos (Leganés) | 2020/04/02+04+17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1246483385826136065) |
| 52 | Hospital de Fuenlabrada | 2020/04/05+08 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247469587064590336) [\[2\]](https://twitter.com/nuria_imeq/status/1247245128307179520) [\[3\]](https://twitter.com/JPozuelo69/status/1255458850951569419) |
| 10 | Correos Plaza Salvador (Leganés) | 2020/04/06 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247142950280163333) |
| 10 | Farmacia Av. Fuenlabrada (Leganés) | 2020/04/06 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247142950280163333) |
| 10 | Hospital Universitario de la Princesa | 2020/04/06 | [\[1\]](https://twitter.com/nuria_imeq/status/1248613575817453568) |
| 53 | Hospital Universitario 12 de Octubre | 2020/04/07+21 y 2020/05/05 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253249057499348992) |
| 30 | Residencia Peñuelos Arganzuela | 2020/04/07+23 | |
| 10 | Hospital Clínico Universitario San Carlos | 2020/04/07 | [\[1\]](https://twitter.com/nuria_imeq/status/1250047570409336833) |
| 420 | Hospital Virgen de la Salud (Toledo) | 2020/04/07+10+17 y 2020/05/03 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1247835218192588800) [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Barber (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Torrijos (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Talavera (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Residencia Santa Casilda (Toledo) | 2020/04/07 | [\[2\]](https://twitter.com/uc3m_aero/status/1247631158587916290) |
| 20 | Hospital Gregorio Marañón (Rayos) | 2020/04/07 | [\[1\]](https://twitter.com/nuria_imeq/status/1247955733926367250) |
| 6 | Farmacia Povedano Del Yerro Jesús (Leganés) | 2020/04/07 | [\[1\]](https://twitter.com/davidgmato/status/1250796966021410817) |
| 50 | Sacyr Social (Servicio de Atención a Domicilio del Ayuntamiento, Getafe) | 2020/04/08 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248161731748278273) |
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
| 30 | Centro Salud (Arroyomolinos) | 2020/04/17 | |
| 25 | Residencia de Usera | 2020/04/17 | |
| 26 | UVI 20 (San Martín de Valdeiglesias) | 2020/04/17 | [\[1\]](https://twitter.com/nuria_imeq/status/1253308663927693313) |
| 30 | Hospital de Fuenlabrada (UCI) | 2020/04/17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1251568352511889408) |
| 51 | Limpieza (Universidad Carlos III de Madrid) | 2020/04/17 y 2020/05/14 | |
| 30 | IFEMA (Voluntarios) | 2020/04/17 | |
| 30 | Casa Sacerdotal (Toledo) | 2020/04/19 | |
| 11 | Residencia de Mayores Amavir (Arganzuela) | 2020/04/19 | |
| 5 | Ortopedia Iglesias Hermanos (Carabanchel) | 2020/04/20 | |
| 5 | Clínica Dental Atlanta (Las Rozas) | 2020/04/20 | |
| 5 | Clínica Dental Arco (Villanueva de la Cañada) | 2020/04/20 | |
| 40 | Residencias Yeles | 2020/04/21 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253968915446804482) |
| 2 | Limpieza Calle (Leganés) | 2020/04/21 | |
| 15 | Residencia Ballesol Olavide | 2020/04/23 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1255540832498843649) |
| 5 | Thyssenkrupp | 2020/04/23 | |
| 10 | Clínica Dental (Alcorcón) | 2020/04/23 | |
| 25 | Centro Médico Nenufar (Alcorcón) | 2020/04/23 | |
| 15 | Fisioterapia FisioVital (Getafe) | 2020/04/23 | |
| 200 | Mensajeros de la Paz: Residencia Montserrat Caballé | 2020/04/25 | [\[1\]](https://twitter.com/nuria_imeq/status/1254002535020535808) |
| 10 | Clínica Dental Cruz | 2020/04/25 | |
| 20 | Asociación de Mayores (El Álamo) | 2020/04/26 | |
| 160 | Ministros Voluntarios | 2020/04/27 | |
| 25 | Servicio de correos (Granada) | 2020/04/29 | |
| 50 | Centro de Salud 2 de Mayo (Móstoles) | 2020/04/29 | |
| 50 | Clinica Gereátrica Los Ángeles (Getafe) | 2020/04/29 | [[1]](https://twitter.com/nuria_imeq/status/1255545803797671937) |
| 12 | Logopedia y Psicología (Villaverde) | 2020/04/29 | |
| 20 | Asociación Amar Dragoste (Leganés) | 2020/04/30 | |
| 4 | Peluqueria Sandro's (Santa Engracia) | 2020/04/30 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1256502570723524609) |
| 10 | Consultorio Médico (Leganés) | 2020/05/01 | [\[1\]](https://twitter.com/nuria_imeq/status/1256270751570833408) |
| 100 | Residencia Infantil Isabel de Castilla | 2020/05/03 | [\[1\]](https://twitter.com/nuria_imeq/status/1256899267802927104) |
| 20 | Residencia San José (Toledo) | 2020/05/03 | |
| 20 | Cáritas (Getafe) | 2020/05/04 | [\[1\]](https://twitter.com/nuria_imeq/status/1256899276174700544) |
| 5 | Clínica Fisioterapia Charcot (Parla) | 2020/05/04 | |
| 20 | Trabajadores de limpieza y desinfección | 2020/05/07 | |
| 10 | Ortopedia Orthosport (Valdemoro) | 2020/05/07 | |
| 20 | Oficina Patentes y Marcas (P. Castellana) | 2020/05/07 | |
| 10 | Clínica Salud Natura | 2020/05/07 | |
| 6 | Local familiar alimentación (Navahermosa, Toledo) | 2020/05/07 | |
| 8 | Ultramarinos (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258369044710817793) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 4 | Pastelería (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1257754436602155009) |
| 6 | Quiosco (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 3 | Clínica pediátrica (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 1 | Pollería (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 2 | Floristería (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 1 | Tienda pinturas (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 1 | Trabajadora social (Leganés) | 2020/05/07 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1258451788405133312) |
| 50 | Escuela Infantil | 2020/05/07 | |
| 10 | Clínica Dental Cantero | 2020/05/08 | |
| 73 | Hospital de Getafe | 2020/05/08+15+17 | |
| 30 | Pequeño comercio: fruterías, carnicerías, peluquerías, tienda de informática (Leganés Norte) | 2020/05/09 | |
| 15 | Centro Salud (Loranca) | 2020/05/09 | |
| 150 | Centro de Educación Especial | 2020/05/11 | |
| 10 | Pequeño comercio, restaurante... (Parla) | 2020/05/11 | |
| 15 | Cáritas (Alcorcón) | 2020/05/14 | |
| 10 | Centro de Salud (Getafe) | 2020/05/15 | |
| 165 | Hospital Universitario de Albacete | 2020/05/16 | |
| 250 | Asociación de Voluntarios "Bocatas" |  2020/05/16 | |
| 2 | Vecino mayor (Leganés) |  2020/05/16 | |
| 20 | Asociación Rumiñahui |  2020/05/17 | |
| 5 | Bomberos (Madrid) |  2020/05/17 | |
| 5 | Enfermeras de Quirón prevención (Parla) |  2020/05/17 | |
| 80 | Pacientes oncológicos (Toledo) |  2020/05/18 | |
| 5 | Autoescula Transito Vallecas |  2020/05/18 | |
| 22 | Centro de Salud San Nicasio (Leganés) | 2020/05/19 | |
| ======== | ========= | ===== | ==== |
| | | | |

<p></p>

## Correas mascarilla entregadas

{: #sujetamask .display}
| Cantidad | Ubicación | Fecha | RRSS |
| -------- | --------- | ----- | ---- |
| 500 | Hospital Universitario Fundación Jiménez Díaz | 2020/04/09+19+26 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/Larryancito/status/1248752387218722816) [\[3\]](https://twitter.com/nuria_imeq/status/1249647590297284608) [\[4\]](https://twitter.com/DrJCornago/status/1252533818449412096) |
| 125 | Hospital Universitario 12 de Octubre | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/ElenaVA70/status/1248579798571585537) [\[3\]](https://twitter.com/davidgmato/status/1248935754329403399) |
| 130 | Hospital Universitario de Móstoles | 2020/04/09+12 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 55 | Residencia Monte Hermoso | 2020/04/09+17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) [\[2\]](https://twitter.com/natxo88/status/1249746483248857088) |
| 100 | Hospital Clinico San Carlos | 2020/04/09 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 150 | Hospital La Paz | 2020/04/09+15 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1248304553130328066) |
| 200 | Hospital de Getafe | 2020/04/09+27 | |
| 450 | Hospital Virgen de la Salud (Toledo) | 2020/04/10+17 y 2020/05/03 | |
| 30 | Hospital de Móstoles | 2020/04/10 | |
| 100 | Hospital Rey Juan Carlos (Móstoles) | 2020/04/10 | |
| 200 | Hospital Universitario Fundación Alcorcón | 2020/04/10 | |
| 8200 | Hospital Gregorio Marañón | 2020/04/14+16+17+21+27 y 2020/05/07 | [\[1\]](https://twitter.com/3d_maranon/status/1250010760014630912) [\[2\]](https://twitter.com/uc3mRoboticsLab/status/1252582760893632513) |
| 50 | Hospital de Alcorcón | 2020/04/14 | |
| 250 | Residencia Personas Mayores de Villaviciosa de Odón | 2020/04/15 | |
| 40 | Centro Salud (Arroyomolinos) | 2020/04/17 | |
| 25 | Residencia de Usera | 2020/04/17 | |
| 100 | Hospital Universitario Santa Cristina | 2020/04/17 | |
| 100 | Hospital Carlos III | 2020/04/17 | |
| 200 | Hospital Gómez Ulla | 2020/04/17 | |
| 100 | Instituto Psiquiátrico José Germain (Leganés) | 2020/04/17 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1251497914653966336) |
| 30 | UVI 20 (San Martín de Valdeiglesias) | 2020/04/17 | |
| 20 | Hospital Puerta de Hierro (Majadahonda) | 2020/04/20 | [\[1\]](https://twitter.com/davidgmato/status/1253305572012765187) |
| 6 | Clínica Dental Atlanta (Las Rozas) | 2020/04/20 | |
| 6 | Clínica Dental Arco (Villanueva de la Cañada) | 2020/04/20 | |
| 600 | Hospital de Guadarrama | 2020/04/22 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1253663113976610816) |
| 100 | Residencia Ballesol Olavide | 2020/04/23 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1255540832498843649) |
| 50 | Residencia Peñuelos Arganzuela | 2020/04/23 | |
| 10 | Clínica Dental (Alcorcón) | 2020/04/23 | |
| 75 | Transade Logística (Valdemoro) | 2020/04/23 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1255750449644388354) |
| 500 | Ministros Voluntarios | 2020/04/27 | |
| 12 | Logopedia y Psicología (Villaverde) | 2020/04/29 | |
| 8 | Peluqueria Sandro's (Santa Engracia) | 2020/04/30 | [\[1\]](https://twitter.com/uc3mRoboticsLab/status/1256502570723524609) |
| 20 | Asociación Amar Dragoste (Leganés) | 2020/04/30 | |
| 150 | Residencia San José (Toledo) | 2020/05/03 | |
| 5 | Clínica Fisioterapia Charcot (Parla) | 2020/05/04 | |
| 150 | HM Sanchinarro | 2020/05/07 | |
| 520 | Hospital de Getafe | 2020/05/08+21 | |
| 150 | Centro de Educación Especial | 2020/05/11 | |
| 20 | Clínica Groen Fisioterapia | 2020/05/12 | |
| 25 | Limpieza (Universidad Carlos III de Madrid) | 2020/05/14 | |
| 600 | Hospital Universitario de Albacete | 2020/05/16 | |
| 100 | Asociación de Voluntarios "Bocatas" |  2020/05/16 | |
| 20 | Asociación Rumiñahui |  2020/05/17 | |
| 80 | Pacientes oncológicos (Toledo) |  2020/05/18 | |
| ======== | ========= | ===== | ==== |
| | | | |

