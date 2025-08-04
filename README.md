<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YAKUZA - Fraktion</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="hero">
        <div class="overlay"></div>
        <div class="content">
            <img src="images/logo.png" alt="Yakuza Logo" class="logo">
            <h1>山口組 - Die Familie der Ehre</h1>
            <p>„強さと名誉の道“<br><span>– Der Weg von Stärke und Ehre –</span></p>
        </div>
    </div>
    <section class="about">
        <h2>Über Uns</h2>
        <p>Wir sind die YAKUZA – eine traditionsreiche, tief organisierte Familie aus dem Untergrund. 
        Unsere Leidenschaft für Roleplay hat uns von den dunklen Straßen Tokyos bis in die Metropole Los Santos geführt. 
        Viele unserer Brüder stammen aus alten Zeiten auf GVMP und SIBAUI, wo Loyalität, Ehrgefühl und Disziplin unser Spiel prägten.
        Jetzt bringen wir diese Werte in eine neue Ära.</p>
    </section>
    <section class="history">
        <h2>Unsere Geschichte</h2>
        <p>Die Yakuza – ursprünglich im 17. Jahrhundert in Japan aus fahrenden Glücksspielern und Straßenkriegern entstanden – 
        hat über Jahrhunderte hinweg eine Struktur aufgebaut, die auf Ehre, Loyalität und Tradition basiert. 
        Mit dem zunehmenden Einfluss westlicher Syndikate und dem Zerfall alter Allianzen entstand der Plan, 
        neue Wurzeln in der „Stadt der Sünde“ zu schlagen: Los Santos. 
        Unter dem Deckmantel von Diskretion, Disziplin und maximaler Effizienz entstand eine Zelle, die sich rasch durch 
        illegale Geschäfte, Netzwerkbildung und gezielte Gewalt etablierte.
        Heute ist die YAKUZA mehr als eine Gang – sie ist eine Familie. Unsere Basis? Diskretion. Unsere Waffe? Vertrauen.
        Unsere Mission? Kontrolle.</p>
    </section>
</body>
</html>


# Basic CSS styling for the page
style_css = """
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    color: white;
    background-color: #0d0d0d;
}

.hero {
    position: relative;
    background: url('../images/bg.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.overlay {
    position: absolute;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.7);
    z-index: 1;
}

.content {
    position: relative;
    z-index: 2;
}

.logo {
    width: 150px;
    margin-bottom: 20px;
}

h1 {
    font-size: 3em;
    color: #ff0000;
}

p span {
    color: #aaa;
    font-style: italic;
}

section {
    padding: 40px 20px;
    max-width: 1000px;
    margin: 0 auto;
}

h2 {
    color: #ff0000;
    font-size: 2em;
    margin-bottom: 10px;
}
