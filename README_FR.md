<a name="top" id="top"></a><center># 1pp (One Pixel Productions)</center>

<center><strong>Un mod de Spellhold Studios pour les jeux Infinity Engine</strong></center>

<strong>Auteure :</strong> Erephine<br />
<strong>Version :</strong> 4.2.0<br />
<strong>Langues :</strong> <a href="README.md">anglais</a>, fran�ais<br />
<strong>Plateformes :</strong> Windows, linux


<a href="#intro">Pr�sentation</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Liste des composants</a> &#x2B25; <a href="#101">D�tail des composants</a> &#x2B25; <a href="#credits">Remerciements</a> &#x2B25; <a href="#version">Historique des versions</a></center></br></br>


<hr>


## <a name="intro" id="intro"></a>Pr�sentation

Sans aucun doute le mod le plus complet en mati�re d'ajustements graphiques, 1pp est le fruit d'un long et ambitieux travail passionn� men� pendant pr�s de 8 ans, avec pour objectif d'offrir une exp�rience de jeu raffin�e et plus agr�able � tous ceux qui consid�rent que les �l�ments graphiques de Baldur's Gate II laissaient � d�sirer par rapport � ceux de son pr�d�cesseur.</br></br>
Mis � jour et simplifi� sous la forme d'un programme d'installation unique, 1ppv4 compile en un seul package les divers composants d'am�lioration graphique qui se sont accumul�s au fil des ans.</br>

Ce mod transforme certaines ic�nes d'inventaire d'objets de Baldur's Gate II au style de Baldur's Gate, et remplace certains �l�ments du jeu par un contenu qui corresponde � la qualit� � laquelle nous �tions habitu�s. D'un point de vue technique, One Pixel Productions s'efforce donc de corriger les � d�fauts cosm�tiques � qui n'auraient jamais d� survivre au passage du contr�le qualit�. Il comporte de nombreux composants d�taill�s plus <a href="#components">bas</a>.

Consultez le <a href="http://www.spellholdstudios.net/ie/1pp">site internet du mod</a> ou son <a href="http://www.shsforums.net/index.php?showforum=159">forum</a> pour d�couvrir toutes les derni�res mises � jour.</br>
<div style="text-align:right"><a href="#components">Retour en haut de page</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibilit�

Ce mod est con�u pour fonctionner sur les jeux Infinity Engine suivants : Baldur's Gate II (Les Ombres d'Amn : BG2-SoA), avec ou sans son extension Tr�ne de Bhaal (Throne of Bhaal : ToB), les mods de conversion Baldur's Gate Trilogy (BGT), Baldur's Gate Tutu (Tutu), Icewind Dale (IWD) avec ou sans ses extensions Heart of Winter (HoW) et (TotLM), and Icewind Dale II (IWD2).

1pp est un mod WeiDU, et devrait par cons�quent �tre compatible avec n'importe quel mod WeiDU. Je ne peux cependant pas tous les tester. Si vous faites face � des bugs, veuillez les signaler dans le forum, s'il vous pla�t.

Je recommande fortement aux joueurs de BG2 et de ToB d'installer la derni�re version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.</br></br>
Si vous jouez avec BG2-ToB ou BGT, je vous recommande fortement d'installer la derni�re version du <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> avant d'installer ce mod.</br>
<div style="text-align:right"><a href="#components">Retour en haut de page</a></div>


<hr>


## <a name="compat" id="compat"></a>Installation

#### Mise en garde

<em>Si une ancienne version de ce mod est d�j� install�e, il est n�cessaire de la d�sinstaller d'abord. Pour cela, lancez <strong>setup-1pp.exe</strong>, et d�sinstallez tous les composants pr�c�demment install�s. Une fois la d�sinstallation achev�e, supprimez le r�pertoire <strong>1pp</strong> et le fichier <strong>setup-1pp.exe</strong> (version Windows) avant d'extraire la nouvelle version du mod.</em>

<em>Lorsque vous installez ou d�sinstallez, <strong>ne fermez pas la fen�tre <acronym title="Disk Operating System">DOS</acronym></strong> en cliquant sur le bouton <strong>X</strong> ! Au lieu de cela, appuyez sur la touche <strong>Entr�e</strong> lorsque l'invite de commandes vous le demande.</em>

<em>Par pr�caution, <strong>D�sactivez les antivirus</strong> ou tout logiciel r�sidant en m�moire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une f�cheuse tendance � d�clarer les ex�cutables des mods comme des faux positifs, provoquant ainsi l'�chec de la proc�dure d'installation.</em>

## 

#### Windows

1pp pour Windows est livr� et install� avec WeiDU, et est diffus� sous forme d'archive.

Vous devez extraire les fichiers de l'archive dans votre r�pertoire de jeu (<em>le dossier qui contient le fichier CHITIN.KEY</em>) � l'aide de <a href="http://www.7-zip.org/download.html">7zip</a> ou de <a href="http://www.rarlab.com/download.htm">WinRAR</a>. Une fois l'archive extraite correctement, vous devriez trouver le r�pertoire <strong>1pp</strong> et le fichier <strong>setup-1pp.exe</strong>. Pour installer le mod, il suffit de double-cliquer sur <strong>setup-1pp.exe</strong> et de suivre les instructions affich�es � l'�cran.

Vous pouvez lancer <strong>setup-1pp.exe</strong> dans votre r�pertoire de jeu pour r�installer, d�sinstaller, ou encore changer des composants.

## 

#### Note pour effectuer une d�sinstallation compl�te

En plus des m�thodes d�taill�es plus haut pour supprimer des composants, il est possible de d�sinstaller compl�tement le mod en tapant <strong>setup-1pp --uninstall</strong> dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.

## 

#### :warning: Avertissement : nouvelle proc�dure d'installation

##### Depuis la version 4.2.0, les variables n�cessaires � l'installation sont lues dans le fichier 1pp-config-default.ini, ou dans le fichier 1pp-config.ini, si ce dernier existe.

