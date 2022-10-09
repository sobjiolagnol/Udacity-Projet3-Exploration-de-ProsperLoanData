# (Dataset Exploration ProsperLoanData)
## by SOBJIO Ludane Lagnol


## Dataset

> Dans ce projet, nous allons explorer les données des prêts Prosper qui contiennent des informations sur 113937 prêts effectués par Prosper entre 2005 et 2014. Pour les besoins de 
ce projet, nous imaginerons que nous sommes un concurrent de Prosper et nous tenterons d'utiliser ces données pour prédire le taux d'intérêt qu'un emprunteur potentiel se verrait
 proposer par Prosper afin de pouvoir offrir un taux légèrement moins cher.

Selon Wikipedia, Prosper est le premier prêteur de pair à pair d'Amérique dans lequel les emprunteurs demandent des fonds et d'autres individus et institutions peuvent financer ces
 demandes de prêt. Bien que les prêts Prosper aient été initialement mis aux enchères, depuis juillet 2009, les taux sont fixés par le modèle Prosper et les prêteurs peuvent choisir 
de financer ou non le prêt. Prosper détermine ses taux à l'aide d'un score de crédit traditionnel et de son propre score propriétaire Prosper basé sur ses propres données historiques.

## Summary of Findings

Lors de l'exploration, j'ai constaté que le TAEG de l'emprunteur est négativement corrélé au montant du prêt initial. Pour différents montants de prêt, le TAEG a une large fourchette,
 mais la fourchette du TAEG diminue avec l'augmentation du montant du prêt. Le TAEG de l'emprunteur diminue également avec l'amélioration de la notation. Les emprunteurs ayant la meilleure 
notation Prosper ont le TAP le plus bas. Cela signifie que la notation de Prosper a un effet important sur le TAEG de l'emprunteur. Il est intéressant de noter que la relation entre le TAEG de l'emprunteur et le montant du prêt passe de négative à légèrement positive lorsque les notes de Prosper passent de HR à A ou mieux. Cela peut s'expliquer par le fait que les personnes ayant une note A ou AA ont tendance à emprunter plus d'argent, l'augmentation du TAEG pourrait les empêcher d'emprunter encore plus et de maximiser le profit. En revanche, les personnes dont la note est plus basse ont tendance à emprunter moins d'argent, et une baisse du TAEG pourrait les encourager à emprunter davantage. J'ai également constaté que le TAEG de l'emprunteur diminue avec l'augmentation de la durée de l'emprunt pour les personnes ayant une notation HR-C. Mais pour les personnes ayant une notation B-AA, le TAEG est plus élevé. Mais pour les personnes ayant des notes B-AA, le TAEG augmente avec l'augmentation de la durée de 
l'emprunt.

En dehors des principales variables d'intérêt, j'ai constaté que le montant du prêt est positivement corrélé avec le revenu mensuel déclaré, ce qui est logique puisque les emprunteurs
 ayant un revenu mensuel plus élevé peuvent prêter plus d'argent. Le montant du prêt augmente également avec l'augmentation de la durée du prêt. J'ai également constaté que les emprunteurs
 ayant une meilleure notation ont un revenu mensuel et un montant de prêt plus élevés. Les emprunteurs salariés, indépendants et à temps plein ont un revenu mensuel et un montant de prêt 
plus élevés que les emprunteurs à temps partiel, retraités et sans emploi. Il existe une interaction entre le terme catégorique et les caractéristiques de notation de Prosper.
 Proportionnellement, il y a plus de prêts à 60 mois sur les notations B et C. Il n'y a que des prêts de 36 mois pour les emprunteurs de la catégorie HR. Pour le montant du prêt,
 il y a une interaction entre la durée et la notation. Plus la note de Prosper est élevée, plus le montant du prêt augmente dans les trois catégories, et plus l'amplitude de l'augmentation
 du montant du prêt entre les catégories est importante.




## Key Insights for Presentation

Pour la présentation, je me concentre sur les caractéristiques qui pourraient affecter le TAEG de l'emprunteur, à savoir le montant initial du prêt et la notation Prosper.
 J'ai commencé par montrer la distribution du TAEG de l'emprunteur et la variable du montant du prêt. Ensuite, j'ai montré la relation entre le TAEG et le montant du prêt, 
ainsi que le TAEG et la notation. J'ai également étudié l'effet de la notation sur la relation entre le TAEG et le montant du prêt, ainsi que l'effet de la notation sur la 
relation entre le TAEG de l'emprunteur et la durée du prêt.

