<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pianoroth</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; background-color: #f7f9fa; color: #2c3e50; text-align: center; }
        .container { max-width: 800px; margin: 50px auto; padding: 20px; }
        h1 { font-size: 2.5em; margin-bottom: 20px; }
        p { font-size: 1.2em; color: #7f8c8d; }
        .contact-box { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); display: inline-block; margin-top: 30px; text-align: left; }
        footer { margin-top: 100px; font-size: 0.9em; border-top: 1px solid #dcdde1; padding-top: 20px; color: #7f8c8d; }
        .impressum { text-align: left; max-width: 600px; margin: 20px auto; display: none; background: #fff; padding: 20px; border: 1px solid #dcdde1; }
    </style>
    <script>
        // Eine simple Funktion, um das Impressum per Klick ein- und auszublenden
        function toggleImpressum() {
            var x = document.getElementById("impressum-content");
            if (x.style.display === "block") { x.style.display = "none"; } 
            else { x.style.display = "block"; }
        }
    </script>
</head>
<body>

    <div class="container">
        <h1>Willkommen bei pianoroth</h1>
        <p>Diese Website befindet sich aktuell im Aufbau.</p>

        <div class="contact-box">
            <h3>Kontakt</h3>
            <p><strong>E-Mail:</strong> service@pianoroth.de</p>
            <p>Seien Sie gespannt wie eine Saite.</p>
        </div>

        <footer>
            <p>&copy; 2026 pianoroth. Alle Rechte vorbehalten.</p>
            <p><a href="#" onclick="toggleImpressum(); return false;" style="color: #2980b9; text-decoration: none;">Impressum & Datenschutz</a></p>
            
            <div id="impressum-content" class="impressum">
                <h4>Impressum</h4>
                <p><strong>Angaben gemäß § 5 DDG:</strong></p>
                <p>[Jurek] [Roth]<br>
                [Ecksteinstraße 42]<br>
                [04277] [Leipzig]</p>
                <p><strong>Kontakt:</strong><br>
                E-Mail: service@pianoroth.de</p>
                <p><strong>Verantwortlich für den Inhalt nach § 18 Abs. 2 MStV:</strong><br>
                [Jurek] [Roth]<br>
                [Ecksteinstr. 42, 04277 Leipzig]</p>
            </div>
        </footer>
    </div>

</body>
</html>
