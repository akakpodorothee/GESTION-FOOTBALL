# gestion-football


    Ce projet consiste à créer un API REST pour la gestion des statistiques des joueurs  de foot de l'équipe nationale du Togo.

          POUR CONSTRUIRE UNE API RESTfUl,NOUS AVONS UTILISES :

                .Node JS
                .Express.js-framework Web rapide, sans opinion et minimaliste pour Node.js


    PACKAGGES INSTALLES:
           
           .nvm - Node Version Manager
           .npm - node Package Manager
           .Node.js
           .Express installé avec npm 

     COMMENT UTILISE:

     .POST https://whispering-forest-65829.herokuapp.com/api/v1/stats/(le id)
          
          ce lien permettra de créer les statistiques d'un joueur
           
           // exemple d'entrée
             {
                "id": 145,
                "wins": 5,
                "losses": 1,
                "points_scored": 14
                }

             // le fichier json serait comme celui-ci

                   {
                    "id": 145,
                    "wins": 5,
                    "losses": 1,
                    "points_scored": 14
                    },

      .GET https://whispering-forest-65829.herokuapp.com/api/v1/stats
                
                ce lien permettra d'obtenir les statistiques du joueur 145

              //  le fichier json serait comme suit:

                 {
                     "id": 145,
                    "wins": 5,
                    "losses": 1,
                    "points_scored": 14
                    },

       .PUT https://whispering-forest-65829.herokuapp.com/api/v1/stats/(id)

       ce lien mettra à jour les statistiuques  du joueur 27

                {
                    "id": 27,
                    "wins": 14,
                    "losses": 26,
                    "points_scored": 28
                    }

       le fichier json serait comme suit:

            {
                "id": 27,
                "wins": 14,
                "losses": 26,
                "points_scored": 28
                }

        .DELETE https://whispering-forest-65829.herokuapp.com/api/v1/stats/(id) 

             ce lien effacera les statistiques du joueur 1O1 

             // l'Entrée

                  {
                    "id": 101,
                    "wins": 10,
                    "losses": 3,
                    "points_scored": 7
                  }

              //  le fichier json serait vide  