Avec les versions pr�d�centes, pendant la proc�dure d'installation, de nombreux messages vous permettaient de personnaliser les composants � votre convenance (en fonction de votre jeu IE et des composants que vous aviez install�s). Tous ces choix de variables d�termin�s pendant l'installation du mod ont �t� externalis�s dans le fichier **_1pp-config-default.ini_** situ� dans le r�pertoire 1pp. Ce fichier �tablit une installation � _standard_ �.

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier les variables souhait�es dans le fichier 1pp-config-default.ini, puis de sauvegarder ce dernier sous le nom **_1pp-config.ini_**.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorit� aux v�tres. Si le fichier 1pp-config.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par d�faut (celle correspondant � l'installation � _standard_ �).</br>

<div style="text-align:right"><a href="#components">Retour en haut de page</a></div>


<hr>


## <a name="components" id="components"></a>Composants

Le programme d'installation comprend les composants suivants. Chacun poss�de un num�ro distinct et pr�-d�fini qui lui attribue une position d�termin�e (mot-cl� <em>DESIGNATED</em> en langage WeiDU) ; ce qui permet aux autres composants de le d�tecter et aux utilitaires d'installation automatiques comme le BiG World Setup de pr�ciser quels composants installer.

&#8258; <strong>Contenu concernant le moteur du jeu et les fichiers de base</strong></br>
><span style="margin-left: 50px;"><a href="#101">[101] 1ppv4 : Paperdolls (composant principal)</a></span></br>
><span style="margin-left: 50px;"><a href="#102">[102-103] 1ppv4 : Couleurs de palette �tendues</a></span></br>
><span style="margin-left: 50px;"><a href="#104">[104] 1ppv4 : Modification de l'interface pour BGII</a></span></br>
><span style="margin-left: 50px;"><a href="#105">[105] 1ppv4 : Corrections d'avatars</a></span></br>
><span style="margin-left: 50px;"><a href="#106">[106-109] 1ppv4: Femmes naines</a></span></br>
><span style="margin-left: 50px;"><a href="#110">[110-112] 1ppv4 : Des voleurs en pagaille</a></span></br>
><span style="margin-left: 50px;"><a href="#113">[113] 1ppv4 : Avatar intelligent & Changement d'armure</a></span></br>
><span style="margin-left: 50px;"><a href="#114">[114] 1ppv4 1ppv4 : Rendu des sorts nuanc�</a></span></br>

&#8258; <strong>Modifications d'objets, ajouts et impl�mentation</strong></br>

><span style="margin-left: 50px;"><a href="#200">[200] 1ppv4 : Corrections de base</a></br>
><span style="margin-left: 50px;"><a href="#201">[201] 1ppv4 : Ic�nes de sorts et de parchemins uniformes</a></span></br>
><span style="margin-left: 50px;"><a href="#202">[202] 1ppv4 : Ajustements de sorts</a></span></br>
><span style="margin-left: 50px;"><a href="#203">[203] 1ppv4 : R�tablissement des animations d'�p�es enflamm�es</a></span></br>
><span style="margin-left: 50px;"><a href="#204">[204] 1ppv4 : Coloration des b�tons</a></span></br>
><span style="margin-left: 50px;"><a href="#205">[205] 1ppv4 : Boucliers de BG1 v2</a></span></br>
><span style="margin-left: 50px;"><a href="#206">[206] 1ppv4 : Animations suppl�mentaires de bouclier (fichiers de base)</a></span></br>
><span style="margin-left: 50px;"><a href="#207">[207] 1ppv4 : B�tons de magiciens (fichiers de base)</a></span></br>
><span style="margin-left: 50px;"><a href="#208">[208] 1ppv4 : Animations suppl�mentaires de casques (fichiers de base)</a></span></br>
><span style="margin-left: 50px;"><a href="#209">[209] 1ppv4 : Ailes amovibles (fichiers de base)</a></span></br>
><span style="margin-left: 50px;"><a href="#210">[210] 1ppv4 : Plus de diversit� de paperdolls d'objets (fichiers de base)</a></span></br>

><span style="margin-left: 50px;"><a href="#400">[400] 1ppv4 : Mise � jour et modification des objets</a> <em>[composant de mise � jour principal de 1ppv4]</em></br>
><span style="margin-left: 50px;"><a href="#401">[401] 1ppv4 : Rendu des projectiles am�lior�</a></span></br>

&#8258; <strong>Correctifs suppl�mentaires ne concernant pas les personnages</strong></br>

><span style="margin-left: 50px;"><a href="#300">[300] 1ppv4 : Correction des animations des solaires et des �l�mentaires</a></span></br>
><span style="margin-left: 50px;"><a href="#301">[301] 1ppv4 : Correction d'autres �l�ments divers</a></span>

------------------------

### <a name="101" id="101"></a>[101] 1ppv4 : Paperdolls (composant principal)

Disponible pour : <span style="color:#006600">SoA</span>, <span style="color:#770000">ToB</span>, <span style="color:#008800">Tutu</span>, <span style="color:#009FB9">HoW</span>, <span style="color:#666666;">IWDII (placeholder)</span></br>

<img src="1pp/documentation/files/101.jpg"></br>

C'est le composant qui est � l'origine de ce projet. Il convertit les paperdolls [<em>NdT : silhouettes dans l'�cran des personnages</em>] de Baldur's Gate I pour le moteur de Baldur's Gate II (utilis� dans SoA/ToB et HoW). Il comprend aussi des paperdolls redessin�s pour toutes les combinaisons de races et de classes correspondant aux animations du jeu, ainsi que pour les objets port�s par les personnages. Cette nouvelle version d�tecte l'installation du mod Infinity Animations et le prend en compte dans ses modifications, notamment pour les jeux HoW utilisant les animations de BG1 install�es par le pack correctif d'animations 1pp pour IWD.

###### <em>N'oubliez pas que ce composant ne modifie ni les ic�nes, ni les couleurs des objets ; il n'est donc pas recommand� de l'installer seul. Cependant, il constitue un pr�-requis pour presque tous les composants suivants.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="102" id="102"></a>[102-103] 1ppv4 : Couleurs de palette �tendues

<strong>Composant obligatoire</strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/102.jpg">

Ce composant ajoute de nouvelles nuances de couleurs aux jeux Infinity Engine, en faisant passer le nombre de couleurs disponibles de 116 � 256. Il implante aussi une nouvelle table de couleurs al�atoires utilisables par Baldur's Gate II et de nouveaux fichiers de jeux de couleurs pour Icewind Dale II, offrant un choix plus important de couleurs pour d�finir la peau et les cheveux des diff�rentes races.</br>
Il corrige aussi quelques probl�mes mineurs li�s aux nuances standard.</br>
<a href="1pp/documentation//files/extpal_readme-french.html">Pour en savoir plus �</a></br></br>

<strong>Installation minimum pour assurer la compatibilit� du mod [102]</strong></br>
Pour les syst�mes d'exploitation qui n'acceptent pas le correctif binaire (OSX), ce composant installe les fichiers basiques dont 1pp � besoin pour fonctionner correctement, mais ne permet pas d'utiliser les nouvelles couleurs pour personnaliser les personnages.</br></br>

<strong>Installation compl�te [103]</strong></br>
L'installation compl�te modifie l'ex�cutable du jeu, permettant un usage complet des nouvelles couleurs de palette.</br>
Avec l'installation compl�te, les choix suppl�mentaires de couleurs pour la peau et les cheveux sont disponibles automatiquement dans les �crans du jeu.</br>
Quant aux couleurs des v�tements, le compl�ment standard de 34 couleurs primaires et secondaires sera disponible dans les �crans de cr�ation et de personnalisation de personnage. Pour b�n�ficier de plus de couleurs de v�tements, il suffit de cliquer sur � Personnaliser � > � Couleurs � dans l'�cran des personnages pour acc�der � un jeu suppl�mentaire de 34 couleurs.</br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="104" id="104"></a>[104] 1ppv4 : Modification de l'interface pour BGII

Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu (si vous utilisez l'interface classique de BG2)</span></br>

<img src="1pp/documentation/files/104.jpg">

Cette interface retravaill�e pour Baldur's Gate II SoA/ToB a pour but d'adoucir les ar�tes trop prononc�es des �crans sans s'�loigner du design d'origine. Parmi les modifications majeures, une horloge remplace la � bo�te � d'origine, les �&#160;parchemins sans bords � de nombreux �crans font place � des parchemins plus r�alistes (voir les captures d'�cran dans le lien plus bas), et une option permet de modifier les polices de caract�res.</br>
<a href="1pp/documentation//gui_readme-french.html">Plus d'images �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="105" id="105"></a>[105] 1ppv4 : Corrections d'avatars

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/105.jpg">

Ce composant corrige et am�liore plusieurs s�ries d'animations d'avatars de personnages de Baldur's Gate II, et met � jour leurs paperdolls pour mieux refl�ter les modifications effectu�es.</br>
<a href="1pp/documentation/files/avafix_readme-french.html">Plus de captures d'�cran �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="106" id="106"></a>[106-109] 1ppv4 : Femmes naines

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/106.jpg">

Ce composant modifie le moteur du jeu de Baldur's Gate II pour qu'il utilise des animations d'avatar diff�renci�es pour les femmes naines et les magiciennes des races de petite taille, et installe le contenu n�cessaire pour qu'elles soient op�rationnelles dans le jeu.</br>
<a href="1pp/documentation/files/dwarf_readme-french.html">Plus de captures d'�cran �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="110" id="110"></a>[110-112] 1ppv4 : Des voleurs en pagaille

<strong>Composants pr�-requis : <a href="#101">[101]</a> <a href="#106">[106-109]</a></strong>
###### Note : La mani�re dont ce composant est cod� provoquera l'�chec de son installation si le mod Infinity Animations est d�j� install�. Pour �viter ce probl�me, installez IA apr�s lui.
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/110.jpg">

Dans BGII, les voleurs ne disposent d'animations que pour un niveau d'armure (les armures de cuir). �quiper un voleur d'un autre type d'armure affiche l'animation par d�faut (sans armure). Dans l'�cran du personnage, seuls les deux premiers niveaux d'armure sont repr�sent�s par un paperdoll, les autres affichent le paperdoll sans armure.</br>
Ce composant modifie l'ex�cutable du jeu pour qu'il utilise l'ensemble des animations des voleurs, et installe le contenu n�cessaire pour qu'elles soient op�rationnelles.</br>
<a href="1pp/documentation/files/thieves_readme-french.html">Consulter le readme d'origine �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="113" id="113"></a>[113] 1ppv4 : Avatar intelligent & Changement d'armure

Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/113.jpg">

Ce composant permet d'afficher correctement les armures et les robes lorsque les personnages de toutes les classes s'en �quipent. Il contourne la limitation du moteur du jeu qui n'affiche pas les robes port�es par les guerriers, pr�tres et voleurs, ni les armures port�es par les magiciens, en changeant l'animation des personnages selon les types d'armure dont ils sont �quip�s.</br>
<a href="1pp/documentation/files/switch_readme-french.html">Consulter le readme d'origine �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="114" id="114"></a>[114] 1ppv4 : Rendu des sorts nuanc�

<strong>N�cessite l'activation de l'acc�l�ration 3D</strong></br>
Disponible pour : <span style="color:#060">SoA (partial)</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII (placeholder)</span></br>

<img src="1pp/documentation/files/114.jpg">

Ce composant am�liore sensiblement certains effets visuels de sorts des jeux IE utilisant le moteur de Baldur's Gate II en les dotant d'un l�ger effet d'alpha blending [<em>NdT : simulation de transparence</em>]. Notez qu'il ne fonctionnera correctement qu'avec l'activation de l'acc�l�ration 3D. Si vous jouez en mode Rendu logiciel, il n'est pas recommand� d'installer ce composant.</br>
<a href="1pp/documentation/files/effects_readme-french.html">Plus de captures d'�cran �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="200" id="200"></a>[200] 1ppv4 : Corrections de base

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/200.jpg">

Pour l'essentiel, ce composant reprend les modifications d'ic�nes d'inventaire des objets de 1ppv2. En d'autres termes, il am�liore la qualit� graphique des ic�nes dans BGII, particuli�rement dans l'expansion ToB. Il met aussi � jour des ic�nes et les objets associ�s ajout�s par certains mods. Il constitue le socle sur lequel 1ppv4 a �t� con�u pour SoA/ToB.</br>
<a href="1pp/documentation/files/v2_readme-french.html">Consulter le readme d'origine �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="201" id="201"></a>[201] 1ppv4 : Ic�nes de sorts et de parchemins uniformes

Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/201.jpg">

Ce composant harmonise le graphisme des ic�nes de sorts utilis� par Baldur's Gate II avec celui du jeu original. Il met aussi � jour les ic�nes dans les livres de sorts, dans les �crans utilisateurs, ainsi que celles des parchemins de sort.</br>
<a href="1pp/documentation/files/spic_readme-french.html">Plus de captures d'�cran �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="202" id="202"></a>[202] 1ppv4 : Ajustements de sorts

Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/202.jpg">

Des ajustements mineurs de sorts pour SoA/ToB, comme l'attribution d'effets visuels distincts aux sorts d'armure (Armure fantomatique, Armure spirituelle), ainsi que le remaniement des sorts de type � cause des blessures �, en les alignant sur leurs �quivalents P&amp;P et en les rendant v�ritablement viables.</br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="203" id="203"></a>[203] 1ppv4 : R�tablissement des animations d'�p�es enflamm�es

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/203.jpg">

Ce composant r�tablit les animations sp�cifiques des �p�es enflamm�es pour Baldur's Gate II (identiques � celles du jeu original). Il installe aussi des �p�es courtes enflamm�es, ajoutant ainsi une nouvelle cat�gorie d'objet dans le jeu.</br>
<a href="1pp/documentation/files/fs_readme-french.html">Consulter le readme d'origine �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="204" id="204"></a>[204] 1ppv4 : Coloration des b�tons

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/204.jpg">

Ce composant permet de personnaliser l'apparence des b�tons en les colorant par segment (des parties pr�d�finies du b�ton, contrairement au jeu qui leur attribue une couleur uniforme) ; ce qui permet de diversifier les b�tons du jeu et de faire correspondre leur apparence � celles de leurs ic�nes dans l'�cran d'inventaire. Il patche aussi les b�tons du jeu pour profiter de ce nouveau contenu.</br>
<a href="1pp/documentation/files/qs_readme-french.html">Consulter les notes de d�veloppement �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="205" id="205"></a>[205] 1ppv4: Boucliers de BG1 v2

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/205.jpg">

Ce composant remplace les animations classiques de boucliers par celles de Baldur's Gate I, correctement reconstruites et redessin�es. Il a �t� r�alis� gr�ce au soutien inestimable de l'�quipe de BG:EE.</br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="206" id="206"></a>[206] 1ppv4 : Animations suppl�mentaires de boucliers (fichiers de base)

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/206a.jpg">

<img src="1pp/documentation/files/206b.jpg">

Ce composant installe des versions modifi�es des animations de boucliers de Baldur's Gate II, ainsi que plusieurs nouveaux types de boucliers. Il comporte aussi une version de bouclier qui utilise les animations d'un autre, mais poss�de ses propres paperdolls.</br>

###### <em>N'oubliez-pas qu'il s'agit d'un composant basique : il ne modifie aucun objet. Son installation permettra aux composants suivants de vous proposer des options suppl�mentaires lors de la mise � jour des objets et des sorts.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="207" id="207"></a>[207] 1ppv4 : B�tons de magiciens (fichiers de base)

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/207.jpg">

Ce composant installe une nouvelle animation de b�ton (le b�ton du magicien), ainsi que plusieurs nouveaux paperdolls pour les autres b�tons color�s.</br>

###### <em>N'oubliez-pas qu'il s'agit d'un composant basique : il ne modifie aucun objet. Son installation permettra aux composants suivants de vous proposer des options suppl�mentaires lors de la mise � jour des objets et des sorts.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="208" id="208"></a>[208] 1ppv4 : Animations suppl�mentaires de casques (fichiers de base)

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/208a.jpg">
<img src="1pp/documentation/files/208b.jpg">

Ce composant am�liore les animations de casques de Baldur's Gate II original, et installe cinq nouvelles animations de casques (dont l'un n'est pas repr�sent� dans les captures d'�cran ci-dessus). Il installe �galement des bandeaux visibles sur la t�te des personnages !</br>

###### <em>N'oubliez-pas qu'il s'agit d'un composant basique : il ne modifie aucun objet. Son installation permettra aux composants suivants de vous proposer des options suppl�mentaires lors de la mise � jour des objets et des sorts.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="209" id="209"></a>[209] 1ppv4 Ailes amovibles (fichiers de base)

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/209.jpg">

Ce composant ajoute des ailes dont les personnages elfes peuvent s'�quiper (avec quelques restrictions d'usage).</br>
<a href="files/wings_readme-french.html">Consulter le readme d'origine &amp; les notes de d�veloppement �</a></br>

