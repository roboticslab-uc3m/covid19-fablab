# covid19-fablab

## Pantallas protectoras entregadas


<link rel="stylesheet" href="https://cdn.datatables.net/1.10.20/css/jquery.dataTables.min.css">

<script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js"></script>

<script type="text/javascript">
$(document).ready(function() {
    $('#example').DataTable({"paging": false, "searching": false, "info": false});
} );
</script>


<table id="example" class="display" style="width:100%">
    <thead>
        <tr>
            <th>Cantidad</th>
            <th>Ubicación</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>100</td><td>Hospital Severo Ochoa</td></tr>
        <tr><td>100</td><td>Hospital Fundación San José</td></tr>
        <tr><td>50</td><td>Hospital de campaña Leganés</td></tr>
        <tr><td>50</td><td>Policía municipal de Leganés</td></tr>
        <tr><td>30</td><td>Hospital Ramón y Cajal</td></tr>
        <tr><td>25</td><td>Protección civil Leganés</td></tr>
        <tr><td>25</td><td>Residencia Orpea Villanueva de la Cañada</td></tr>
        <tr><td>14</td><td>Seguridad Universidad</td></tr>
        <tr><td>12</td><td>Bomberos Leganés</td></tr>
    </tbody>
</table>
