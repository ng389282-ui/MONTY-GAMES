<?xml version="1.0" encoding="UTF-8"?>
<Game name="Shadow Hunters" type="Multiplayer">

    <Settings>
        <MaxPlayers>6</MaxPlayers>
        <MinPlayers>2</MinPlayers>
        <TimeLimit>900</TimeLimit> <!-- seconds (15 minutes) -->
    </Settings>

    <Maps>
        <Map id="1" name="Abandoned Hospital"/>
        <Map id="2" name="Underground Metro"/>
        <Map id="3" name="Haunted Forest"/>
        <Map id="4" name="City Mall"/>
        <Map id="5" name="School Building"/>
    </Maps>

    <Roles>
        <Role id="HUNTER">
            <Description>Find and capture the Shadows.</Description>
            <Abilities>
                <Ability name="NightVision"/>
                <Ability name="Tracker"/>
            </Abilities>
        </Role>
        <Role id="SHADOW">
            <Description>Hide among humans and escape through portals.</Description>
            <Abilities>
                <Ability name="Disguise"/>
                <Ability name="SpeedBoost"/>
            </Abilities>
        </Role>
    </Roles>

    <WinConditions>
        <Condition role="HUNTER">All Shadows captured</Condition>
        <Condition role="SHADOW">At least one Shadow escapes</Condition>
    </WinConditions>

</Game><img width="1024" height="1024" alt="1000033528" src="https://github.com/user-attachments/assets/b4473951-96a9-47a0-839f-5bb4da16eefa" />
