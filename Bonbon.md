début fonction calculBonbon

argentDispo <- lireRéel
prixBonbon <- lireRéel

quantitéBonbonAchetable <- 0
totalDépensé <- 0

Si argentDispo > 0 et prixBonbon > 0
   Tant que totalDépensé <= (argentDispo - prixBonbon)
      quantitéBonbonAchetable <- quantitéBonbonAchetable + 1
      totalDépensé <- totalDépensé + prixBonbon
   Fin Tant que
   Retourner quantitéBonbonAchetable
Fin si

fin fonction
