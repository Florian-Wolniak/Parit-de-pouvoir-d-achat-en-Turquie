# Parité de pouvoir d'achat en Turquie
Ce projet évalue empiriquement la validité de la Parité du Pouvoir d'Achat pour la Turquie sur la période 2000-2025. À travers une modélisation économétrique en R, l'étude teste la PPA absolue et relative via des tests de stationnarité et des régressions en différences premières sur les indices de prix à la consommation et à la production.

## Objectif
L'enjeu principal de ce projet est de déterminer et de comprendre la sensibilité du taux de change nominal du livre turc, en fonction du différentiel d'inflation entre la Turquie et ses partenaires commerciaux disposant d'une devise étrangère. 
La Turquie a été choisi principalement pour son inflation chronique, la forte volatilité de sa monnaie et pour son récent développement international.

## Données
Nous utiliserons des données récentes provenant de la banque des règlements internationaux pour les taux de changes bilatéraux, ou encore du FMI pour les indices de prix à la consommation et à la production. L'étude couvre le premier trimestre de l'année 2000 jusqu'au troisième trimestre de 2025. 

## Méthodologie 
Pour cette études nous utiliserons la méthode de régression par les moindres carrés ordinaires pour tester l'hypothèse de PPA absolue. Nous utiliserons ensuite un test ADF afin de tester la non-stationnarité du taux de change nominal du livre turc et des indices de prix. Enfin nous utiliserons aussi un test de Ljung-Box, qui a permis de détecter une autocorrélation résiduelle dans les modèles en niveau, corrigée par la suite via l'estimateur robuste de Newey-West (HAC)



