==========================================================================

                       P R O T E U S   A D D O N S

==========================================================================

  WEAPON SELECTOR
  Sélecteur d'armes visuel inspiré du style Helix pour Garry's Mod.

   Plateforme   :  Garry's Mod
   Catégorie    :  Interface / Client
   Version      :  1.0.3
   Auteur       :  Proteus
   Licence      :  FREE

==========================================================================


--------------------------------------------------------------------------
  PRÉSENTATION
--------------------------------------------------------------------------

Proteus Weapon Selector remplace le sélecteur d'armes par défaut de
Garry's Mod par une interface plus sobre, plus légère et inspirée du
weapon selector du gamemode Helix.

Cette version est autonome et fonctionne sous DarkRP, Sandbox et les
gamemodes dérivés de Sandbox. Elle ne dépend pas de Helix et ne nécessite
aucun framework externe.


--------------------------------------------------------------------------
  PUBLIC VISÉ
--------------------------------------------------------------------------

Créateurs et administrateurs de serveurs Garry's Mod qui veulent une
interface d'armes plus propre, moderne et discrète pour leurs joueurs.

L'addon est particulièrement adapté aux serveurs DarkRP, RP, semi-RP,
Sandbox personnalisés et serveurs utilisant des packs d'armes.


--------------------------------------------------------------------------
  INSTALLATION
--------------------------------------------------------------------------

1. Placer le dossier "proteus_weaponselector" dans :

      garrysmod/addons/

2. Redémarrer le serveur ou changer de map.
3. Rejoindre le serveur.
4. Tester avec la molette, les touches de slots et le clic gauche.

L'addon se charge automatiquement côté client.


--------------------------------------------------------------------------
  COMMANDES ET CONTRÔLES
--------------------------------------------------------------------------

  Molette haut / bas     Ouvre le sélecteur et navigue entre les armes.
  Touches 1 à 6          Sélectionne une arme selon les slots Garry's Mod.
  Clic gauche            Équipe l'arme sélectionnée.
  Échap                  Ferme le sélecteur.
  Scoreboard             Ferme automatiquement le sélecteur.

Le sélecteur se ferme aussi automatiquement après un court délai sans
action, configurable dans sh_config.lua.


--------------------------------------------------------------------------
  DESIGN
--------------------------------------------------------------------------

Le design est volontairement simple, sombre et léger afin de se rapprocher
du comportement visuel Helix :

  - affichage central ;
  - mouvement circulaire fluide ;
  - textes blancs ;
  - arme sélectionnée mise en avant sans surcharge visuelle ;
  - fade in et fade out ;
  - animation de transition entre les armes ;
  - pas de compteur d'armes affiché ;
  - pas de fond derrière les instructions.

L'objectif est d'obtenir une interface propre, efficace et discrète.


--------------------------------------------------------------------------
  CONFIGURATION
--------------------------------------------------------------------------

Tout se règle dans :

      lua/proteus_weaponselector/sh_config.lua

Options principales :

  Enabled
      Active ou désactive l'addon.

  HideDefaultSelector
      Cache le sélecteur d'armes par défaut de Garry's Mod.

  CloseDelay
      Durée avant la fermeture automatique du sélecteur.

  AnimationSpeed
      Vitesse du fade in et du fade out.

  IndexSpeed
      Vitesse de transition entre les armes.

  Radius / Spacing / ShiftX
      Réglages de placement et de mouvement du sélecteur.

  Font / FontSize / FontWeight
      Réglages de police du nom des armes.

  ShowInstructions
      Affiche les instructions des SWEP si elles existent.

  ShowAmmo
      Affiche les munitions de l'arme sélectionnée.

  ShowCounter
      Affiche ou masque la position dans la liste. Désactivé par défaut.

  SortBySlot
      Trie les armes selon les slots Garry's Mod.

  DisabledWeapons
      Permet de masquer certaines armes du sélecteur.

--------------------------------------------------------------------------
  CRÉDITS
--------------------------------------------------------------------------

