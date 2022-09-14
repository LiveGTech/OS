# Installez LiveG OS sur un appareil
Si un appareil que vous avez n'exécute pas encore LiveG OS, vous devrez installer LiveG OS sur le stockage interne de cet appareil. Ces étapes doivent être suivies si votre appareil n'a aucun système d'exploitation installé (où vous obtenez un message d'erreur lorsque vous essayez de l'allumer), ou a un système d'exploitation différent (comme Microsoft Windows).

> **Remarque:** Si vous avez acheté un nouvel appareil livré avec LiveG OS, vous n'avez pas besoin de suivre ces étapes. Consultez [notre guide sur la configuration d'un appareil exécutant LiveG OS](setup.md) à la place.

## Avant de commencer
Vous aurez besoin d'un périphérique de stockage à portée de main pour installer LiveG OS avec (comme un bâton de mémoire USB). Assurez-vous que le périphérique de stockage est compatible avec l'appareil sur lequel vous souhaitez installer un LiveG OS.

Une fois que vous avez trouvé un périphérique de stockage, vous devrez ensuite le formater et copier la configuration LiveG OS dessus. Cela peut être fait en visitant [liveg.tech/os/get](https://liveg.tech/os/get) et en téléchargeant LiveG OS. D'autres étapes sur la façon de copier LiveG OS sur votre périphérique de stockage sont [indiquées dans notre guide](create-media.md).

> **Avertissement :** Lorsque la configuration LiveG OS est copiée, toutes les données sur le périphérique de stockage doivent être effacées au préalable. Assurez-vous que vous sauvegardez le périphérique de stockage ailleurs avant de le copier LiveG OS.

## Procédure de configuration
Les étapes suivantes ci-dessous devront être suivies pour installer LiveG OS.

### 1. Éteignez l'appareil si vous n'avez pas déjà fait
Reportez-vous au guide de l'utilisateur de votre appareil pour plus d'aide sur l'arrêt ou la désactivation de l'appareil.

Si votre appareil exécute Microsoft Windows, maintenez la touche <kbd>Shift</kbd> tout en arrêtant le système. Cela permet au menu BIOS / démarrage d'être accessible lorsque l'appareil est activé à nouveau.

### 2. Connectez le périphérique de stockage contenant du LiveG OS au périphérique d'installation
Si vous avez un bâton de mémoire USB avec LiveG OS installé dessus, branchez le bâton de mémoire.

### 3. Démarrez l'appareil et choisissez des options pour démarrer sur LiveG OS
Lorsque vous alimentez l'appareil, vous devrez dire à l'appareil de démarrer sur le périphérique de stockage connecté au lieu du stockage interne. Cela se fait généralement sur de nombreux appareils en maintenant une touche de clavier ou en appuyant sur une combinaison de volumes ou de boutons d'alimentation.

Cette procédure varie en fonction de l'appareil et qui l'a fabriquée, alors reportez-vous au guide de l'utilisateur de votre appareil pour plus d'aide à ce sujet, ou contactez votre fournisseur ou votre fabricant.

Pour les modèles d'appareil fabriqués par les fabricants suivants, vous devrez effectuer ce qui suit lorsque le logo du fabricant apparaît sur l'écran de l'appareil :

* **Acer** : Tenez la touche <kbd>F2</kbd> (ou <kbd>Del</kbd> sur certains modèles). Pour la plupart des modèles, utilisez les touches fléchées pour accéder à **boot**, puis sélectionnez le périphérique de stockage pertinent.
* **Asus** : Tenez la clé <kbd>F2</kbd>. Lorsque l'interface du BIOS apparaît, appuyez sur <kbd>F8</kbd>, puis sélectionnez le périphérique de stockage pertinent.
* **Dell** : Tenez la touche <kbd>F2</kbd>. Pour la plupart des modèles, utilisez les touches fléchées pour accéder à **boot**, puis sélectionnez le périphérique de stockage pertinent.
* **HP** : Tenez la touche <kbd>F9</kbd>, puis sélectionnez le périphérique de stockage pertinent à l'aide du clavier. Pour certains modèles, vous devrez peut-être accéder au menu du BIOS via les boutons <kbd>F10</kbd> ou <kbd>F1</kbd>.
* **Lenovo / ThinkPad** : Tenez les touches <kbd>FN</kbd> + <kbd>F12</kbd>. Pour la plupart des modèles, utilisez les touches fléchées pour accéder à **startup**, puis sélectionnez le périphérique de stockage pertinent. Pour certains modèles, <kbd>FN</kbd> + <kbd>F2</kbd> doit être utilisé à la place.

### 4. Attendez que LiveG OS commence
Cela devrait prendre moins d'une minute. Votre appareil aura démarré lorsque l'écran de sélection de la langue de configuration LiveG OS apparaît.

### 5. Sélectionnez votre langue
LiveG OS affichera une liste de langues qui seront utilisées dans tout le système. Dans cette liste, sélectionnez **français**.

### 6. Choisissez les paramètres de la langue
Une fois que vous avez choisi votre langue, vous serez en outre demandé dans quelle langue / variation de langue vous souhaitez lire du texte, en plus de la mise en page du clavier que vous souhaitez utiliser pour saisir du texte.

Par exemple, si vous parlez le français, vous sélectionnez **français (France)** pour **région / variation de langue** et **AZERTY** pour **disposition du clavier**.

Une fois que vous êtes satisfait des paramètres choisis, appuyez sur **suivant**.

### 7. Choisissez l'option pour installer LiveG OS
Choisissez l'option **installer LiveG OS sur le stockage interne**.

Si vous souhaitez essayer LiveG OS avant de l'installer, vous pouvez choisir l'option **essayez LiveG OS sans installation**, mais vous devrez redémarrer ces étapes à partir de l'étape 1 lorsque vous souhaitez installer LiveG OS.

### 8. Choisissez le disque interne à installer
Choisissez le disque que vous souhaitez installer LiveG OS dans la liste des options, puis appuyez sur **suivant**.

La taille totale de chaque disque est affichée sous chaque option afin qu'il soit plus facile pour vous de faire correspondre le disque correct (la taille du disque peut également être étiquetée sur la case avec laquelle votre appareil est venu).

### 9. Choisissez une partition de disque à installer
Nous vous recommandons de choisir le disque entier **effacez tout le disque et installez LiveG OS** car cela supprimera toutes les partitions qui ont été utilisées uniquement pour l'ancien système d'exploitation qui a été précédemment installé sur l'appareil.

Les utilisateurs avancés peuvent souhaiter choisir une autre option pour autoriser le double boot.

Une fois qu'une option a été choisie, appuyez sur **suivant**.

### 10. Confirmer l'installation
Lorsque vous êtes prêt à démarrer le processus d'installation, appuyez sur **confirmer**. Si vous souhaitez revoir les options que vous avez choisies, appuyez sur **précédent**.

> **Avertissement :** Pendant que LiveG OS est installé, les données sur le disque respectif choisi précédemment seront effacées. Assurez-vous de sauvegarder toutes les données importantes que vous souhaitez conserver sur un autre appareil avant de commencer l'installation.

### 11. Attendez que l'installation se termine
Cette étape devrait prendre quelques minutes pour copier LiveG OS en stockage interne et configurer votre appareil pour démarrer correctement en LiveG OS lorsque vous l'allumez.

Vous ne pouvez pas annuler l'installation pendant son exécution.

### 12. Redémarrez le système
Une fois l'installation terminée, le système redémarre après 10 secondes afin que vous puissiez continuer à configurer votre appareil. Vous pouvez également appuyer sur **redémarrer** pour redémarrer immédiatement le système.

Lorsque le système redémarre, nous vous recommandons de configurer à nouveau les options de démarrage au démarrage pour garantir que les bottes LiveG OS du stockage interne. Une fois redémarré, le périphérique de stockage d'installation peut être supprimé.

Lorsque le système a terminé le démarrage, continuez à configurer votre appareil en suivant les [instructions de configuration](setup.md).