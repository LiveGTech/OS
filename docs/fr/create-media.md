# Créer des supports d'installation LiveG OS
Pour installer LiveG OS sur un périphérique existant, vous devrez copier LiveG OS sur un périphérique de stockage portable (comme un bâton de mémoire USB) qui peut être connecté au périphérique cible.

Visitez [liveg.tech/os/get](https://liveg.tech/os/get) pour en savoir plus sur les exigences minimales que le périphérique de stockage doit répondre.

LiveG OS ne peut pas être copié sur le périphérique de stockage en copiant simplement le fichier sur le système de fichiers de l'appareil. Au lieu de cela, l'ensemble du périphérique de stockage doit être effacé et _flashé_, qui copie correctement la configuration LiveG OS afin qu'il soit démarrable sur le périphérique cible. Cela peut être fait avec des logiciels tiers, comme indiqué plus loin dans ce guide.

Avant de commencer, téléchargez LiveG OS sur un ordinateur (il peut s'agir de l'ordinateur sur lequel vous souhaitez installer LiveG OS). Nous copierons ensuite le fichier ISO (.iso) sur le périphérique de stockage à l'aide de l'un des programmes disponibles répertoriés ci-dessous. Assurez-vous que votre périphérique de stockage est connecté à cet ordinateur.

> **Avertissement :** La copie de la configuration LiveG OS nécessite que toutes les données sur le périphérique de stockage soient effacées au préalable. Assurez-vous que vous sauvegardez le périphérique de stockage ailleurs avant de le copier LiveG OS.

## En utilisant balenaEtcher
balenaEtcher est compatible avec les périphériques exécutant Windows, MacOS ou Linux.

Téléchargez balenaEtcher à partir de [balena.io/etcher](https://www.balena.io/etcher/) et installez-le sur un ordinateur (il peut s'agir de l'ordinateur sur lequel vous souhaitez installer LiveG OS).

Ouvrez balenaEtcher et appuyez sur **flash from file**. Sélectionnez le fichier ISO pour LiveG OS dans le sélecteur de fichiers. Une fois le fichier choisi, sélectionnez le périphérique de stockage pour copier le fichier ISO en appuyant sur **change** s'il n'est pas déjà sélectionné. Enfin, appuyez sur **flash!** et attendez que la copie se termine. Une fois terminé, éjectez le périphérique de stockage, à partir duquel il sera prêt à l'emploi.

Pour plus d'aide et de support avec l'utilisation de balenaEtcher, visitez [balena.io/etcher](https://www.balena.io/etcher/).

## En utilisant Rufus
Rufus est compatible avec les appareils exécutant uniquement Windows.

Téléchargez Rufus à partir de [rufus.ie](https://rufus.ie/) et installez-le sur un ordinateur (il peut s'agir de l'ordinateur sur lequel vous souhaitez installer LiveG OS).

Ouvrez Rufus et sélectionnez le périphérique de stockage dans la liste **périphérique**. Sous **type de démarrage**, sélectionnez **disque ou image ISO (veuillez sélectionner)**, puis appuyez sur le bouton **sélection**. Sélectionnez le fichier ISO de LiveG OS dans le sélecteur de fichiers. Une fois le fichier choisi, appuyez sur **démarrer** et attendez que la copie se termine. Une fois terminé, éjectez le périphérique de stockage, à partir duquel il sera prêt à l'emploi.

Pour plus d'aide et de soutien à l'utilisation de Rufus, visitez [rufus.ie](https://rufus.ie/).

## En utilisant UNetbootin
UNetbootin est compatible avec les périphériques exécutant Windows, MacOS ou Linux.

Téléchargez UNetbootin à partir de [unetbootin.org](https://unetbootin.org/) et installez-le sur un ordinateur (il peut s'agir de l'ordinateur sur lequel vous souhaitez installer LiveG OS).

Ouvrez UNetbootin et sélectionnez **diskimage**. Appuyez sur **...** et sélectionnez le fichier ISO de LiveG OS dans le sélecteur de fichiers. Sélectionnez le périphérique de stockage dans la liste **drive**. Appuyez sur **OK** et attendez que la copie se termine. Une fois terminé, éjectez le périphérique de stockage, à partir duquel il sera prêt à l'emploi.

Pour plus d'aide et de support avec l'utilisation de UNetbootin, visitez [unetbootin.org](https://unetbootin.org/).