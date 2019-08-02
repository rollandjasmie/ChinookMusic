# ChinookMusic
# README
Projet Chinoo kMusic


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
  
  
           Niveau facile


Quel est le nombre total d'objets Album contenus dans la base (sans regarder les id bien sûr) ?
   	
	347

Qui est l'auteur de la chanson "White Room" ?
  	
	Eric Clapton

Quelle chanson dure exactement 188133 milliseconds ?
  	
	Derfect

Quel groupe a sorti l'album "Use Your Illusion II" ?
	
	Guns N Roses


b) Niveau Moyen



Combien y a t'il d'albums dont le titre contient "Great" ? (indice)
  
  Track.where("title LIKE ?", "%Great%").count

Supprime tous les albums dont le nom contient "music".

Combien y a t'il d'albums écrits par AC/DC ?
	
	Track.where("artist LIKE ?", "%AC/DC%").count

Combien de chanson durent exactement 158589 millisecondes ?
	
	Track.where("duration LIKE ?", "%158589%").count
