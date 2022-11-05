---
title: 'Contáctanos '
permalink: "/contact.html"

---
<form action="https://formspree.io/{{site.email}}" method="POST">  
<p class="mb-4">Por favor, envía tu mensaje a {{site.name}}. ¡Nosotros responderemos tan pronto como sea posible!</p> <div class="form-group row"> <div class="col-md-6"> <input class="form-control" type="text" name="name" placeholder="Nombre_" required> </div> <div class="col-md-6"> <input class="form-control" type="email" name="replyto" placeholder="Dirección de E-mail*" required> </div> </div> <textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensaje_*" required></textarea>  
<input class="btn btn-success" type="submit" value="Enviar"> </form>