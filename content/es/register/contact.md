---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

title: Contacto

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

---

<form name="izenematea" method="post" data-netlify="true" action="/eu/thankyou/">
  <div class="form-group form-inline">
    <label class="sr-only" for="inputName">Nombre</label>
    <input type="text" name="name" class="form-control w-100" id="inputName" placeholder="Izena" required="">
  </div>
  <div class="form-group form-inline">
    <label class="sr-only" for="inputEmail">Email</label>
    <input type="email" name="email" class="form-control w-100" id="inputEmail" placeholder="Email" required="">
  </div>
  <div class="form-group">
    <label class="sr-only" for="inputMessage">¿Qué mensaje nos quieres enviar?</label>
    <textarea name="message" class="form-control" id="inputMessage" rows="5" placeholder="Mezua" required=""></textarea>
  </div>
  <button type="submit" class="btn btn-outline-primary px-3 py-2">Enviar</button>
</form>
