
# Partie 1 :Deployyer l'application avec serveur ServeurJaxWS

### Deployer le web service :
![c1](https://user-images.githubusercontent.com/82270887/163588617-700b1759-00d2-4563-b320-1de097f23ea9.png)
### consulter le web service avec un browser Http :
l'url de service http:/:localhost:8686/BanqueWS?wsdl?
le serveur n'est plus accessible que dans le localhost
![c2](https://user-images.githubusercontent.com/82270887/163588788-a87cd1e1-b8a0-4261-89e3-504762ff0f75.png)

### consulter le wsdl avec SOAP :
le wsdl contient les methodes suivantes 

![c3](https://user-images.githubusercontent.com/82270887/163589297-657b63ee-3778-4197-9941-f28ce5f11413.png)
### test de la méthode conversionEuroToDh
on remarque que lorsque on envoi le montant et en envoi la requet vers le web servcice ,le web service fait des traitement et il envoi une réponse en format Xml

![c4](https://user-images.githubusercontent.com/82270887/163589597-64d5754a-2998-4f4a-a335-72b65652408b.png)
 pour verifier les autres méthodes on fait le même travail
 # Partie 2 : Créer un autre projet ClientWS et le communiquer avec le projet TPWebService
 à partir du WSDL on génère des classes et des interfaces qu'on va utiliser pour communiquer  avec le webService
 resultat de test 
 ![c6](https://user-images.githubusercontent.com/82270887/163591134-5bd05bda-2c48-4715-957a-f2b055d2520f.png)
