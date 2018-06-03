---
layout   : default
permalink: design/ui-style-guide/formulieren/
published: true
# Custom Page Variables
# ─────────────────────
title: Formulieren
---
Je moet maar één keer een formulier invullen en dat is op de smartphone-app:

Registratie
------------
{: .witruimte}

<form>
    <div class="form-group">
        <label for="InputName">Naam</label>
        <input type="name" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Leïla Minne">
    </div>
    <div class="form-group">
        <label for="InputEmail">E-mailadres</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="leilaminne@gmail.com">
    </div>
    <div class="form-group">
        <label for="InputPassword">Wachtwoord</label>
        <input type="password" class="form-control" id="exampleInputPassword1" aria-describedby="emailHelp" placeholder="Wachtwoord">
    </div>
    <div class="form-group">
        <label for="InputPassword">Wachtwoord bevestigen</label>
        <input type="password" class="form-control" id="exampleInputPassword1" aria-describedby="emailHelp" placeholder="Wachtwoord">
    </div>
 </form>

Inloggen
---------
{: .witruimte}

<form>
    <div class="form-group">
        <label for="InputEmail">E-mailadres</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="leilaminne@gmail.com">
    </div>
    <div class="form-group">
        <label for="InputPassword">Wachtwoord</label>
        <input type="password" class="form-control" id="exampleInputPassword1" aria-describedby="emailHelp" placeholder="Wachtwoord">
        <small id="emailHelp" class="form-text text-muted">
            <a href="#">Uw wachtwoord vergeten?</a>
        </small>
    </div>
 </form>