###### <em>N'oubliez-pas qu'il s'agit d'un composant basique : il ne modifie aucun objet. Son installation permettra aux composants suivants de vous proposer des options suppl�mentaires lors de la mise � jour des objets et des sorts.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="210" id="210"></a>[210] 1ppv4 : Plus de diversit� de paperdolls d'objets (fichiers de base)

<strong>Composant pr�-requis : <a href="#101">[101]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/210.jpg">

Ce composant augmente la vari�t� de paperdolls disponibles en ajoutant des variantes pour repr�senter des objets utilisant les m�mes animations. Cela comprend des paperdolls sp�cifiques pour afficher les �p�es b�tardes, divers types de fl�aux, les masses, les arcs courts, et plus encore (tous ne sont pas pr�sents sur l'image ci-dessus).</br>

###### <em>N'oubliez-pas qu'il s'agit d'un composant basique : il ne modifie aucun objet. Son installation permettra aux composants suivants de vous proposer des options suppl�mentaires lors de la mise � jour des objets et des sorts.</em></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="400" id="400"></a>[400] 1ppv4: Mise � jour et modification des objets

<strong>Composants pr�-requis : <a href="#101">[101]</a> <a href="#200">[200]</a> (pour SoA/ToB/Tutu)</strong></br>
<strong>Composants recommand�s : <a href="#203">[203]</a> <a href="#204">[204]</a> <a href="#205">[205]</a> <a href="#206">[206]</a> <a href="#207">[207]</a> <a href="#208">[208]</a> <a href="#209">[209]</a> <a href="#210">[210]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span></br>

Il s'agit du composant principal de mise � jour de 1ppv4. Avant de l'ex�cuter, assurez-vous d'avoir install� tous les composants que vous souhaitez utiliser (les composants recommand�s offriront des choix d'installation et du contenu suppl�mentaires). Les captures d'�cran suivantes illustrent les options d'installation par d�faut, sauf indication contraire.</br>

