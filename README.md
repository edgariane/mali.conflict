<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Popup-Fenster</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(128, 128, 128, 0.5); /* Grau, durchsichtig */
            justify-content: center;
            align-items: center;
        }
        .popup {
            background-color: #fff; /* Weiß */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5); /* Schwarzer Schatten */
            text-align: center;
        }
        .popup a {
            color: #1E90FF; /* Blau */
            text-decoration: underline;
            cursor: pointer;
        }
        .popup a:hover {
            color: #000; /* Schwarz */
        }
        .popup button {
            margin: 10px;
            padding: 8px 15px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .popup #okButton {
            background-color: #000; /* Schwarz */
            color: #fff; /* Weiß */
        }
        .popup #cancelButton {
            background-color: #000; /* Schwarz */
            color: #fff; /* Weiß */
        }
    </style>
</head>
<body>

<div class="overlay" id="popupOverlay">
    <div class="popup">
        <p>Mit dem Klick auf "<a href="Fehler.html" target="_self">Nutzungsbedingungen</a>" und "<a href="Fehler.html" target="_self">Richtlinien</a>" akzeptieren Sie diese.</p>
        <button id="okButton" onclick="closePopup()">OK</button>
        <button id="cancelButton" onclick="redirectAndClose()">Abbrechen</button>
    </div>
</div>

<script>
    function openPopup() {
        document.getElementById("popupOverlay").style.display = "flex";
    }

    function closePopup() {
        document.getElementById("popupOverlay").style.display = "none";
    }

    function redirectAndClose() {
        window.location.href = 'DAann Nicht.html'; // Ersetze mit der URL deines GIFs
        setTimeout(function() {
            window.open('', '_self', ''); // Öffne ein leeres Fenster im aktuellen Tab
            window.close(); // Schließe das aktuelle Fenster
        }, 5); // Schließe die Seite nach 5 Sekunden (kann je nach GIF-Länge angepasst werden)
    }
</script>
<script>
    window.onload = openPopup;
</script>
</body>

---------------------------------------------------INHALT DER SEITE----------------------------------------------------------------
<body>
    <h2>Inhalt:</h2>
    <nav>
        <a href="#Einführung in den Autoritarismus">Einführung in den Autoritarismus</a> <br>
        <a href="#Merkmale des Autoritarismus">Merkmale des Autoritarismus</a> <br>
        <a href="#Typen des Autoritarismus">Typen des Autoritarismus</a> <br>
        <a href="#Ursachen und Faktoren des Autoritarismus">Ursachen und Faktoren des Autoritarismus</a> <br>
        <a herf="#Auswirkungen des Autoritarismus">Auswirkungen des Autoritarismus</a>
        <a herf="#Bekämpfung von Autoritarismus">Bekämpfung von Autoritarismus</a>
        <a herf="#Beispiele autoritärer Regime">Beispiele autoritärer Regime</a>
        <a herf="#Aktuelle Entwicklungen und Herausforderungen">Aktuelle Entwicklungen und Herausforderungen</a>
        <a herf="#Quellen und weiterführende Literatur">Quellen und weiterführende Literatur</a>
        <a herf="#FAQs zum Autoritarismus">FAQs zum Autoritarismus</a>
    </nav>
    <main>
        <div class="1anfang">
            <h2>Autoritarismus</h2>
        </div>
<section id="Einführung in den Autoritarismus">
</section>
<section id="Merkmale des Autoritarismus">
</section>
<section id="Typen des Autoritarismus">
</section>
<section id="Ursachen und Faktoren des Autoritarismus">
</section>
<section id="Auswirkungen des Autoritarismus">
</section>
    
<section id="Bekämpfung von Autoritarismus">
            <h2>Was hatt das mit Pakistan zu tun?</h2>
        </section>
<section id="Beispiele autoritärer Regime">
    <h2>Infos über Pakistan</h2>
</section>
<section>
<section id="Aktuelle Entwicklungen und Herausforderungen">
    <h2>...</h2>
</section>
<section id="Quellen und weiterführende Literatur">
    <h2>Quellen</h2>
</section>
<section id="FAQs zum Autoritarismus">
</section>
    <footer>
        <a href="Rick Astley - Never Gonna Give You Up (Official Music Video).mp4">Quellen</a>
        <p>&copy; 2024 Millitärisches Verfassungsschema</p>
    </footer>
<html>
