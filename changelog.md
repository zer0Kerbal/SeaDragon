# Changelog
  
| modName    | Sea Dragon (SEA)                                                  |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | NecroBones and zer0Kerbal                                         |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209579-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/SeaDragon)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/SeaDragon)            |
| spacedock  | (https://spacedock.info/mod/440)                                  |
| ckan       | SeaDragon                                                         |

## Version 0.3.99.0-adoption - `<Thank you NecroBones>` edition

* Released
  * 21 Jan 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 0.3.99.0

* Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Changes 0.3.99.0

### Archival Releases

* Add
  * 0.3.4.0-release - `<Archival>` edition
  * 0.3.3.0-release - `<Archival>` edition
  * 0.3.2.0-release - `<Archival>` edition
  * 0.3.1.0-release - `<Archival>` edition
  * 0.3.0.0-release - `<Archival>` edition
  * 0.2.0.0-release - `<Archival>` edition
  * 0.1.0.0-release - `<Archival>` edition

### Localization 0.3.99.0

* Add
  * agency
* run localizer
* Localize
  * <SeaDragon.cfg> v1.0.0.0
    * adds localized tags to parts
* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* closes #8 - Create Localization directory and contents
* closes #10 - Create <SeaDragon.cfg>
* closes #13 - English <us-en.cfg>
* closes #30 - Part Localization
* updates #12 - Localization - Master

### Update License 0.3.99.0

* Updated License: CC BY-SA 4.0
  * was: CC BY 4.0
* closes #11 - Update License

### Hero logo 0.3.99.0

* Create
  * Hero.png
* closes #6 - Create HeroLogo.png

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* size reduction
  * <RSSDflameParticle02.mbm> --> <RSSDflameParticle02.png>
    * 193kb --> 27kb
  * <RSSDsmokeParticle02.mbm> --> <RSSDsmokeParticle02.png>
    * 257kb --> 19kb
* relocate part.cfg to Parts/
* closes #9 - Part Asset Updates

### Sound Asset Updates

* Convert
  * from `wav` to `ogg`
    * <RSBengine.wav> --> <RSBengine.ogg>
      * 518kb --> 69kb
    * <RSBengine2.wav> --> <RSBengine2.ogg>
      * 1.531mb --> 98kb
* 2.43mb --> 210kb
* closes #46 - Sound Asset Updates

### Thumbnails

* Create
  * @thumbs/
  * add thumbnails
* closes #47 - Create Thumbs

### ghostparts

* Create
  * [ghostparts.cfg]
  * this patch which will go away
* closes #48 - ghostparts

### Parts 0.3.99.0

* Update file names
  * <RSSDtankStage1.cfg> --> <sea-tankStage1.cfg>
  * <RSSDtankStage2.cfg> --> <sea-tankStage2.cfg>
  * <RSSDtankStage3.cfg> --> <sea-tankStage3.cfg>
  * <RSSDengineStage1.cfg> --> <sea-engineStage1.cfg>
  * <RSSDengineStage2.cfg> --> <sea-engineStage2.cfg>
  * <RSSDengineTVC.cfg> --> <sea-engineTVC.cfg>
  * <RSSDfairing23m.cfg> --> <sea-fairing23m.cfg>
  * <RSSDtankBallast.cfg> --> <sea-tankBallast.cfg>
* lint

### docs/

* Update
  * <SeaDragon.version>
    * remove
    * [KSP_VERSION_MAX]
* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartsCatalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #5 - Create GitHub Pages

### Compatibility 0.3.99.0

* rename Patches/ --> Compatibility/

### Config 0.3.99.0

* Resources
* <Category.cfg> v1.4.0.0
  * update links and flavor text

### Status 0.3.99.0

* Issues
  * closes #1 - SeaDragon (SEA) 0.3.99.0-adoption `<Thank you NecroBones>` edition
  * closes #2 - 0.3.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 0.3.99.0 Create Documentation
  * closes #4 - 0.3.99.0 Create Social Media Presence
  * closes #50 - [Bug 🐞]:
  * closes #49 - [Bug 🐞]: Fairings and tweakscale

---

## Version 0.3.4.0-release - `<Archival>` edition

* 12 Jul 2016
* Released for Kerbal Space Program 1.9.1
* Final release by original author

* Tweak
* Slightly increased heat tolerance of first stage parts.

### Status 0.3.4.0

* Issues
  * closes #37 - 0.3.4.0-release
  * closes #7 - Archival Releases

---

## Version 0.3.3.0-release - `<Archival>` edition

* 11 Jun 2016
* Released for Kerbal Space Program 1.1.3

* Minor hotfix
* Corrected staging problems in sample rockets.

### Status 0.3.3.0

* Issues
  * closes #36 - 0.3.3.0-release
  * updates #7 - Archival Releases

---

## Version 0.3.2.0-release - `<Archival>` edition

* 22 Apr 2016
* Released for Kerbal Space Program 1.1.2

* Tweaks
* Added collider setting for procedural fairing base.
* Adjusted tech node to play more nicely with Real Scale Boosters.

### Status 0.3.2.0

* Issues
  * closes #35 - 0.3.2.0-release
  * updates #7 - Archival Releases

---

## Version 0.3.1.0-release - `<Archival>` edition

* 03 Apr 2016
* Released for Kerbal Space Program 1.1.0

* KSP 1.1 Hotfix
* Sample rockets were locking up KSP 1.1 when sending to the pad/runway. Updated for 1.1, but are no longer compatible with 1.0.5.
* Sample rockets saved with fairing settings to use maximum ejection force, and 4-way clamshells.

### Status 0.3.1.0

* Issues
  * closes #34 - 0.3.1.0-release
  * updates #7 - Archival Releases

---

## Version 0.3.0.0-release - `<Archival>` edition

* 02 Apr 2016
* Released for Kerbal Space Program 1.1.0

* The Sea-Recovery Update
* Increased crash tolerance of first stage engine and tank to 150 m/s to support oceanic crash-landing recovery.
* Removed stack attachment node from end of skirt extension on second stage tank, and instead added it to second stage engine.
* Added inflatable "recovery flare" to the first stage engine, and updated sample rockets to put it on action group 2.

### Status 0.3.0.0

* Issues
  * closes #33 - 0.3.0.0-release
  * updates #7 - Archival Releases

---

## Version 0.2.0.0-release - `<Archival>` edition

* 28 Mar 2016
* Released for Kerbal Space Program 1.1.0

* The Sea-Launch Update
* Increased crash tolerance considerably on all parts, to allow bouncing around in the water.
* Added attachment node at bottom of first stage engine to allow attaching the ballast tank. 
* Extended first stage tank's lower skirt, and removed extraneous attachment node corresponding to it.
* Shortened first stage engine length (and updated sample rocket accordingly), after discovering miscalculation.
* Reworked colliders for first and second stage main engines, and first stage tank.
* Added ballast tank for sea launches.
* Added SPH sample rocket with ballast tank. 
* Updated VAB sample rocket to ignite the verniers at launch in the staging.
* Added an animated bell extension for the second stage engine, and updated sample rockets to use it (action group 1).
* Added custom smoke trail for first stage engine (known issue: runs regardless of air pressure).
* Removed smoke trails from upper-stage engine + verniers (hydrogen burns cleanly).

### Status 0.2.0.0

* Issues
  * closes #32 - 0.2.0.0-release
  * updates #7 - Archival Releases

---

## Version 0.1.0.0-release - `<Archival>` edition

* 25 Mar 2016
* Released for Kerbal Space Program 1.0.5

* First test release
* Mostly complete. Using stock procedural fairing system. No ballast tanks.
* Known issue: Fairing "confetti" is rather deadly.
* Known issue: Steering authority in upper stage is weak. Already artificially inflated though! (should be worse!)

### Status 0.1.0.0

* Issues
  * closes #31 - 0.1.0.0-release
  * updates #7 - Archival Releases

---
