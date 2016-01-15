<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<title>NPC_EE</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link rel="stylesheet" href="style/g3readme_cam.css" type="text/css" />
<link href="style/g3icon.ico" rel="icon" type="image/bmp" />
</head>
<body>
<h1>NPCs Enhanced for Everyone! (a.k.a. NPC_EE)</h1>
<div class="section">
  <p><strong>Author:</strong> <a href="http://forums.gibberlings3.net/index.php?showuser=6306">Duns Scotus, the SubtleDoctor</a><br />
</p>
  <p><strong> Version 2.0 </strong><br />
    <strong> Languages:</strong> English<br />
    <strong>Platforms: </strong>Windows, Mac OS X</p>
</div>
<h2>Overview</h2>
<div class="section">
  <p>This is intended to be a successor to the fantastic "Level 1 NPCs" mod.  L1NPCs was never updated for the EE games, and its author is no longer active, and it is an incredible, complicated piece of work that is difficult for someone else to update.  So I made this.  It's not as complete as L1NPCs, and my techniques are not as sophisticated.  But it aims to reach a similar result: add replayability by allowing players to easily change the class and kit of various NPCs, thus creating different parties with different tactics, for different playthroughs</p>
  <p>In application, this kind of pales in comparison to Level 1 NPCs, but it should at least let you spice things up a bit.  And it has one real advantage: you can change the kits of every NPC in every playthrough *in-game,* without going back out to Weidu to uninstall/reinstall a mod.</p>
  <p>The way this works is, during installation you can change the *class* of various NPCs.  Some only have one alternate class, some have more than one, and some don't have any option to change.  This is based on the in-game lore; e.g. Xan is a spellcaster with a Moonblade; that could work as a mage, but also as a fighter/mage or a bard or a sorcerer.  Conversely, Jaheira is a druid, she talks all the time about being a druid, and so there is no option to make her anything other than a druid.</p>
  <p>Once you have decided which <i>class</i> to give each NPC, you have the option to give all of them (even those you didn't change, and including mod NPCs) a special innate ability that you can use in-game to add or change their <i>kit</i>.  This is a single-use ability, so choose wisely!  This ability will trigger a dialogue that gives you the option to adopt any kit for that class... this includes any and all mod kits that you may have installed.  Turn Mazzy into a Dwarven Defender!  Make Keldorn a Blackguard!  Make Minsc a fighter in the Weidu install, and then use this ability to make him a Barbarian!  (Barbarian is actually, technically, a fighter kit.)</p>
  <p>The reason I split up the class changes and kit changes is simple: Weidu installation code is static, and there are only a certain number of class in the game; no mod can add new ones.  On the other hand, you can install <i>hundreds</i> of kits into the game; this mod automatically detects <i>all</i> of them and makes <i>all</i> of them available.  You can't do that in the Weidu installer, you have to do it in-game.  Yes, it breaks the 4th wall very slightly, but it is the only way to achieve that kind of flexibility.  It means that this mod can automatically adapt to and work with every other kit mod you can possibly install.</p>
</div>
<h2>Installation</h2>
<div class="section">
  <p><strong>Windows:</strong><br />
    The mod archive should be extracted into your game folder from the archive (or just unzipped and then copied there). If properly extracted, you should have an "NPC_EE" folder and "setup-npc_ee.exe" in your BG2 folder. To install, simply double-click "setup-npc_ee.exe" and follow the instructions on screen.</p>
  <p>Run setup-npc_ee.exe again as needed to reinstall, uninstall or otherwise change components.</p>
  <p><strong>Mac OS X:</strong><br />
    This mod is packaged and installed with WeiDU. To install, simply extract the contents of the mod into your game folder. If properly extracted, you should have a folder called "NPC_EE" and a file called "weidu," and the "Mac WeiDU Launcher" in your BG2 directory. To install, simply double-click the WeiDU Launcher, choose NPC_EE from the list, and follow the instructions on screen.</p>
</div>
<h2>Compatibility</h2>
<div class="section">
  <p>This is designed to work with any Infinity Engine game on a variant of the BG2 engine that someone might purchase and play today, in 2015. Of course, there are no NPCs in IWDEE, and v1 only includes options for the BG1 NPCs. So as of v1, this is really for TuTu, BGT, and BG:EE.</p>
  <p><strong>This mod should be LAST.</strong> I know a lot of mods say that, but this one really should be installed last. I would install this AFTER Generalized Biffing, so NPC_EE can be easily uninstalled and reinstalled to change NPCs for new playthroughs.</p>
</div>
<h2>Contents</h2>
<div class="section">
  <h4 class="subheader">Component 100: choose a new class for Imoen</h4>
  <div class="section">
    <p>Make Imoen a mage-thief, or a bard</p>
  </div>
  <h4 class="subheader">Component 120: choose a new class for Jaheira</h4>
  <div class="section">
    <p>Make Jaheira a single-class druid</p>
  </div>
  <h4 class="subheader">Component 140: choose a new class for Khalid</h4>
  <div class="section">
    <p>Make Khalid a ranger/cleric, or a ranger></p>
  </div>
  <h4 class="subheader">Component 160: choose a new class for Minsc</h4>
  <div class="section">
    <p>Make Minsc a fighter</p>
  </div>
  <h4 class="subheader">Component 180: choose a new class for Dynaheir</h4>
  <div class="section">
    <p>Make Dynaheir a sorcerer</p>
  </div>
  <h4 class="subheader">Component 220: choose a new class for Coran</h4>
  <div class="section">
    <p>Make Coran a single-class thief, or a ranger, or a bard</p>
  </div>
  <h4 class="subheader">Component 240: choose a new class for Branwen</h4>
  <div class="section">
    <p>Make Branwen a fighter/cleric (multiclass)<br />
    <i>(If the Gloryblood of Tempus kit is installed, making Branwen a fighter/cleric will also give her that kit.)</i></p>
  </div>
  <h4 class="subheader">Component 320: choose a new class for Montaron</h4>
  <div class="section">
    <p>Make Montaron a single-class thief</p>
  </div>
  <h4 class="subheader">Component 460: choose a new class for Alora</h4>
  <div class="section">
    <p>Make Alora a cleric/thief<br />
    <i>(If the Misadventurer of Brandobaris kit is installed, making Alora a cleric/thief will also give her that kit.)</i></p>
  </div>
  <h4 class="subheader">Component 480: choose a new class for Xan</h4>
  <div class="section">
    <p>Make Xan a bard, or a fighter/mage, or a sorcerer</p>
  </div>
  <h4 class="subheader">Component 580: choose a new class for Viconia</h4>
  <div class="section">
    <p>Make Viconia a cleric/thief</p>
  </div>
  <h4 class="subheader">Component 620: choose a new class for Neera</h4>
  <div class="section">
    <p>Make Neera a sorcerer (still subject to wild magic)</p>
  </div>
  <h4 class="subheader">Component 680: choose a new class for Yoshimo</h4>
  <div class="section">
    <p>Make Yoshimo a fighter/thief</p>
  </div>
  <h4 class="subheader">Component 700: choose a new class for Valygar</h4>
  <div class="section">
    <p>Make Valygar a fighter/thief</p>
  </div>
  <h4 class="subheader">Component 720: choose a new class for Nalia</h4>
  <div class="section">
    <p>Make Nalia a bard, or a cleric/mage, or a sorcerer</p>
  </div>
  <h4 class="subheader">Component 760: choose a new class for Mazzy</h4>
  <div class="section">
    <p>Make Mazzy a fighter/cleric, or a paladin<br />
    <i>(If the Hearthguard of Arvoreen kit is installed, making Mazzy a fighter/cleric will also give her that kit.)</i></p>
  </div>
  <h4 class="subheader">Component 2000: NPC kit choices</h4>
  <div class="section">
    <p>As described above, this will add an innate ability to every single-class NPC allowing them to take a kit - or, if they already have a kit, to switch to a new one.</p>
    <p>If you've read this far, I might as well tell you about a little experiment: I've added one kit option to a class in which is doesn't belong: any sorcerer NPC will be able to become a "Wild Sorcerer" - which is just a sorcerer with the Wild Mage wizard kit.  This will cause a chance of wild surges and randomly adjust their caster level.  I don't know if NRD or Chaos Shield will be available; honestly, I haven't tested this one bit, except to make sure the change actually happens.  Why would anyone do this?  I have no idea.  But, it seems like a perfect option for Neera, doesn't it?  ;)</p>
  </div>
  <h4 class="subheader">Component 3000: multiclass kit choices</h4>
  <div class="section">
    <p>This will give the kit-choice innate ability to multiclass NPCs.  They can only choose kits in one of their classes.  The order of priorities is this: 1) rangers; 2) clerics; 3) fighters; 4) druids' 5) thieves; 6) mages. So a ranger/cleric is presumed to worship a nature deity, and can choose a ranger kit; but any other multiclass cleric will choose a deity, and cannot have a kit from the other class.  A fighter/thief can be a kensai/thief or a barbarian/thief (yes!) but not a fighter/swashbuckler.  And you can be an assassin/mage or swashbuckler/mage, but not a thief/illusionist (unless you're a gnome).  Needless to say this is way outside the basic game rules, and you only have yourself to blame if you abuse this and render the game stupidly easy.</p>
  </div>
