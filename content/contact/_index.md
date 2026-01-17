---
title: "Contact"
description: "Une question ? Une collaboration ? Écrivez-moi."
layout: "simple"
---

<div class="contact-container">
  
  <p class="contact-intro">
    Contactez-moi pour toutes demandes
  </p>

  <form action="https://formspree.io/f/mvzzzrzv" method="POST" class="contact-form">
    
<div class="form-group">
      <label for="name">Votre Nom</label>
      <input type="text" id="name" name="name" placeholder="Jean Dupont" required>
    </div>

 <div class="form-group">
      <label for="email">Votre Email</label>
      <input type="email" id="email" name="email" placeholder="jean@exemple.com" required>
    </div>

<div class="form-group">
      <label for="message">Votre Message</label>
      <textarea id="message" name="message" rows="6" placeholder="Bonjour Dylan..." required></textarea>
    </div>

<button type="submit" class="gear-btn submit-btn">Envoyer le message</button>
  </form>

</div>