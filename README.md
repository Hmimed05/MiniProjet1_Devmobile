# MiniProjet1_Devmobile
Mini Projet 1 de Module Développement Mobile

<h4> La technologie utilisée : Java / Android studio  </h4>


<h2> L'harchitecture du projet :  </h2>
    
     Le projet se compose de 5 classe : 
      => MainActivity.java : qui est présentée à l'utilisateur lorsque l'application est lancée. L'activité principale peut alors démarrer d'autres activités pour effectuer différentes actions.  
        => Transaction.List.java : classe qui gére les transactions d'utilisateurs . 
         => Transaction.Activity.java : qui est présentée à l'utilisateur lorsqu'il demande les transaction
          => TransferActivity.java : qui est présentée à l'utilisateurs lorsqu'il fait une transaction de transfert(debit)
           => Classe Transaction : classe pour créer les transactions 
<h2> Affichage d'application sur le simulateur :  </h2>

  * le solde choisie aléatoirement (entre 5000 et 10000 DH ) avec une fonction random <br>
  ![photo1](https://user-images.githubusercontent.com/65094783/103952520-d77d4500-5140-11eb-9a43-ef7b63c883f7.PNG) <br>
   * Quand l'utilisateur clique sur Débit , il demande d'entrée le montant qui peut transférer et gére les contraintes suivant : 
 ![photo4](https://user-images.githubusercontent.com/65094783/103953090-c6810380-5141-11eb-90e3-a13b9fe2b120.PNG)  <br>

       - - - L'application n'accepte pas le zéro  <br>
    
![photo3](https://user-images.githubusercontent.com/65094783/103952601-fda2e500-5140-11eb-9de0-97e3cb71b464.PNG) <br>
       - - - L'application vérifie que le montant est moins de solde <br>
)
 ![photo2](https://user-images.githubusercontent.com/65094783/103952554-e663f780-5140-11eb-8989-543ebef681ed.PNG) <br>
   *Quand le transfert se passe , l'application retourne à la page d'acceuille<br>
 ![photo5](https://user-images.githubusercontent.com/65094783/103952685-1e6b3a80-5141-11eb-97e5-112cd9075b74.PNG) <br>

   * Les listes de transactions s'affiche de la maniére suivante <br>
![photo6](https://user-images.githubusercontent.com/65094783/103952720-2925cf80-5141-11eb-860a-2d7b2c5a1977.PNG) <br>