</div>
<h2>Contact Information</h2>
<div class="section">
  <p>This mod was created by SubtleDoctor. You can visit <a href="http://forums.gibberlings3.net/index.php">The
    Gibberlings Three</a> for information on this and many other fine mods.</p>
</div>
<h2>Thanks and Acknowledgements</h2>
<div class="section">
  <p>Huge thanks in particular to Smeagolheart, Crevsdaak, kjeron, Camdawg, Mike1072, kreso, and The Imp for advice and help with using Weidu.  And special thanks to Grammarsalad, without whom I never could have made the kit-choice-by-dialogue system in v2.</p>
  <p>Thanks to the still active and vibrant Infinity Engine modding community. </p>
  <p><strong>Tools Used in Creation</strong><br />
    <a href="http://www.weidu.org/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a> by
    Wes Weimer, and then the bigg and then Wisp<br />
    <a href="http://www.idi.ntnu.no/~joh/ni/">Near Infinity</a> by Jon Olav Hauglid, and then Argent77 and Astrobryguy<br />
    <a href="http://iesdp.gibberlings3.net/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a> maintained by igi</p>
</div>
<h2>Credits and Copyright Information</h2>
<div class="section">
  <p>Copyright 2014-2016. If you want to use or adapt any part of this mod in another mod or similar endeavor, please try to contact me at forums.gibberlings3.net or forum.baldursgate.com to discuss it.  As a general rule, I have no problem with that as long as you credit the source of the work.  If you cannot get in touch with me, assume that you have my permission to use any of this code for any project that is non-commercial, offered for free, and intended for the greater enjoyment of players of Infinity Engine games.  If you do so, please credit me, and mention how awesome I am in a comment in the code, or something like that.  You may NOT use this code for any profit-making or commercial venture, without express permission from me.</p>
</div>
<h2>Version History</h2>
<div class="section">
  <p><strong>Version 2.0 - January 2016</strong></p>
  <ul>
    <li>Total revamp, now class changes are in Weidu and kit changes are via dialogue.</li>
  </ul>
  <p><strong>Version 1.2 - October 2015</strong></p>
  <ul>
    <li>Fixes for various NPCs</li>
  </ul>
  <p><strong>Version 1.1 - September 2015</strong></p>
  <ul>
    <li>Added BG2 NPCs</li>
  </ul>
  <p><strong>Version 1.0 - August 2015</strong></p>
  <ul>
    <li>First version, transferred over from Scales of Balance v3.2</li>
  </ul>
</div>
</body>
</html>