<img src="1pp/documentation/files/400h4.jpg">
<img src="1pp/documentation/files/400s4.jpg">
<img src="1pp/documentation/files/400ss.jpg">

Divers choix vous seront propos�s pendant d'installation (en fonction de votre jeu IE et des composants que vous avez install�s). Pour avoir un aper�u complet des options, veuillez consulter le lien ci-dessous. Si vous souhaitez affecter des couleurs pr�-d�finies aux objets non magiques, choisissez les options 2 ou 3 du r�glage 4 (COULEURS DES OBJETS PR�-D�FINIES).</br>
<a href="1pp/documentation/files/v4u_readme-french.html">Autres options d'installation �</a></br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="401" id="401"></a>[401] 1ppv4: Rendu des projectiles am�lior�

<strong>Composants pr�-requis : <a href="#200">[200]</a> <a href="#400">[400]</a></strong></br>
Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/401.jpg">
<img src="1pp/documentation/files/401b.jpg">

Ce composant am�liore les effets visuels des projectiles de Baldur's Gate II. Vous pourrez d�tecter quel genre de billes, fl�ches ou carreaux sont tir�s sur vous, ou si vous �tes vraiment distrait(e), que <em>vous</em> tirez. Il comprend des projectiles color�s de billes, de carreaux, de haches et de fl�chettes, et, ce qui est encore plus chouette, vous pouvez distinguer les diff�rents types de munitions sur votre paperdoll !</br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="300" id="300"></a>[300] 1ppv4 : Correction des animations des solaires et des �l�mentaires

