WEEK 1

les 1.2 array en list
![opdracht 1 1 p2](https://github.com/user-attachments/assets/32ef2d9e-392c-4f8a-91c5-7ff1743722f4)





    void Update()
    {
        if (Input.GetKeyDown(KeyCode.Backspace)) PrintRandomItem();
        if (Input.GetKeyDown(KeyCode.Escape)) PrintAllItems();
    }
    private void PrintRandomItem()
    {
        int RandomItem = Random.Range(0, bosses.Length);
        Debug.Log(bosses[RandomItem]);

    }
    private void PrintAllItems()
    {
        for (int i = 0; i < bosses.Length; i++)
        {
            Debug.Log($"[{i}] {bosses[i]}");
        }

    }







----------------------------------------------------------------------------------------------
les 1.1 project
Titel (werktitel)

orb destroyer

Genre

Physics-based arcade puzzelgame.

Beschrijving

de speler schiet een balletje dat andere ballentjes raakt. aan de hand van welke kleur bal de speler krijgt kan de speler die zelfde kleur bal vernietigen door het te schieten op dezelfde kleur.

Gameplaykern

Bal: het balletje van de speler is een random kleur. afhangend van de  kleur van de ball kan de speler dezelfde kleur balletjes in het spel vernietigen.
Targets of bumps: wat raakt de bal.
Score: als de speler balletjes vernietigd krijgt ie punten. afhangend van de hoeveelheid ballen word ook de hoeveelheid punten bepaald. 1 balletje = 2 punten.
Doel: het behalen van een aantal bepaalde punten.

Stijl en sfeer

Korte omschrijving van thema, kleuren en geluid.
de kleuren van de balletjes zijn allemaal random. voor  het geluid maken de balletjes een geluid als ze vernietigd worden.

Structuur van het level

Bovenaan: schietplek.
Midden: veld met targets.
Onderaan: opvang of doelgebied voor het einde van de beurt.
links: schema met punten.

LEVELSCHETS
<img width="1512" height="982" alt="Scherm­afbeelding 2025-11-21 om 12 44 01" src="https://github.com/user-attachments/assets/f1660c32-4ad0-4cc5-ab55-1511b98a6264" />




REFLECTIE - WEEK 1

Wat heb je deze week gemaakt? ik heb deze week een random item system gemaakt en begonnen aan de schets en stappenplan voor het project.
Hoe heb je dit aangepakt? door alles optijd aftemaken en in de les te maken.
Waar liep je tegenaan en hoe heb je dat opgelost of wat heb je nodig? nergens voor nu. alles ging goed, behalve dat ik een klein probleempje met unity had voor het random item system.
Welke theorie of Unity-onderdelen heb je geleerd of toegepast? arrays.


---------------------------------------------------------------
WEEK 2

les 2.1 ![Schermopname2025-12-05om12 03 54-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/f44e71ea-39a7-45fc-b96b-76e7dc2bde39)

Script.aim:[Aim.cs](https://github.com/user-attachments/files/23960708/Aim.cs)



script.shoot:[Shoot.cs](https://github.com/user-attachments/files/23960702/Shoot.cs)


Les 2.2 ![Schermopname2025-12-09om12 54 31-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/fd80a48f-dcf5-40e2-897c-4d2527127f41)

script.shoot+krachtlijn:[Shoot.cs](https://github.com/user-attachments/files/24054455/Shoot.cs)

Wat heb je deze week gemaakt: ik heb een canon gemaakt die balletjes afvuurt, en een krachtlijn.
Hoe heb je dit aangepakt: door een empty object te maken en prefabs. en mee te doen met de uitleg.
Waar liep je tegenaan en hoe heb je dat opgelost of wat heb je nodig: het maken van de canon ging niet helemaal goed. ik heb dit opgelost door de foto op de goede manier in mijn unity te zetten.
Welke theorie of Unity-onderdelen heb je geleerd of toegepast (AddForce, Rigidbody, Collider, OnCollisionEnter): ik heb prefabs toegepast en ik heb empty objects gebruikt wat ik nooit eerder had gebruikt.


l
