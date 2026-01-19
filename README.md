<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <title>Negozio Piscine - Ricambi</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; background: #f0f8ff; }
        header { text-align: center; padding: 20px; background: #0099cc; color: white; }
        h1 { margin: 0; }
        section { margin: 20px 0; padding: 20px; background: white; border-radius: 8px; }
        a { color: #0099cc; text-decoration: none; }
        footer { text-align: center; margin-top: 40px; color: gray; }
        input, textarea, button { padding: 10px; margin-top: 5px; width: 100%; }
    </style>
</head>
<body>
    <header>
        <h1>Negozio Piscine - Ricambi</h1>
        <p>Il tuo negozio online di pezzi di ricambio per piscine</p>
    </header>

    <section>
        <h2>Preventivi Personalizzati</h2>
        <form action="mailto:tuo-email@example.com" method="post" enctype="text/plain">
            <label>Nome:</label>
            <input type="text" name="nome" required>
            <label>Email:</label>
            <input type="email" name="email" required>
            <label>Richiesta:</label>
            <textarea name="richiesta" rows="5" required></textarea>
            <button type="submit">Invia Preventivo</button>
        </form>
    </section>

    <section>
        <h2>Prodotti in Vendita</h2>
        <ul>
            <li>Filtro piscina - €50</li>
            <li>Pompa acqua - €120</li>
            <li>Skimmer - €35</li>
            <li>Cloro e trattamenti - vari prezzi</li>
        </ul>
    </section>

    <footer>
        &copy; 2026 Negozio Piscine - Tutti i diritti riservati
    </footer>
</body>
</html>