Design et comportement inspirés du weapon selector Helix.
Adaptation autonome DarkRP/Sandbox par Proteus.

Le code est indépendant et ne nécessite pas le gamemode Helix.


--------------------------------------------------------------------------
  NOTES ET LIMITES
--------------------------------------------------------------------------

- L'addon remplace seulement le sélecteur visuel.
- Certains SWEP peuvent ne pas fournir de nom, d'instructions ou de données
  de munitions propres. Dans ce cas, l'addon utilise les informations
  disponibles.
- Aucun commentaire dans le code source : toute l'information utile est
  centralisée dans ce fichier Readme.txt.


==========================================================================

                       E N G L I S H   V E R S I O N

==========================================================================

  WEAPON SELECTOR
  Helix-style visual weapon selector for Garry's Mod.

   Platform     :  Garry's Mod
   Category     :  Interface / Client
   Version      :  1.0.3
   Author       :  Proteus
   License      :  MIT

==========================================================================


--------------------------------------------------------------------------
  OVERVIEW
--------------------------------------------------------------------------

Proteus Weapon Selector replaces the default Garry's Mod weapon selector
with a cleaner, lighter interface inspired by the Helix gamemode weapon
selector.

This version is standalone and works with DarkRP, Sandbox and Sandbox-based
gamemodes. It does not require Helix or any external framework.


--------------------------------------------------------------------------
  TARGET USERS
--------------------------------------------------------------------------

Garry's Mod server creators and administrators who want a cleaner, modern
and discreet weapon selection interface for their players.

The addon is well suited for DarkRP, RP, semi-RP, custom Sandbox servers and
servers using weapon packs.


--------------------------------------------------------------------------
  INSTALLATION
--------------------------------------------------------------------------

1. Place the "proteus_weaponselector" folder in:

      garrysmod/addons/

2. Restart the server or change the map.
3. Join the server.
4. Test it with the mouse wheel, slot keys and left click.

The addon loads automatically on the client.


--------------------------------------------------------------------------
  CONTROLS
--------------------------------------------------------------------------

  Mouse wheel up / down   Opens the selector and cycles weapons.
  Keys 1 to 6             Selects a weapon using Garry's Mod slots.
  Left click              Equips the selected weapon.
  Escape                  Closes the selector.
  Scoreboard              Automatically closes the selector.

The selector also closes automatically after a short configurable delay.


--------------------------------------------------------------------------
  DESIGN
--------------------------------------------------------------------------

The design is intentionally simple, dark and lightweight to stay close to
the Helix visual behavior:

  - centered display;
  - smooth circular movement;
  - white text;
  - selected weapon highlighted without heavy visuals;
  - fade in and fade out;
  - smooth weapon transition;
  - no weapon counter;
  - no background behind instructions.

The goal is to keep the interface clean, efficient and discreet.


--------------------------------------------------------------------------
  CONFIGURATION
--------------------------------------------------------------------------

The configuration file is located here:

      lua/proteus_weaponselector/sh_config.lua

Main options:

  Enabled
      Enables or disables the addon.

  HideDefaultSelector
      Hides the default Garry's Mod weapon selector.

  CloseDelay
      Delay before the selector automatically closes.

  AnimationSpeed
      Fade in and fade out speed.

  IndexSpeed
      Weapon transition speed.

  Radius / Spacing / ShiftX
      Selector placement and movement settings.

  Font / FontSize / FontWeight
      Weapon name font settings.

  ShowInstructions
      Displays SWEP instructions when available.

  ShowAmmo
      Displays ammo for the selected weapon.

  ShowCounter
      Shows or hides the weapon list position. Disabled by default.

  SortBySlot
      Sorts weapons using Garry's Mod weapon slots.

  DisabledWeapons
      Allows specific weapons to be hidden from the selector.
 
--------------------------------------------------------------------------
  CREDITS
--------------------------------------------------------------------------

Design and behavior inspired by the Helix weapon selector.
Standalone DarkRP/Sandbox adaptation by Proteus.

The code is independent and does not require the Helix gamemode.
