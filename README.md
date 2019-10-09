NaN_event groupe 2
nombre de tables: 10

Admins(
	id, 
	email, 
	password, 
	profile_pic, 
	username, 
)

Categories(
	id, 
	name
) 

Commune(
	id, 
	name, 
	#ville_id
)

Events(
	id, 
	titre, 
	description, 
	datetime, 
	lien_gmap, 
	commune_id, 
	ville_id, 
	prix, 
	lieu, 
	#admin_id, 
)

EventCatgories(
	#event_id,category_id
)


Images(
	id, 
	path,
	#event_id
)


Interesser(
	#user_id,event_id
)


Participer(
	#user_id,event_id
)

Ville(
	id, 
	name
)

Users(
	id, 
	email, 
	password, 
	username, 
	photo
)
