<!---

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/glassoue/glassoue.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/glassoue/glassoue.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

-->

## Introduction 
Dans le cadre du cours MOS 4.4 Nouvelles Technologies de l'Information et de la Communication à l’Ecole Centrale de Lyon, j’ai fait une veille technologique sur la thématique Le Machine Learning dans le monde du retail. 

On commence par la définition de quelques termes importants:
- Intelligence artificielle  
c’est une science qui vise à développer des machines qui peuvent  raisonner comme les êtres humains et agir comme eux intuitivement
- Machine Learning   
Une sous-catégorie de l’intelligence artificielle. On parle des algorithmes ayant la capacité d'apprendre et d’améliorer leurs performances sans être explicitement programmés   
- Big Data   
Ce sont des données variées, arrivant dans des volumes de plus en plus importants et avec une vitesse plus élevée. Cette définition est également connue sous le nom des trois « V »
- Retail  
La vente des biens ou de services par une entreprise à un consommateur pour son propre usage. C’est le dernier maillon de la chaîne de distribution. 
Le modèle B2C est probablement le modèle commercial le plus largement compris par le grand public. Le modèle B2C vend des produits finis et des services directement aux consommateurs, tandis que les modèles B2B vendent des produits à d'autres entreprises.

**Pourquoi on parle de machine learninig et retail maintenant ?**  
Plusieurs de modèle de machine learninig et cas d’usage viennent de l’intuition humaine. 
En apercevant des merchants et on parlant à eux, on se rend compte que de ces intuitions existant avant la machine learninig. 
Plus précisément, un merchant de ma famille avait un cahier dans lequel il écrit des notes par rapport à ses clients: une sorte de catégorisation selon la capacité d’achat, préférences etc. 
Il y a aussi un grand travail sur l’assortiment, proposition des produits similaires etc.

Le machine learninig vient automatiser tout cela sur des volumes gigantesques de données (nombre de produits par exemple). 
Amazon propose 12 millions articles. En comptant aussi les vendeurs sur Amazon, ce nombre atteint l’ordre de 350 millions. 

Ces notions sont dus à l’évolution de la raison humaine et de la technologie. Avant, le retail était caractérisé par des entités physiques statiques (magasins, épiceries etc ). Le flux est d’un seul coté: les clients vont aux magasins. 
Maintenant, le retail s’est enrichie. En plus des méthodes traditionnelles, on parle des entités physiques et digitales. Le commerce est fait in-store et out-store. La quantité des données est très importante: on parle de la digitalisation, des ERPs (enterprise resource planning) dans les entreprises. 

## Cas d’usage du Machine Learning en retail

McKinsey parle du “e-commerce boom”. Avec les vagues de covid, l’e-comemrce a fait un progrès équivalent de 10 ans en seulement 3 mois. 
![mckinsey-covid-boom-ecommerce](/images/mckinsey-covid-boom-ecommerce.png)

On présente quelques cas d’usage connus: 

