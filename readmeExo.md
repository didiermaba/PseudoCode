# TP OF (Organisme de formation)

Prépavenir a besoinn d'1 système de gestion pr les demandes
d'inscriptions aux aux formations du catalogue.

### Le catalogue

- Développeur Web et Web Mobile
- Concepteur Développeur d'Applications
- Webdesigner
- Référencement SEO

Le programme sera utilité par 2 pes (1 admin et 1 assistant),
l'objetif étant de faciliter la gestion du processus d'inscription des futurs élèves.


Prise de notes :
```
Candidat:

Le stagiaire visite le site de l'organisme de formation
    S'il ne trouve pas sa formation
        Il abandonne sa recherche
        Et le programme s'arrete 
    si jamais il trouve la formation souhaitée
        Alors il fait sa dmde d'inscription
        Et il recoit en retour l'accusé de réception de sa candidature

Traitement de dmde d'inscription par l'organisme
    Vérification de disponibilités pour la formation choisie 
        SI place disponible 
            l'organisme prend contact avec le stagiaire par mail retour pour la suite
        SINON, place indisponible
            Notifier au candidat que les places ne sont plus dispo.
            Et le dossier est cloturé 

Demande de docs à fournir pour l'inscription
    Vérification du dossier
        Si le dossier est valide
            Le candidat peut alors acceder au test d'admission
                Si le candidat reussit au test
                    candidature retenue
                    Et recoit la confirmation de son inscription 
                SINON, le candidat échoue au test 
                    Et le dossier est cloturé
        SINON, le dossier est invalide
            La candidature n'est pas retenue
            et le dossier est cloturé  

Admin : 

L'administrateur et son assistant ont chacun un compte admin 

L'admin ayant plus de responsabilités,il a accès à certains fichiers de son assistant

L'assistant ou l'admin postent les annonces des sessions organisées par l'organisme 

