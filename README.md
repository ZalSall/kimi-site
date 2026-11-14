<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KIMI - Enquête</title>
<style>
body{font-family:Arial;background:#0f0f0f;color:white;display:flex;justify-content:center;padding:20px;margin:0}
.card{background:white;color:#111;border-radius:16px;padding:28px;width:100%;max-width:420px}
h1{margin:0 0 5px}
input,textarea{width:100%;padding:12px;border:1px solid #ddd;border-radius:10px;margin:8px 0 16px;box-sizing:border-box}
button{width:100%;padding:14px;background:#111;color:white;border:none;border-radius:10px;font-weight:bold}
</style>
</head>
<body>
<div class="card">
<h1>Enquête KIMI</h1>
<p>Ton avis compte. 30 secondes.</p>
<form action="https://formspree.io/f/mbgodbqg" method="POST">
<label>Ton prénom</label>
<input type="text" name="prenom" required>
<label>Ton jeu préféré</label>
<input type="text" name="jeu_prefere" required>
<label>Ton avis</label>
<textarea name="avis"></textarea>
<button type="submit">Envoyer →</button>
</form>
</div>
</body>
</html>