### 1. Utilisation des réseaux sociaux
On parle d’une **stratégie omni-canal**: un des aspects les plus importants est que les données sont récupérées de partout sur internet. Ne soyez donc pas surpris lorsque vous recherchez un produit sur Google, puis que vous entrez dans votre compte Amazon et que vous trouvez le produit.  
Ces différents canaux parlent entre eux. ( exemple: partager des storys sur Instagram à partir de Whatsapp, Facebook etc.)Linguistiquement, "omni", il fait référence à "tout". Il s'agit donc de tout point de contact ou "touchpoint" entre l'entreprise et le client (magasin, site Internet, réseau social, mail, centre d'appels, IoT etc.)

Le machine learninig ne cesse d’évoluer rapidement. Cependant, certains cas d'utilisation doivent toujours être vérifiés par les managers, comme l'optimisation des prix dans certains cas. C’est la notion de **data driven décisions**. 

L’industrie de retail prend les données des différentes plateformes (par exemple utilisation des APIs des sites web) . Les réseaux sociaux fournissent beaucoup de données sur les clients.   
Les données sont toujours en croissance, et donc variables aussi.    
Les médias sociaux se composent principalement de données non structurées, c'est-à-dire d'une énorme quantité de textes, d'images et de vidéos. Des techniques comme le traitement du langage naturel (NLP) sont utilisées pour extraire des informations des médias sociaux. Ces informations sont ensuite utilisées pour identifier les tendances et prédire ce que les clients aimeront acheter.  

**Exemple**  
De nombreuses industries utilisent Facebook pour leurs stratégies de marketing. 

### 2. Optimisation du prix, prix dynamique, promotions
Le client tient compte du prix et de la qualité (et d'autres facteurs) quand il achète un produit.  
Pour le **détaillant**, le prix dépend   
- du coût de fabrication
- du comportement et de l'approche du client lorsqu'il achète ou non un produit. 
Pour comprendre cela, il existe des outils de science des données tels que:  
- la segmentation de la clientèle
- la tarification des concurrents 
- l'attitude d'achat d'un client
- la flexibilité des prix

**Données**
Les données obtenues à partir des sources multicanaux sont analysées pour appliquer les méthodes ci-dessus: historique des transactions du client, description des produits, avis des clients, localisation géographique, élasticité des prix etc.

**Résultats**
- Meilleur prix pour un article 
- Prix pour les promotions 
- Avantage du modèle d'optimisation en temps réel: lorsqu'il s'agit d'un nouveau produit, le modèle peut déjà proposer des prix basés sur des similitudes avec d'autres produits

Les algorithmes apprennent continuellement à partir de nouvelles informations et détectent les nouvelles demandes et tendances. Les entreprises de commerce électronique pourraient bénéficier de modèles prédictifs qui leur permettraient de déterminer le meilleur prix pour chaque produit particulier.

**Exemple**
**Amazon** est un leader dans ce domaine( Dynamic pricing), les prix changement tous les 10 minutes, ce qui est 50 fois plus que Walmart.   
Cela a boosté les revenus par 25%. 
![price-optimization-opportunities](/images/price-optimization-opportunities.png)

### 3. Marketing personnalisé
Il s’agit d’un marketing différent pour chaque utilisateur ou catégorie d’utilisateurs selon la segmentation de la clientèle.  

**Données**   
historique de navigation des utilisateurs, achats passés, goûts et dégoûts, 
Grâce à la segmentation de la clientèle, les entreprises peuvent cibler un type de clients riches par exemple.  

**Techniques**   
régression, clustering etc.

**Exemple**    
**Vedic hair care**, **Amazon**,  a mis en place un plan marketing pour attirer le public en lui proposant des produits personnalisés. Ils suggèrent des produits en fonction des préoccupations et des préférences de leurs clients.

### 4. Détection de fraude 
Gagner la confiance du client est le facteur le plus important qui affecte la croissance des industries. Il est nécessaire de lutter contre les fraudes.  

En raison de la croissance des transactions en ligne, des achats, des opérations bancaires, des déclarations de sinistres, etc. la fraude est devenue un problème majeur pour ces entreprises et elles investissent beaucoup de ressources pour reconnaître et prévenir les fraudes.   
Les fraudes peuvent également prendre la forme de faux avis.   

**Techniques**   
- Algorithmes de ML supervisés : régression logistique, réseau neuronal, analyse de séries chronologiques.
- Algorithmes ML non supervisés : Analyse en groupes, réseau bayésien
- Techniques statistiques : moyenne, quantiles, distribution de probabilité, règles d'association.
- Réseaux de neurones profonds , permettent de prendre l’aspect temporel en considération. 

### 5. Réalité augmenté 
Une phrase qu’on entend toujours, et qu’un client aime bien l’entendre avant d’acheter c’est  "Essayez avant d'acheter".   
De nombreuses entreprises de vente au détail ont utilisé ce mot pour leur marketing. La réalité augmentée offre au client une expérience en temps réel du produit. 

D’après Eastern Peak, en 2021, ils s'attendent à ce que les technologies immersives fassent partie de leurs expériences d'achat.   
69 % des clients s'attendent aujourd'hui à utiliser la réalité augmentée lorsqu'ils font leurs achats, et les détaillants font de leur mieux pour s'adapter et mettre en œuvre cette technologie immersive. Avant la pandémie, le marché de la réalité augmentée dans le commerce de détail avait atteint 10 milliards de dollars et devrait connaître un taux de croissance annuel composé de 46,6 % jusqu'en 2027.  

La différence entre la réalité augmentée et la réalité virtuelle est que la RA ne remplace pas le monde réel mais l'augmente avec des objets virtuels supplémentaires.

**Exemples**  
- **Magicplan** offrent aux clients un planificateur de conception de propriétés résidentielles basé sur la réalité augmentée, qui leur permet de voir à quoi ressemblera leur maison une fois toutes les rénovations terminées. Les acheteurs peuvent même faire une promenade virtuelle dans leur nouvelle résidence et estimer les matériaux dont ils auront besoin pour le projet de rénovation.  
- **Lowes** l'application AR de Lowes aide les clients à naviguer rapidement dans les magasins de la marque, à choisir de meilleurs itinéraires et à trouver rapidement ce dont ils ont besoin.  
- Harmonisation des couleurs dans une pièce   
- **Sephora** a developpé une application mobile dispose d'une fonction Visual Artist, qui permet aux utilisateurs d'essayer les produits de la marque en combinant la technologie de reconnaissance faciale et la RA. Si les utilisateurs aiment leur nouveau look, ils peuvent commander les produits via l'interface de l'application.  

![AR](/images/AR.png)

### 6. Localisation d’un nouveau magasin
L’objectif c’est de recommander le meilleur quartier pour l'ouverture du nouveau magasin.   

**Données**  
données clients disponibles en ligne, tendances du marché dans cette zone, emplacement des autres magasins à proximité, etc.
analyse géospatiale, techniques ML

**Quelques intuitions**    
Le nouveau magasin:   
- est loin des concurrents
- est proche des Apple stores
- doit se trouver dans des zones où les revenus des résidents sont élevés
- doit se trouver dans des zones où la croissance économique est en hausse
- est idéalement près des principales stations de transport en commun

**Exemple**   
**Wendy's**, une chaîne de hamburgers populaires aux États-Unis, qui a tiré parti de l'analyse de l'emplacement pour identifier de nouveaux emplacements de magasins et économiser près de 750 000 $.   

### 7. Analyse du sentiment des clients
L’objectif c’est de permettre aux détaillants de fournir de meilleurs services à la clientèle dans l’avenir.   

Traditionnellement, les détaillants utilisaient des groupes de discussion et des sondages pour analyser l'expérience des clients avec le produit. Ce processus prenait beaucoup de temps et était également un peu coûteux.  
Aujourd'hui, les données proviennent des réseaux de médias sociaux et des services en ligne : retour d'information, critiques, évaluations. Ces sources sont facilement disponibles, rapides et gratuites.  
Les détaillants effectuent des analyses sur la base du traitement du langage naturel et de l'analyse de texte afin d'extraire les sentiments positifs, neutres ou négatifs.  

**Techniques**   
Natural Language Processing

### 8. Systèmes de recommandation 
Un système de recommandation c’est un système qui:   
- filtre les informations des clients 
- prédit les préférences des utilisateurs lorsqu'ils naviguent sur Internet (différents sitess web, site web du détaillant), et donc leurs comportements d’achat
- identifie les tendances, augmente leurs ventes et donc leurs revenus.

Les moteurs de recommandation s'auto gèrent et s'ajustent en fonction des choix effectués par les clients. Il existe essentiellement trois grandes techniques de recommandation:  

- Filtrage collaboratif (utilise la similitude entre les utilisateurs)
Ce type de système fait une prédiction de ce que vous pourriez aimer en se basant sur les préférences de nombreux autres utilisateurs. Il part du principe que si A aime Gionee et B aime Gionee et Vivo, alors A pourrait aussi aimer Vivo.

- Filtrage basé sur le contenu
Ce type de système se concentre sur les produits eux-mêmes, et non sur les autres utilisateurs, et recommande des produits qui ont des attributs ou des caractéristiques similaires.   

**Exemple**  
**Netflix**: proposer des films de contenu similaire à ceux déja regardés par un utilisateur.   
**Amazon**, **Dell**: au moment d’achat d’un ordinateur portable suggérer un sac à un bon prix. 

- Système de recommandation hybride  
Il s'agit d'un système où les deux techniques ci-dessus sont utilisés et leurs résultats sont combinés.

### 10. Prédiction 

#### Prédiction de la valeur à vie du client - Customer lifetime value CLV
La valeur à vie du client (VVC) est le bénéfice total qu'un client peut apporter à l'entreprise pendant toute la durée de la relation client-entreprise.
**Données**  
Les achats précédents du client, les écarts entre les achats et le nombre de commandes répétées.

#### Prédiction du taux de désabonnement - Churn prediction 
La prédiction du taux de désabonnement permet de découvrir les clients qui risquent de partir.   
La solution d'apprentissage automatique mise en œuvre dans le commerce électronique permet de réagir rapidement aux clients qui cesseront probablement d'acheter chez vous.   
Un tel système augmentera le taux de rétention et vous apportera un flux stable de revenus.   

#### Prévision de la demande 
**Exemple**
- **Pantene, Walgreens, and The Weather Channel - 2013 **  
Pouvez-vous imaginer qu'une prévision météorologique a aidé une chaîne de magasins à augmenter ses ventes ? Vous êtes curieux ? Voici l'histoire étonnante.

La prévision météorologique ne concerne pas seulement la météo. Elle a bien plus à offrir. Une chaîne météo prédit l'impact de la météo sur les émotions de ses clients des plateformes des détaillants.  

- **Target**   
L'équipe d'analystes de l'entreprise s'est réunie et a trouvé un moyen de savoir si une cliente pouvait être enceinte, avant même qu'une annonce ne soit faite. 
En analysant les tendances d'achat de ses clientes, il s'est avéré qu'il était possible non seulement d’attribuer un niveau de probabilité que la cliente soit enceinte, mais aussi prédire la date probable de l'accouchement.
Grâce à ces informations, la société de vente au détail a commencé à mélanger les offres envoyées à ces clientes afin d'inclure des articles pour le fœtus avec les coupons habituels.


### 12. Engine de recherche
Les utilisateurs utilisent les moteurs de recherche pour trouver rapidement ce dont ils ont besoin. 
Ils ont de moins en moins de temps et de patience pour formuler des requêtes, attendre les résultats et les analyser. C'est pourquoi il est nécessaire de personnaliser les résultats des requêtes de recherche.  

Un moteur de recherche personnalisé pourrait jouer un rôle de plus en plus important. Il est basé sur des modèles de Machine Learning avec les préférences à court et à long terme de l'utilisateur, son historique ou ses requêtes précédentes. 
La recherche peut être visuelle ou vocale.  

**Exemples**
**Ebay**  a créé une technologie appelée eBay Machine Translation (eMT). Ce système traduit les noms de produits avec une précision de 90 %. Grâce à cette solution d'apprentissage automatique, les ventes totales de l'entreprise ont augmenté de 10,9 % en 2014.     

En examinant les données extraites d'eBay, les chercheurs du MIT ont comparé les ventes entre les États-Unis et les pays hispanophones d'Amérique latine avant et après que la plateforme d'achat ait introduit la traduction assistée par l'IA pour les listes de produits en 2014.
L'étude a trouvé des résultats similaires dans les langues russe, italienne et française (ce qui prouve l'efficacité de l'eMT). 

"La traduction automatique chez eBay est essentielle pour promouvoir le commerce transfrontalier. Notre technologie aide à surmonter les barrières linguistiques et permet aux acheteurs de commander des articles depuis des pays étrangers" - Evgeny Matusov, directeur principal de la science de la traduction automatique chez eBay. 

- **American Eagle**, une célèbre marque de vêtements, s'associe à **Slyce**, une startup prometteuse spécialisée dans la reconnaissance d'images. Grâce à son application mobile, Slyce fournit un moteur de recherche visuel qui permet aux clients de rechercher des vêtements spécifiques à partir de photos prises par l'appareil photo de leur appareil portable.


<!---
-----------------------------------------------------------------------------------------------------------------------
-->
## Exemples des outils chez Amazon        
Amazon compte 12 millions produits propores d’Amazon et 350 millions produits tenant en compte les autres vendeurs sur la plateforme.  

### 1. Systèmes de recommandation 
Il y a deux types de recommandation:   
- on-site recommandation lors de la navigation sur le site web
- off-site à travers des recommandations par email     
D’après Mckinsey 35 % de ce que les consommateurs achètent sur Amazon proviennent des moteurs de recommandation. 


### 2. Analyse du parcours du client - Customer Journey Analytics

Amazon collecte les données de différentes sources, par exemple : vous postez sur Instagram que vous allez prendre un vol dans un autre pays, Amazon vous suggérera des produits liés à ce lieu.   
L’entreprise est un leader dans l’expédition anticipée:   
- Les produits sont expédiés avant même que les clients ne les commandent. Le comportement passé et les achats prédits sont utilisés pour planifier la diminution de l'expédition le jour suivant à l'heure suivante.  
- Une fois que ces produits sont sortis de l'entrepôt et se trouvent dans une zone donnée, ils peuvent être commercialisés à d'autres
à un tarif réduit.  
L'utilisation de modèles ML basés sur les données du client pour prédire son futur achat, ou sur un groupe de personnes en France pour comprendre les produits les plus attendus en France par exemple.  

![big-data-in-customer-journey-analytics](/images/big-data-in-customer-journey-analytics.jpg)

### 3. Alexa
Cet outil est utilisé dans de nombreux domaines comme   
- Ecouter la musique sur Amazon music, 
- Acheter des articles sur Amazon   
L'utilisateur peut activer Alexa et commencer à énumérer les articles qu'il souhaite rechercher, acheter ou ajouter à sa liste d'achats par sa voix. Il peut ensuite accéder à une version texte de cette liste dans son application Alexa et apporter des modifications ultérieurement.    
La société affirme également que Alexa aide les utilisateurs en leur suggérant les types de produits qu'ils achètent fréquemment ou en leur recommandant des produits labellisés Amazon's Choice" s'ils recherchent un article qu'ils n'ont jamais acheté auparavant.
Depuis sa sortie initiale en 2014, plus de 100 millions de produits compatibles avec Alexa ont été vendus dans le monde, selon le vice-président principal des appareils et services d'Amazon, David Limp, dans une interview de 2018.   

**Inconvénients**     
33 % des adultes américains citent les inquiétudes liées au fait que les enceintes intelligentes enregistrent ce qu'ils disent comme principale raison de ne pas acheter ces appareils, un chiffre qui a plus que doublé depuis 2018.

![alexa_stats.jpg](/images/alexa_stats.jpg)

![alexa](/images/alexa.png)

### 4. Emballage
Comment Amazon utilise le machine learning pour éliminer 915 000 tonnes d'emballages (en 2015) ?  
En 2020, les outils de ML ont changé le mix d'emballage de manière significative, réduisant l'utilisation de boîtes de 69% à 42% ⇒ moins de camions ⇒ moins d'émissions de carbone.  

Amazon vend des 100s de millions de produits différents et expédie des milliards d'articles par an. Pour expédier avec un emballage minimal à une vitesse maximale et s'assurer que la commande du client arrive à sa porte sans dommage, l'équipe doit innover à grande échelle.   

"C'est un défi que le machine learning est uniquement en mesure de résoudre", explique Matthew Bales, responsable des sciences de la recherche chez Amazon. "Au lieu de demander à quelqu'un d'inspecter ces produits individuellement pour vérifier leur fragilité ou leur volume, nous utilisons le machine learning."   

L'objectif était de mettre à l'échelle la prise de décision sur les centaines de millions de produits qui sont expédiés - pour ne pas automatiquement opter par défaut pour des boîtes, mais pour identifier les articles qui peuvent être emballés dans une enveloppe en papier rembourrée ou dans un sac en papier à la place. Les pochettes postales (enveloppes en papier rembourrées) sont des choix plus durables. Elles sont 75 % plus légèrs qu'une boîte de taille similaire et s'adaptent à la forme du produit. Elles occupent 40 % moins d'espace qu'une boîte lors de l'expédition, ce qui réduit considérablement le nombre de camions sur les routes.    
![emballage1](/images/AI for Good Foundation - Reducing Amazon’s packing waste using multimodal deep learning (FE2021S2P1) [mfr91fwRNKs - 1280x720 - 2m52s].png)

![emballage2](/images/AI for Good Foundation - Reducing Amazon’s packing waste using multimodal deep learning (FE2021S2P1) [mfr91fwRNKs - 1280x720 - 5m09s].png)

### 5. Amazon Go / Carrefour Flash in Paris with Californian start-up AiFi
Il s’agit d’un magasin dans lequel il n’y a pas de file d'attente, pas de caisse, pas de temps d'attente.    
C’est très simple: utilisez l'application Amazon pour entrer, rangez votre téléphone et commencez à faire vos achats. Tout ce que vous ajoutez est ajouté à la carte virtuelle dans votre compte Amazon.   
Si vous changez d'avis sur un article, remettez-le en place et il sera automatiquement retiré de votre liste.   
Une fois sortie, la facture est ajoutée au compte Amazon.    

Il s’agit d’un magasin dans lequel il n’y a pas de file d'attente, pas de caisse, pas de temps d'attente.    
C’est très simple: utilisez l'application Amazon pour entrer, rangez votre téléphone et commencez à faire vos achats. Tout ce que vous ajoutez est ajouté à la carte virtuelle dans votre compte Amazon.    
Si vous changez d'avis sur un article, remettez-le en place et il sera automatiquement retiré de votre liste.     
Une fois sortie, la facture est ajoutée au compte Amazon.    

**Comment**     
Les techniques utilisées sont le deep learning et vision par ordinateur, capteurs de fusion (sensor fusion) comme dans les voitures à conduite autonome.  
- Toutes les données sur les clients quand ils sont dans les magasins (vision par ordinateur)
- Capteurs de fusion : Agréger les signaux de différents capteurs (ou caméras, car cette question a été résolue en utilisant uniquement la vision par ordinateur).
- Calibrage : Faire en sorte que chaque caméra connaisse son emplacement dans le magasin de manière très précise.
- Détection de personnes : Identifier et suivre en permanence chaque personne dans le magasin.
- Reconnaissance d'objets : distinguer les différents articles vendus.
- Estimation de la pose : détecter ce que chaque personne près d'un rayon fait exactement avec ses bras
- Analyse de l'activité : Déterminer si une personne a pris ou a retourné un article.

![amazon_go.png](/images/amazon_go.png)

<!---
-----------------------------------------------------------------------------------------------------------------------
-->
## Le futur du retail 
McKinsey parle d’une expérience d’achat “phy-gitale”. Le monde de retail présente un aspet physique et un aspet digitale.   
On parle aussi de l’idée des magasins digitales, connectés, automatiques et personnalisés pour chaque client à partir des suggestions des achats. Les techniques présentés au dessus sont utilisés.   

Et plus encore : 
- Metaverse : "au-delà" de l’univers (beyond universe)  
- Des expériences AR et VR uniques 
- Digitalisation des produits: symbole de statuts sociaux, les actifs, la maison, les vêtements, les bijoux etc ont une valeur. Cette valeur va augmenter quand le monde va utiliser plus le Metaverse.
- Les grandes marques vendent des produits virtuelles ; Adidas, Vans
- Paiement par crypto monnaie ou par méthodes traditionnelles. 
- Lien avec les NFTs qui sont des articles numériques à vendre. 

<!---
-----------------------------------------------------------------------------------------------------------------------
-->
## Réflections sur les avantages et inconvénients

### Avantages 
- Plus de revenus pour les entreprises utilisant ces technologies 
- Disruption: créations des emplois
Exemples   
**DataHawk** est une entreprise française qui travaille sur les plateformes Amazon et Walmart. L’entreprise aide ses clients à mieux vendre sur ces plateformes à travers des KPIs produits des algorithmes de ML. 
**Google** fait payer les mots de recherche. Un exemple de travail des data scientists dans une autre boite, c’est de prédire le meilleur moment pour acheter ces mots afin de figurer dans les premières pages de recherche. 
- Rapidité de service

### Inconvénients
- Difficulté de ne pas accepter de partager les données. Ça prend beaucoup plus de temps de rejeter les cookies que de les accepter. 
- Prix dynamique: possibilité d’avoir différents prix pour différentes gens 
- Réduction des revenus des petits magasins et épiceries
- Faux avis sur internet. Exemple: **Trustpilot**
- Ces algorithmes reposent sur les données des utilisateurs. Les utilisateurs ne gagnent pas en donnant leurs données, mais les entreprises maximisent leurs revenus.   
J’avais toujours l’idée qu’il faut avoir une sorte de récompense pour le partage des données des utilisateurs.   
J’étais épanoui par l’idée d’un participant dans une émission de télévision en Royaume-Uni Dragon's den. Il a adressé exactement ce point et les jurys ont acceuilli chaleureusement son idée.   

<!---
-----------------------------------------------------------------------------------------------------------------------
-->
## Conclusion
La technique est un outil important pour prospérer et faire progresser les secteurs d’industrie. Plus précisément, la machine learninig joue un rôle crucial dans l’évolution du monde de retail. Ce rôle se caractérise par des transitions :    
- depuis des méthodes de vente traditionnelles et statiques aux méthodes évolutives 
- depuis des produits physiques aux produits digitals et physiques. 


<!---
-----------------------------------------------------------------------------------------------------------------------
-->
## Acronymes
- ML : machine learning 
- IoT: internet of things 
- B2B : business to business
- B2C: business to consumer 
- RA: réalité augmenté
- NLP: naturale language processing 