Disponible pour : <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span></br>

<img src="1pp/documentation/files/300.jpg">

Ce composant modifie le rendu visuel des animations des solaires dans les jeux utilisant le moteur de ToB, ainsi que celui des �l�mentaires de feu (plus transparents).</br>

<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>

------------------------

### <a name="301" id="301"></a>[301] 1ppv4 : Correction d'autres �l�ments divers

Disponible pour : <span style="color:#060">SoA</span>, <span style="color:#700">ToB</span>, <span style="color:#080">Tutu</span>, <span style="color:#088">HoW</span>, <span style="color:#666">IWDII</span></br>

<img src="1pp/documentation/files/301.jpg">

Ce composant apporte des corrections aux �l�ments suivants : animations de chien (palette corrompue), de roturi�re assise (mauvaise conversion des fichiers BAM), variante de l'animation de g�ant du feu (qui �tait inutilisable car elle ne disposait pas d'une palette uniforme). Il corrige aussi un bug dans SoA/ToB et IWD:TotLM, li� au moteur du jeu, qui affiche de mani�re al�atoire de mauvaises s�quences des casques lorsque vous changez d'�quipement, les faisant �&#160;flotter � sur votre personnage. Enfin, il contient un correctif au bug du tampon de profondeur [<em>NdT : gestion de l'�limination des parties cach�es</em>] des boucliers sur les animations de personnages de BGII dans SoA, ToB, IWD:TotLM et IWDII.</br>
<div style="text-align:right"><a href="#components">Retour � la liste des composants</a></div>


<hr>


## Remerciements

Pour toute question ou demande d'assistance, veuillez consulter le <a href="http://www.shsforums.net/index.php?showforum=159">forum du mod</a>.

#### Programme d'installation et contenu : Erephine


#### Logiciels et outils utilis�s pour la cr�ation de ce mod (parmi d'autres)

- <a href="http://www.weidu.org/%7Ethebigg/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> de Wes Weimer, the bigg et Wisp.
- <a href="http://notepad-plus-plus.org/">Notepad++</a> par l'�quipe de Notepad++, Don Ho, et le plug-in de correction orthographique.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a> de Argent77.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a> de Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a> de Andrew Bridges.
- <a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a>.
- <a href="http://www.gimp.org/"><acronym title="GNU Image Manipulation Program">GIMP</acronym></a> par l'�quipe de the GIMP.
- <a href="http://www.gamani.com/">GIF Movie Gear</a>.
- <a href="https://www.autodesk.com/products/3ds-max/overview">3ds Max</a>.
- <a href="http://www.shsforums.net/files/file/552-developer-files-v2/">1pp dev tools</a> de Erephine.
- <a href="http://" target="_blank">Hex Editor Neo</a>.
- <a href="http://" target="_blank">ACDSee Pro</a>.
</br>
<div style="text-align:right"><a href="#components">Retour en haut de page</a></div>


<hr>


## Historique des versions

##### Version 4.2.0 - xx mm 2019

a. General overhaul and re-looking:
  - Variables needed for installation are read from 1pp-config-default.ini or 1pp-config.ini files.
  The previous version interrupted installation with plain text prompts allowing players to customise components to their liking (depending on which IE game the mod is installed for and already installed components). All those variables set during installation have been moved into 1pp-config-default.ini file in 1pp folder. This file provides a 'standard' installation. If players want to define their own customized installation, they have to modify the variables involved in 1pp-config-default.ini and save this file as 1pp-config.ini. The installation process will read both ini files and prioritize user values. If a value is not set or mismatched in 1pp-config.ini, any installation failure will be prevented by reverting it back to its default value.
  - Integrated all BWP Fixpack fixes (thanks Lolorian, The Imp and others!).
  - Split huge [400] Core updates and item patches component into smaller ones (checking 2500 or 3000 lines is easier when you search a glitch or a bug in more than 16000 lines of code!).
  - Code commented as much as possible.
  - Coding simplification:
    - Replaced macros with functions whenever possible.
    - Copy entire folders instead of infinite lines (COPY \~1pp/folder/file.ext\~ \~override\~ or ACTION_FOR_EACH file IN list BEGIN COPY \~1pp/folder/file.ext\~ \~override\~ END).
    - Group actions or patches with ACTION_FOR_EACH and PATCH_FOR_EACH whenever possible.
    - Used new and more efficient WeiDU functions (not released when Erephine wrote this mod) and Gwendolyne's patch functions to optimize the coding (e.g. ADD_ITEM_EQEFFECT, ALTER_EFFECT and ALTER_ITEM_HEADER replace so many lines of codes!).
    - Avoids copying and overwriting the same files again and again...
  - Updated readme (1pp now supports translated readmes).
  - Added French translation (Gwendolyne).
  - Traification. Feel free to provide me with translations. I will include them as soon as possible.
  - Updated WeiDU installer to v246.

