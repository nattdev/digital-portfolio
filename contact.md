---
layout: page
title: Contacto
permalink: /contacto/
---
<div class="contact">
<p class="contact__description-text">Si tienes preguntas o deseas solicitar un presupuesto para tu proyecto, por favor completa el formulario de contacto que aparece a continuación y me pondré en contacto contigo a la brevedad posible.

<span>¡Espero trabajar contigo pronto!</span></p>

<form id="test-form" class="contact__form" action="https://formsubmit.co/2d4ec375b9aa6e62790b433a40a35fa4" method="POST">
		<label for="name">Nombre</label>
     <input type="text" name="name" required>
	  <label for="email">Email</label>
     <input type="email" name="email" pattern="[a-zA-Z0-9!#$%&'*_+-]([\.]?[a-zA-Z0-9!#$%&'*_+-])+@[a-zA-Z0-9]([^@&%$\/()=?¿!.,:;]|\d)+[a-zA-Z0-9][\.][a-zA-Z]{2,4}([\.][a-zA-Z]{2})?" required>
	   <label for="message">Mensaje</label>
		 <textarea type="text" name="message" required></textarea>
		 <input type="hidden" name="_next" value="https://nattdev.github.io/digital-portfolio/success-message/">
		 <input type="hidden" name="_captcha" value="false">
     <button class="contact__description-button" type="submit">Enviar</button>
</form>

</div>
