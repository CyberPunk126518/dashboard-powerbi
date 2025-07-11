<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actualización Automática del Iframe</title>
    <script>
        function reloadIframe() {
            document.getElementById('myIframe').src += '';
        }
        setInterval(reloadIframe, 1800000); // 1800000 ms = 30 minutos
    </script>
</head>
<body>
    <iframe id="myIframe" title="CIM FS MEL" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=30797f2b-e0b9-4d8f-88ea-4244ca25d92f&amp;autoAuth=true&amp;ctid=800848b6-54e6-473a-9e41-5f170af0e0

