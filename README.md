# MLP_UGE
Voici une explication des différents fichiers nécessaire à l'utilisation du MLP : 

  1- MLP_[P_,T_,ETP_,RAD_]_Gradient.ipynb : MLP pour les données ERA5.
    data_full_Alsace_['P_', 'T_', 'ETP_', 'RAD_']_10000.txt : Les données temporalisées ERA5 (7j, 8s, 6m)
    adapt_Alsace.txt : Les données non temporalisées ERA5 et la piézo.
  
  3- MLP_[Humid_,]_Tempo.ipynb : MLP pour les données Safran en serie temporalisée.
    DataSafran_Alsace_['Pluie_Liq','ETR','Humid_sol','Drain']_19500.txt : Les données temporalisées Safran (7j, 8s, 24m).
    adapt_Alsace_Safran.txt : Les données non temporalisées ERA5 et la piézo.
    
  3- MLP_[Humid_,]_.ipynb : MLP pour les données Safran en serie non temporalisée (meilleurs résultats sur Safran).
    adapt_Alsace_Safran.txt : Les données non temporalisées ERA5 et la piézo.