b. Components specific changes and fixes:
  - [114] 1ppv4: Softer Spell Effects (114_effects.tph)
    - Replaced READLN action \~WARNING: This component will only work properly with 3D support enabled (alpha blending). Installing this component on BG2 in software rendering mode IS NOT A GOOD IDEA.\~ with reading '3D Acceleration=1' in baldur.ini before running the component.
    - Function GW_MODIFY_PROJ replaces Lollorian's BWP Fixpack patch (114_effects.tph.patch: modify new projectile values in ALL spell headers) which was inefficient and patched nothing. Moreover, it was using a wrong offset coding for ITM files.

  - [200] 1ppv4: Core content patches (200_1ppv2_cut.tph)
    - Added a new setting (1pp_hammers_icons) allowing to make alternate the overwriting of the Runehammer icon (saves vanilla IHAMM10 icon and installs new IHAMM10 1pp icon as IHAMM05B), and not to set Borok's Fist's icon to Runehammers.
    - Code simplified or re-written with newer functions to provide automatic process:
      - Replaced WRITE_LONG 0x3E 0 and WRITE_ASCII 0x3A \~ISHLDS01\~ with WRITE_ASCII 0x3A \~ISHLDS01\~ #8. Id. with offsets 0x48 0x44, and 0x5C 0x58.
      - Used DELETE_EFFECT and CLONE_EFFECT combo to add new equiped color effects, which avoids writing lines of codes!
    - 1ppv2 BAMs: saved a few vanilla inventory icons for modding purpose (Club of Detonation +3, Splint Mail +1, Chain Mail +3, Mage Robe of Cold Resistance, Mage Robe of Fire Resistance, Mage Robe of Electric Resistance, Knave's Robe, Traveler's Robe, Adventurer's Robe, Robes of the Good, Neutral, and Evil Archmagi, Suryris's Blade +2, Ravager +4, Halberd +3, The Eyes of Truth, Helm of the Rock, Helm of the Rock, Leather Armor, Studded Leather Armor, Plate Mail, Mithral Field Plate +2, Quiver of Plenty +1, Bastard Sword +2, Celestial Fury +3, Short Sword of Mask +4, Angurvadal +4, Foebane +3, Purifier +4, Yamato +4, Usuno's Blade +4, Spectral Brand +4, Hindo's Doom +3, Bastard Sword +3, Katana +3, Scimitar +3, The Answerer +4, Gram the Sword of Grief +5). Instead of definitively overwriting them, it now saves them with V suffixe before overwriting them, and does not overwrite anymore the following icons that are irrelevant (EE does not validate this change) : does not replace iax1h14.bam (Axe of the Unyielding +3) with the very inaccurate IWD Celebrant's Blade icon, idagg11.bam (Boomerang Dagger) with a clone of IMISC75 (Dagger of Venom), and isw1h06.bam (Varscona +2) with a clone of ISW1H41 (Long Sword +2). Does not overwrite Harbinger's icon and copies an alternate resource for modding purpose (isw2h07B). This way, Harbinger keeps its golden icon which fits to its colors settings.
    - specific fixes:
      - dagg21.itm & dagg22.itm (Daggers of the Star): reverted to their original inventory icon IDAGG21. 1PP sets them to IDAGG18 (Shadow Thief Dagger icon), but EE does not validate this change.
      - halb07.itm (Halberd +2): reverted to its original inventory icon IHALB07. 1PP sets it to IHALB03 (Suryris's Blade +2 icon), but EE does not validate this change.
      - sw1h31.itm (Daystar +2): reverted to its original inventory icon ISW1H31. 1PP sets it to ISW1H34 (Albruin +1), but EE does not validate this change. Then switches back its colorisation with Albruin (400_update_bgii_swords).
      - sw1h34.itm (Albruin +1): reverted to its original inventory icon ISW1H34. 1PP sets it to ISW1H31 (Daystar +2), but EE does not validate this change. Then switched back its colorisation with Daystar (400_update_bgii_swords).
      - sw1h41.itm (Long Sword +2): reverted to its original inventory icon ISW1H41. 1PP sets it to SW1H06 (Varscona +2 icon), but EE does not validate this change. Then removed the colorisation modified by 400_update_bgii_swords and sets it to SW1H73 (Long Sword +3) that deserves those settings.
      - sw2h10.itm and sw2h19.itm (Carsomyr +5 and +6): reverted to their original inventory icon ISW2H10. 1PP sets them to ISW2H20, but EE does not validate this change.
      - sw2h11.itm (Two-handed Sword +2): reverted to its original inventory icon ISW2H11. 1PP sets it to ISW2H03, but EE does not validate this change.
      - sw2h20.itm (Two-handed Sword +3): reverted to its original inventory icon ISW2H20. 1PP sets it to ISW2H06, but EE does not validate this change.
      - BW Herbs mod patches: fixed typo (was copying BW02IPO1_l.BAM instead of BW02IPO1.BAM).

  - [201] 1ppv4: Consistent spell and scroll icons (201_spellsandscrolls.tph)
    - BWP Fixpack patch: restored Energy Blades spell and scroll icons (SPWI920) overwritten with Black Blade of Disaster's ones.

  - [202] 1ppv4: Spell tweaks (202_spelltweaks.tph)
    - BWP Fixpack patch for individualised armor effects {202_spelltweaks.tph.patch): modifies opcode #215 visual effect in ALL spell headers.

  - [208] 1ppv4: Additional Helmet Animations (208_v4_helmets.tph)
    - Lollorian's BWP Fixpack JC Helm animation crash fix for Infinity Animations BG1 animation compatibility (208_v4_helmets.tph.patch): 1ppv4's helmet component seems to cause crashes when helmets using the JC animation are equipped by NPCs using BG1 animations from Infinity Animations (http://www.shsforums.net/topic/55047-1ppv410-release-download-discussion/?p=561441).

  - [210] 1ppv4: Increased paperdoll object variety (210_v4_ppd_variety.tph)
    - CRE files: used READ_LONG 0x28 instead of READ_SHORT 0x28 (dword).
    - Coding simplification:
      - ITM files: used WRITE_LONG 0x18 (THIS BAND BNOT BIT2) to remove droppable flag instead of writing the offset new value.

  - [300] 1ppv4: 1ppv4: Fixed animations for solars and elementals (300_solar_fix.tph)
    - The Imp's BWP Fixpack fix for Solar swords without graphic artifacts (http://www.shsforums.net/topic/58208-planetar-animation-glitch/): fixed MASLG1S1.BAM and MSOLG2S1.BAM files.
      Source: https://github.com/omni-axa/BiG-World-Fixpack/commit/de7b3ce8439d8efa8e7427d1ad66efd0f48e547e

  - [400] 1ppv4: Core updates and item patches (400_1pp_update_bgii.tph)
    - Split this huge component into smaller ones (checking 2500 or 3000 lines is easier when you search a glitch or a bug in more than 16000 lines of code!).
    - Added a new setting (1pp_hammers_icons) allowing to make alternate the overwriting of the Runehammer icon (saves vanilla IHAMM10 icon and installs new IHAMM10 1pp icon as IHAMM05B), and not to set Borok's Fist's icon to Runehammers.
    - Added a new setting (1pp_sleeper) allowing to make alternate the turning of The Sleeper into a flail. In any case, 1PP does not overwrites its original inventory bam with a new one, but installs a new icon (IBLUN16B) as an alternate, and saves the vanilla icon for compatibility with other mods purpose.
    - Replaced the tooltip section with two new functions that 1) add a fourth column if needed, 2) automatically writes values in tooltip.2da from the tra file.
    - Lollorian's BWP Fixpack patch for Ashes of Embers compatibility (400_1pp_update_bgii.tph.patch): Renames 1PPv4 BAND0X.ITMs to XOBAND0X.ITMs, using Lollorian's prefix (according to BWL: XO, submitted by Chaplain, 11.03.2010, Prefix owner also known as Lollorian). Source: http://www.shsforums.net/topic/56643-1pp-circlets-and-bg2tweaks-issue/?p=561849
    - Gems sub-component: code simplified and re-written to avoid overwriting files when selecting option no lore needed for identification (1pp_gemlore = 2). Builds an array to define new gems lore values to identify. Same tph used for IWD and BG2 games.
    - Code simplified or re-written with newer functions to provide automatic process:
      - Replaced WRITE_LONG 0x3E 0 and WRITE_ASCII 0x3A \~ISHLDS01\~ with WRITE_ASCII 0x3A \~ISHLDS01\~ #8. Id. with offsets 0x48 0x44, and 0x5C 0x58.

    - shields specific fixes (400_update_bgii_shields.tpa):
      - shld02.itm (Small Shield +1): LPM \~clear\~ was missing, and the code stacked opcode #7 global effects.
      - shld31A.itm (Gorm's Arm +3): fixed wrong coding (WRITE_SHORT instead of WRITE_BYTE for Minimum strength).
      - shld01P.itm (Buckler +2): fixed wrong coding (opcode #0 parameter1 0xfffffe - 16777214??? - should be -3), added opcode #0 with parameter1 = -3 and parameter2 = 4 to add missing protection vs piercing weapons, added missing price, and fixed item description to fit ITM file.
      - X#AJSHLD.itm (Ilvastarr Family Shield - The BG1 NPC Project mod): fixed typo (was copying #AJSHLD instead of X#AJSHLD).
      - shld06P.itm (Redshield +1, +4 vs. Monstrous): fixed wrong coding (opcode #219: switch parameter1 and 2, and parameter2 2 - EA.IDS - should be 3 - GENERAL.IDS), added an external effect (shld06P.eff), and replaced opcode #178 with opcode #177, otherwise opcode #178 won't work.
      - shld07P.itm (Sartessa's Vengeance +1): fixed wrong coding for add magical flag [replace WRITE_BYTE 0x1b 0x6c with WRITE_LONG 0x18 (THIS | BIT6)].
      - shld08P.itm (Tarloc's Contingency +1): code simplified (1tarsp.spl) and fixed wrong coding for Casting sound (1tarss.spl).
      - shld09P.itm (Shield of Devotion +1): fixed wrong coding (#62: parameter2 should be 4, not 3).
    - helmets specific fixes (400_update_bgii_helmets.tpa):
      - helm33.itm (Gold Horned Helm): fixed typo (was copying helm22 instead of helm33).
      - xoband02.itm (Silver Circlet): fixed wrong coding opcodes #33, 34 & 35 (parameter2 originally set to 1 should be 0) and added opcodes #36 & 37 to match item description (+1 to saving throws).
      - xoband03.itm (Eilistraee's Boon +1): same fixes for opcodes #33, 34, 35, 36 & 37. Fixed wrong coding opcode #31: parameter1 originally set to 110, should be 10, and parameter2 switched from 2 to 0 to match item description (+10% magic damage resistance).
      - xoband04.itm (Circlet of the Archmagi): same fixes for opcodes #33, 34, 35, 36 & 37. Added one missing equipped effects (LPM ADD_ITEM_EQEFFECT #19).
    - weapons specific fixes (400_update_bgii_weapons.tpa):
      - dagg12.itm (Firetooth +3): fixed typos in LPM \~pulse\~ function (redundant setr variable set to 152 and 189 should be setg and setb, otherwise they overwrite the setr value and don't set the correct setg and setb values).
      - halb08.itm (Duskblade +2): fixed a typo copying halb06 instead of halb08.
      - hamm10.itm & hamm11.itm (Runehammers): new 1pp_hammers_icons setting gives the choice to assign them, or not, the Borok's Fist's icon.
    - miscellaneous specific fixes (400_update_bgii_misc.tpa):
      - misc89.itm (Edwin's Amulet): added bgmisc89 (BGT and IR compatibility).
      - book06.itm (Tome of Clear Thought), book07.itm (Tome of Leadership and Influence) and book08.itm (Tome of Understanding): harmonized header icon with new inventory icon (IBOOK768) for consistency.
    - swords specific fixes (400_update_bgii_swords.tpa):
      - Does not overwrite Varscona's icon with a clone of ISW1H41 (Long Sword +2) because EE does not validate this change.
      - sw1h31.itm (Daystar +2): as 1PP (Core content patches) sets its icon to ISW1H34 (Albruin +1), but EE does not validate this change, this version reverts to its original inventory icon ISW1H31, and this component switches back its colorisation with Albruin.
      - sw1h34.itm (Albruin +1): as 1PP (Core content patches) sets its icon to ISW1H31 (Daystar +2), but EE does not validate this change, this version reverts to its original inventory icon ISW1H31; and this component switches back colorisation with Daystar.
      - sw1h41.itm (Long Sword +2): as 1PP (Core content patches) sets its icon to SW1H06 (Varscona +2 icon), but EE does not validate this change, this version reverts to its original inventory icon ISW1H41. Then, this component removes its re-colorisation and sets it to SW1H73 (Long Sword +3) that deserves those settings.
      - sw2h06.itm and sw1h13.itm (Spider's Bane +2): harmonized both versions. Now they get the same icon and coloration (no change from vanilla SW1H13 as its colors fit the new icon installed by 1PP).
      - sw2h07.itm (Harbinger +3): does not overwrite Harbinger's icon and copy an alternate resource for modding purpose. This way, Harbinger keeps its golden icon which fits to its colors settings.
      - SW1P01.itm (Viper's Edge +2): removed the #134 global effect (Petrification) otherwise it would be impossible to wield the sword. Fixed wrong coding (the extended effects were not implemented) and modified the cursed effects probabilities, so that they don't stack when not necessary (e.g. why should you be poisoned when petrified?).
    - blunt weapons specific fixes (400_update_bgii_blunt.tpa):
      - blun16.itm (The Sleeper +2): new 1pp_sleeper setting gives the choice to turn it into a flail. If turned into a flail, modifies minimum strength value and uses a new icon (IBLUN16B) to avoid overwriting the vanilla one (let's keep it for modders!).
    - armors specific fixes (400_update_bgii_armors.tpa):
      - chan03B.itm (Werebane Mail +2): added missing identified name.
      - plat15.itm (Pride of the Legion +2): reverted its inventory and description icons (wrongly set to IPLAT23 and CPLAT05) as EE does not validate this change.
      - plat23.itm (Full Plate Mail +2): removed from the patches as EE does not validate them (this silver and golden full plate was turned into a black one!).
    - new staves specific fixes (400_update_bgii_staves2.tpa):
      - Avoids copying and overwriting the same files again and again...
      - MACRO GW_ADJUST_TOOLTIP: ADDS new colums in tooltip.2da (makes sure it contains at least 4 columns, so we can add Narbucchad's Demise ability).
      - FUNCTION GW_ADD_TOOLTIP: ADDS new entries in tooltip.2da.
    - scatters items specific fixes (400_update_bgii_scatter.tph):
      - Coding simplification:
        - Replaced combo ADD_STORE_ITEM + REMOVE_STORE_ITEM with LPF REPLACE_STORE_ITEM.
        - Replaced two ADD_STORE_ITEM #1 with one ADD_STORE_ITEM #2.
      - dmark1.sto (Fovem, Docks merchant) & trmer02.sto (Trademeet merchant): set number_in_stock to 2, otherwise the former code did not work (was supposed to add one Plate and remove the Plate +1, but there was already 1 Plate in the store!

  - [401] 1ppv4: Improved projectile effects (401_projectiles.tph)
    - Code fully re-written with new functions to provide automatic process.
      - Function GW_CLEAR_DUPLICATED_OPCODES: does not stack anymore opcodes #83 and #197, clears duplicated vanilla #89 and #197 effects in SPL and ITM files and checks if protection from SPEAR and/or Bounce SPEAR is already set before adding it.
      - Function GW_MODIFY_PROJ replaces BWP Fixpack patch (401_projectiles.tph.patch): modifies the projectile value only when needed (does not patch melee headers anymore), replaces ADD_ITEM_EQEFFECT, ADD_ITEM_EFFECT, ADD_SPELL_EFFECT and macros with the newer and more efficient CLONE_EFFECT WeiDU function to give new opcodes #83 and #197 the same settings than existing ones (target, resist_dispel, duration, power...). It modifies all extended headers and avoids writing lines of codes!
      - Provided partial IR and SR compatibility in a rather soft way.
    - specific fixes:
      - ax1h08.itm (Hangard's Axe +2), ax1h09.itm (Rifthome Axe +3), ax1h10.itm (Azuredge +3) and ax1h16.itm (K'logarath +4): added IR compatibility (patches itemB files).
      - bolt09.itm (Bolt +3): fixed typo (was patching bolt06 instead of bolt09).
      - Sets new projectiles to Quivers of Plenty, Cases of Plenty, Bags of Plenty and Sling of Everard: Why quivers and launchers needing no ammo should not get new 1pp projectiles?
      - dagg11.itm (Boomerang Dagger +2) and dagg12.itm (Firetooth +3): added IR compatibility (patches itemB files).
      - sper04.itm (Javelin): switched Thrown and Melee strings ref in tooltip.2da.
      - items aurstaf, dragring, magebra, slayerwp and globblu4 (Blue Globe): added missing protections from new normal 1pp ammo projectiles (1axe05, 1dagg05 and 1dart01). The code was only providing protection from 1arow01 and 1bolt01 new projectiles.
      - npshld.itm (Delryn Family Shield): same fix as above + IR compatibility (protection from all types of missiles, including magic ones).
      - shld24.itm (Reflection Shield +1): same fix as above + cleared duplicate entries and adds IR compatibility (IR replaces opcode #197 with opcode #83).
      - brac18.itm (Gloves of Missile Snaring): Don't forget to add Protection from projectiles if IR is installed.
      - spin546.spl (Inertial Barrier), spcl721.spl (Storm Shield) & spcl914.spl (Greater Evasion): patched all headers (was patching only the first header), fixed wrong duration, target, power, resist dispel... Added missing protections from new normal 1pp ammo projectiles (1axe05, 1dagg05 and 1dart01). The code was only providing protection from 1arow01 and 1bolt01 new projectiles.
      - Protection From Normal Missiles spells (spra303, spwi311, & cdwi311 added from BG2 Fixpack): same fixes as above + SR compatibility (protection from all types of missiles, including magic ones).
      - sppr613.spl (Physical Mirror): cleared duplicate entries and added SR compatibility (SR replaces opcode #197 with opcode #83).
      - Included Entropy Shield spell (protection from new 1pp projectiles) if IWDIfication is installed.


##### Version 4.1.0 - 12 novembre 2012

- Les boucliers en �caille ont d�sormais leurs propres animations.
- c�nes de descriptions am�lior�es import�es de BG I.
- Correction du chevauchement de l'interface graphique � basse r�solution.


##### Version 4.0.0 - 6 ao�t 2012

- Sortie initiale.
<div style="text-align:right"><a href="#components">Retour en haut de page</a></div>
