# Nobody-s-SWVR-MMO-mod
This is a full SWVR MMO mod with quests, XP, hunger, and jedi/sith affinity. Its still very much in beta some things wont work. its designed for use with VRChat, Blade and Sorcery, and contractors. It connects the three games with questlines and you actuall need to eat now to keep your hunger bar full. Enjoy and read the readme for more info

**IMPORTANT** the "reset progress button doesnt currently work, if you wish to reset progress open f12 DevTools and type this  -   
js
CopyEdit
// Reset values
localStorage.removeItem("swvrSave");
xp = 0;
level = 1;
affinity = "Neutral";
document.getElementById("level").innerText = "1";
document.getElementById("xpText").innerText = "0 / 100 XP";
document.getElementById("xpFill").style.width = "0%";
document.getElementById("affinityText").innerText = "Neutral";
document.getElementById("codexEntries").innerHTML = "";

// Update UI and save
updateAffinityBar();
updateCodenameDisplay();
saveProgress(); 

**ALSO** this version may have bugs, report any to my email- Haydenvic2001@gmail.com

*Known bugs* 
some quests that should award sith affinity award jedi affinity.
reset progress button doesnt work currently.
