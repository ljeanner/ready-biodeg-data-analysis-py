
<h1> QSAR biodegradation Data Set  </h1> <ul>
https://archive.ics.uci.edu/ml/datasets/QSAR+biodegradation#
</ul>

Par <em>Lucile Jeanneret </em>
<h2>L’objet du devoir est de mettre en pratique les différentes compétences nécessaires au métier de data-scientist, vues en cours cette année :</h3>
<ul>
<li>Data-visualisation</li>
<li>Modélisation</li>
<li>Usage de Git</li>
</ul>
<h3>Une base de donnée distincte est affectée à chaque étudiant du cours selon le fichier excel joint. Chacun doit :</h3>
<ul>
<li>Créer un script python qui automatise toute la procédure de modélisation de la base de données :
<ul>
<li>Téléchargement du fichier de données à la main.</li>
<li>Data-visualisation des données (via matplotlib, seaborn ou bokeh …)</li>
<li>Data-préparation (pandas)</li>
<li>Modélisation (scikit learn)</li>
<li>Optimisation des hyperparamètres (grid search)</li>
<li>Visualisation des performance (courbe roc …)</li>
</ul>
</li>
</ul>
<h3>Le résultat attendu est en plusieurs points :</h3>
<ul>
<li>Un repository github pour la partie modélisation
<ul>
<li>Doit avoir :</li>
<li>Du code propre, commenté et fonctionnel</li>
<li>Un fichier readme expliquant le contexte, et les objectifs</li>
</ul>
</li>
<li>Un ppt :
<ul>
<li>Présenter l’analyse descriptive des données dans un powerpoint qui explique le contexte de la base de donnée, la cible à prédire, les différentes features disponibles, les étapes de récupération de données, de features engeneering, les tests des différentes hyper paramètres, et les gains de performance des différents modèles.</li>
<li>Le nom du ou des élèves</li>
<li>Ce fichier ppt doit être dans le github</li>
</ul>
</li>
</ul>
<hr>

<hr>


<h2> Contexte :</h2> 
<li> L'ensemble de données sur la biodégradation QSAR a été créé par le groupe de recherche Milano Chemometrics and QSAR (Université de Milan, Bicocca, Milan, Italie). La recherche qui a abouti à ces résultats a été financée par le septième programme-cadre de la Communauté européenne [FP7 / 2007-2013] au titre de la convention de subvention n. 238701 du projet Marie Curie ITN Environmental Chemoinformatics (ECO). </li> <br>

<h2> Objectif :</h2> 
<li> Les données ont été utilisées pour développer des modèles QSAR (Quantitative Structure Activity Relationships) pour l’étude des relations entre la structure chimique et la biodégradation des molécules. Les valeurs expérimentales de biodégradation de 1 055 produits chimiques ont été recueillies à partir de la page Web de l'Institut national de technologie et d'évaluation du Japon (NITE). Des modèles de classification ont été développés afin de distinguer les molécules biodégradables prêtes (356) et non prêtes (699) </li>

<h2> Description : </h2>

<li>41 descripteurs moléculaires et 1 classe expérimentale :  rb / nrb</li> 


<table>
    <tbody>
        <tr>
            <td>Caractéristique</td>
            <td align="center">Multivariate</td>
        </tr>
        <tr>
            <td>Attribut</td>
            <td align="center">Entier, réelle</td>
        </tr>
        <tr>
            <td>Tache</td>
            <td align="center">Classification</td>
        </tr>
        <tr>
            <td>Total</td>
            <td align="center">1055</td>
        </tr>
        <tr>
            <td>Nb attributs </td>
            <td align="center">41</td>
        </tr>

       
    </tbody>
</table>


