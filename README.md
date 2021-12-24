<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>mon formulaire</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <!--<div class="contact-wrapper">
		 <div class="form-horizontal">
			<h1 class="section-header">Posez-nous vos questions !</h1>
			<p>Nom</p>
			<p>Email</p>
			<p>Téléphone</p>
			<p>Catégorie de question</p>
			<p>Message</p>
			<div class="send-button">Envoyer</div>
			<div class="advert-wrapper">
				<p>Souhaitez-vous recevoir nos news ?</p>
			</div>
		</div>
	 </div>-->
   <form 
   method="post" 
   action="action.php.">

     <label for="name">nom</label>
     <input type="text" id="name" name="name" placeholder="saisissez votre nom">

     <label for="date">Date de naissance</label>
     <input type="date" id="date" name="birthdate" placeholder="saisissez votre date de naissance">

     <label for="comment">commentaire</label>
     <textarea rows="4" name="comment" placeholder="ajoutez votre commentaire"></textarea>

     <label for="email">votre adresse mail</label>
     <input type="email" id="email" name="email" placeholder="saisissez votre adresse mail">
   </form>
    
  </body>
</html>
