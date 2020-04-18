# covid19-fablab | uc3m

<link rel="stylesheet" href="https://cdn.datatables.net/1.10.20/css/jquery.dataTables.min.css">

<script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/plug-ins/1.10.20/api/sum().js"></script>

<script type="text/javascript">
$(document).ready(function() {
    $('#example').DataTable( {
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
    $('#example2').DataTable( {
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

<table id="example" class="display" style="width:100%">
    <thead>
        <tr>
            <th>Cantidad</th><th>Ubicación</th><th>Fecha</th><th>RRSS</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>130</td><td>Hospital Severo Ochoa (Leganés)</td><td>2020/03/27+29 y 2020/04/08</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1243642850685997063">[1]</a>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1244325337829445643">[2]</a>
            <a href="https://twitter.com/davidgmato/status/1247866579154604033">[3]</a>
            <a href="https://twitter.com/nuria_imeq/status/1250047570409336833">[4]</a>
        </td></tr>
        <tr><td>25</td><td>Protección Civil (Leganés)</td><td>2020/03/31</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1245070018578190337">[1]</a></td></tr>
        <tr><td>25</td><td>Residencia Orpea (Villanueva de la Cañada)</td><td>2020/03/31</td><td></td></tr>
        <tr><td>100</td><td>Hospital Fundación San José</td><td>2020/04/01</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1245422540006309889">[1]</a>
            <a href="https://twitter.com/FISJ_Madrid/status/1246023461287452672">[2]</a>
        </td></tr>
        <tr><td>50</td><td>Policía Municipal de (Leganés)</td><td>2020/04/01</td><td></td></tr>
        <tr><td>50</td><td>Hospital de Campaña (Leganés)</td><td>2020/04/02</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1245778047082598402">[1]</a></td></tr>
        <tr><td>130</td><td>Hospital Ramón y Cajal</td><td>2020/04/02+14</td><td>
            <a href="https://twitter.com/uc3m_aero/status/1246060229256716288">[1]</a>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1250881480739430407">[2]</a>
        </td></tr>
        <tr><td>14</td><td>Seguridad Universidad</td><td>2020/04/02</td><td></td></tr>
        <tr><td>50</td><td>Hospital de Aranjuez</td><td>2020/04/03</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1246415631253213189">[1]</a></td></tr>
        <tr><td>72</td><td>Bomberos (Leganés)</td><td>2020/04/02+04</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1246483385826136065">[1]</a></td></tr>
        <tr><td>52</td><td>Hospital de Fuenlabrada</td><td>2020/04/05+08</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1247469587064590336">[1]</a>
            <a href="https://twitter.com/nuria_imeq/status/1247245128307179520">[2]</a>
        </td></tr>
        <tr><td>10</td><td>Correos Plaza Salvador (Leganés)</td><td>2020/04/06</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1247142950280163333">[1]</a></td></tr>
        <tr><td>10</td><td>Farmacia Av. Fuenlabrada (Leganés)</td><td>2020/04/06</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1247142950280163333">[1]</a></td></tr>
        <tr><td>10</td><td>Hospital Universitario de la Princesa</td><td>2020/04/06</td><td><a href="https://twitter.com/nuria_imeq/status/1248613575817453568">[1]</a></td></tr>
        <tr><td>15</td><td>Hospital Universitario 12 de Octubre</td><td>2020/04/07</td><td></td></tr>
        <tr><td>10</td><td>Residencia Peñuelos Arganzuela</td><td>2020/04/07</td><td></td></tr>
        <tr><td>10</td><td>Hospital Clínico Universitario San Carlos</td><td>2020/04/07</td><td><a href="https://twitter.com/nuria_imeq/status/1250047570409336833">[1]</a></td></tr>
        <tr><td>120</td><td>Hospital Virgen de la Salud (Toledo)</td><td>2020/04/07</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1247835218192588800">[1]</a>
            <a href="https://twitter.com/uc3m_aero/status/1247631158587916290">[2]</a>
        </td></tr>
        <tr><td>20</td><td>Residencia Barber (Toledo)</td><td>2020/04/07</td><td><a href="https://twitter.com/uc3m_aero/status/1247631158587916290">[2]</a></td></tr>
        <tr><td>20</td><td>Residencia Torrijos (Toledo)</td><td>2020/04/07</td><td><a href="https://twitter.com/uc3m_aero/status/1247631158587916290">[2]</a></td></tr>
        <tr><td>20</td><td>Residencia Talavera (Toledo)</td><td>2020/04/07</td><td><a href="https://twitter.com/uc3m_aero/status/1247631158587916290">[2]</a></td></tr>
        <tr><td>20</td><td>Residencia Santa Casilda (Toledo)</td><td>2020/04/07</td><td><a href="https://twitter.com/uc3m_aero/status/1247631158587916290">[2]</a></td></tr>
        <tr><td>20</td><td>Hospital Gregorio Marañón (Rayos)</td><td>2020/04/07</td><td><a href="https://twitter.com/nuria_imeq/status/1247955733926367250">[1]</a></td></tr>
        <tr><td>6</td><td>Farmacia Povedano Del Yerro Jesús (Leganés)</td><td>2020/04/07</td><td><a href="https://twitter.com/davidgmato/status/1250796966021410817">[1]</a></td></tr>
        <tr><td>50</td><td>Sacyr Social (Servicio de Atención a Domicilio del Ayuntamiento, Getafe)</td><td>2020/04/08</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1248161731748278273">[1]</a></td></tr>
        <tr><td>100</td><td>Hospital Virgen de la Salud (Toledo)</td><td>2020/04/10</td><td></td></tr>
        <tr><td>40</td><td>UME</td><td>2020/04/10</td><td><a href="https://twitter.com/nuria_imeq/status/1250547777366523904">[1]</a></td></tr>
        <tr><td>160</td><td>Hospital Universitario Santa Cristina</td><td>2020/04/10+17</td><td>
            <a href="https://twitter.com/nuria_imeq/status/1250547777366523904">[1]</a>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1250753574260412418">[2]</a>
        </td></tr>
        <tr><td>25</td><td>Residencia Mayores de Griñon</td><td>2020/04/10</td><td></td></tr>
        <tr><td>25</td><td>Hospital Universitario de Móstoles</td><td>2020/04/12</td><td></td></tr>
        <tr><td>100</td><td>Universidad Carlos III de Madrid</td><td>2020/04/13</td><td></td></tr>
        <tr><td>15</td><td>Hospital de Móstoles</td><td>2020/04/13</td><td></td></tr>
        <tr><td>100</td><td>Hospital Ramón y Cajal</td><td>2020/04/14</td><td><a href="https://twitter.com/nuria_imeq/status/1250547777366523904">[1]</a></td></tr>
        <tr><td>33</td><td>Clece SA</td><td>2020/04/14</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1251438739257204736">[1]</a></td></tr>
        <tr><td>100</td><td>Residencias en El Álamo</td><td>2020/04/15</td><td></td></tr>
        <tr><td>100</td><td>Hospital Virgen de la Salud (Toledo)</td><td>2020/04/17</td><td></td></tr>
        <tr><td>30</td><td>Centro Salud Arroyomolinos</td><td>2020/04/17</td><td></td></tr>
        <tr><td>25</td><td>Residencia de Usera</td><td>2020/04/17</td><td></td></tr>
        <tr><td>10</td><td>UVI San Martín de Valdeiglesias</td><td>2020/04/17</td><td></td></tr>
        <tr><td>20</td><td>Bomberos (Leganés)</td><td>2020/04/17</td><td></td></tr>
        <tr><td>10</td><td>Hospital Severo Ochoa (Leganés)</td><td>2020/04/17</td><td></td></tr>
        <tr><td>30</td><td>UCI Hospital Fuenlabrada</td><td>2020/04/17</td><td></td></tr>
        <tr><td>15</td><td>Universidad Carlos III de Madrid (Limpieza)</td><td>2020/04/17</td><td></td></tr>
        <tr><td>30</td><td>IFEMA (Voluntarios)</td><td>2020/04/17</td><td></td></tr>
    </tbody>
    <tfoot>
        <tr>
            <th></th><th></th><th></th><th></th>
        </tr>
    </tfoot>
</table>

<p></p>

## Correas mascarilla entregadas

<table id="example2" class="display" style="width:100%">
    <thead>
        <tr>
            <th>Cantidad</th><th>Ubicación</th><th>Fecha</th><th>RRSS</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>200</td><td>Hospital Universitario Fundación Jiménez Díaz</td><td>2020/04/09</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a>
            <a href="https://twitter.com/Larryancito/status/1248752387218722816">[2]</a>
            <a href="https://twitter.com/nuria_imeq/status/1249647590297284608">[3]</a>
        </td></tr>
        <tr><td>125</td><td>Hospital Universitario 12 de Octubre</td><td>2020/04/09</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a>
            <a href="https://twitter.com/ElenaVA70/status/1248579798571585537">[2]</a>
            <a href="https://twitter.com/davidgmato/status/1248935754329403399">[3]</a>
        </td></tr>
        <tr><td>130</td><td>Hospital Universitario de Móstoles</td><td>2020/04/09+12</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a></td></tr>
        <tr><td>25</td><td>Residencia Monte Hermoso</td><td>2020/04/09</td><td>
            <a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a>
            <a href="https://twitter.com/natxo88/status/1249746483248857088">[2]</a>
        </td></tr>
        <tr><td>100</td><td>Hospital Clinico San Carlos</td><td>2020/04/09</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a></td></tr>
        <tr><td>150</td><td>Hospital La Paz</td><td>2020/04/09+15</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1248304553130328066">[1]</a></td></tr>
        <tr><td>100</td><td>Hospital de Getafe</td><td>2020/04/09</td><td></td></tr>
        <tr><td>100</td><td>Hospital Virgen de la Salud (Toledo)</td><td>2020/04/10</td><td></td></tr>
        <tr><td>30</td><td>Hospital de Móstoles</td><td>2020/04/10</td><td></td></tr>
        <tr><td>100</td><td>Hospital Rey Juan Carlos (Móstoles)</td><td>2020/04/10</td><td></td></tr>
        <tr><td>200</td><td>Hospital Universitario Fundación Alcorcón</td><td>2020/04/10</td><td></td></tr>
        <tr><td>1200</td><td>Hospital Gregorio Marañón</td><td>2020/04/14+16+17</td><td>
            <a href="https://twitter.com/3d_maranon/status/1250010760014630912">[1]</a>
        </td></tr>
        <tr><td>50</td><td>Hospital de Alcorcón</td><td>2020/04/14</td><td></td></tr>
        <tr><td>250</td><td>Residencia Personas Mayores de Villaviciosa de Odón</td><td>2020/04/15</td><td></td></tr>
        <tr><td>100</td><td>Hospital Virgen de la Salud (Toledo)</td><td>2020/04/17</td><td></td></tr>
        <tr><td>40</td><td>Centro Salud Arroyomolinos</td><td>2020/04/17</td><td></td></tr>
        <tr><td>25</td><td>Residencia de Usera</td><td>2020/04/17</td><td></td></tr>
        <tr><td>100</td><td>Hospital Universitario Santa Cristina</td><td>2020/04/17</td><td></td></tr>
        <tr><td>100</td><td>Hospital Carlos III</td><td>2020/04/17</td><td></td></tr>
        <tr><td>200</td><td>Hospital Gómez Ulla</td><td>2020/04/17</td><td></td></tr>
        <tr><td>30</td><td>Residencia Monte Hermoso</td><td>2020/04/17</td><td></td></tr>
        <tr><td>100</td><td>Instituto Psiquiátrico José Germain (Leganés)</td><td>2020/04/17</td><td><a href="https://twitter.com/uc3mRoboticsLab/status/1251497914653966336">[1]</a></td></tr>
        <tr><td>30</td><td>UVI 20 San Martín de Valdeiglesias</td><td>2020/04/17</td><td></td></tr>
    </tbody>
    <tfoot>
        <tr>
            <th></th><th></th><th></th><th></th>
        </tr>
    </tfoot>
</table>

