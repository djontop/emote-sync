qb-adminmenu/client/client.lua 
```lua
-- add at line  27 (after weapon spawn)
local menu18 = MenuV:CreateMenu(false, "emote", menuLocation, 220, 20, 60, 'size-125', 'none', 'menuv', 'test18')
```
```lua
-- copy and paste emote list from provided lua added list after  line 28 or 29

local dance = {
    {name = "Cancel", id = "c"},
    {name = "Indian flag", id = "ctfredflag"},
    {name = "salute", id = "airforce04"},
    {name = "Dance", id = "dance"},
    {name = "Dance 2", id = "dance2"},
    {name = "dance 3", id = "dance3"},
    {name = "dance 4", id = "dance4"},
    {name = "dance 5", id = "dance5"},
    {name = "dance 6", id = "dance6"},
    {name = "dance 7", id = "dance7"},
    {name = "dance 8", id = "dance8"},
    {name = "dance 9", id = "dance9"},
    {name = "dance f", id = "dancef"},
    {name = "dance f 2", id = "dancef2"},
    {name = "Dance F3", id = "dancef3"},
    {name = "Dance F4", id = "dancef4"},
    {name = "Dance F5", id = "dancef5"},
    {name = "Dance F6", id = "dancef6"},
    {name = "Dance Club", id = "danceclub"},
    {name = "Dance Club 2", id = "danceclubb"},
    {name = "Dance Club 3", id = "danceclubc"},
    {name = "Dance Club 4", id = "danceclubd"},
    {name = "Dance Club 5", id = "danceclube"},
    {name = "Dance Club 6", id = "danceclubf"},
    {name = "Dance Club 7", id = "danceclubg"},
    {name = "Dance Club 8", id = "danceclubh"},
    {name = "Dance Club 9", id = "danceclubi"},
    {name = "Dance Club 10", id = "danceclubj"},
    {name = "Dance Club 11", id = "danceclubk"},
    {name = "Dance Club 12", id = "danceclubl"},
    {name = "Dance Club 13", id = "danceclubm"},
    {name = "Dance Club 14", id = "danceclubn"},
    {name = "Dance Club 15", id = "danceclubo"},
    {name = "Dance Club 16", id = "danceclubp"},
    {name = "Dance Drink (Beer)", id = "dancedrink"},
    {name = "Dance Drink 2 (Wine)ce F4", id = "dancedrink2"},
    {name = "Dance Drink 3 (Whiskey)", id = "dancedrink3"},
    {name = "Dance Drink 4 (Whiskey)", id = "dancedrink4"},
    {name = "Dance Drink 5 (Wine)", id = "dancedrink5"},
    {name = "Dance Drink 6 (Beer)", id = "dancedrink6"},
    {name = "Dance Drink 7 (Wine)", id = "dancedrink7"},
    {name = "Dance Drink 8 (Wine)", id = "dancedrink8"},
    {name = "Dance Slow 2", id = "danceslow2"},
    {name = "Dance Slow 3", id = "danceslow3"},
    {name = "Dance Slow 4", id = "danceslow4"},
    {name = "Dance Upper", id = "danceupper"},
    {name = "Dance Upper 2", id = "danceupper2"},
    {name = "Dance Shy", id = "danceshy"},
    {name = "Dance Shy 2", id = "danceshy2"},
    {name = "Dance Slow", id = "danceslow"},
    {name = "Dance Silly", id = "dancesilly"},
    {name = "Dance Silly 2", id = "dancesilly2"},
    {name = "Dance Silly 3", id = "dancesilly3"},
    {name = "Dance Silly 4", id = "dancesilly4"},
    {name = "Dance Silly 5", id = "dancesilly5"},
    {name = "Dance Silly 6", id = "dancesilly6"},
    {name = "Dance Silly 7", id = "dancesilly7"},
    {name = "Dance Silly 8", id = "dancesilly8"},
    {name = "Dance Silly 9", id = "dancesilly9"},
    {name = "Dance old", id = "danceold"},
    {name = "Dance Glowsticks", id = "danceglowstick"},
    {name = "Dance Glowsticks 2", id = "danceglowstick2"},
    {name = "Dance Glowsticks 3", id = "danceglowstick3"},
    {name = "Dance Horse", id = "dancehorse"},
    {name = "Dance Horse 2", id = "dancehorse2"},
    {name = "Dance Horse 3", id = "dancehorse3"},
    {name = "Wave Dance", id = "dancewave"},
    {name = "Wave Dance 2", id = "dancewave02"},
    {name = "Wave Dance 3", id = "dancewave03"},
    {name = "Wave Dance 4", id = "dancewave04"},
    {name = "Wave Dance 5 - Tutankhamen", id = "dancewave05"},
    {name = "Wave Dance 6 - Tutankhamen 2", id = "dancewave06"},
    {name = "Wave Dance 7 - Snake Dance", id = "dancewave07"},
    {name = "Wave Dance 8 - Slide Dance", id = "dancewave08"},
    {name = "Wave Dance 9 - Slide Dance 2", id = "dancewave09"},
    {name = "Wave Dance 10 - Robot Dance", id = "dancewave10"},
    {name = "Wave Dance 11 - Locking Dance", id = "dancewave11"},
    {name = "Wave Dance 12 - Headspin", id = "dancewave12"},

    {name = "Wave Dance 13 - Flaire Dance", id = "dancewave13"},
    {name = "Wave Dance 14 - Female Crowd Dance", id = "dancewave14"},
    {name = "Wave Dance 15 - Uprock Dance", id = "dancewave15"},
    {name = "Dance - MJ Thriller", id = "dancethriller"},
    {name = "Wave Dance 7 - Snake Dance", id = "dancewave07"},
    {name = "Wave Dance 7 - Snake Dance", id = "dancewave07"},
    {name = "Dj", id = "dj"},
    {name = "Dj 1", id = "dj1"},
    {name = "Dj 2", id = "dj2"},
    {name = "Dj 3", id = "dj3"},
    {name = "Dj 4", id = "dj4"},
    {name = "Dj 5", id = "dj5"},
    {name = "Dj 6", id = "dj6"},
    {name = "Dj 7", id = "dj7"},
    {name = "Dj 8", id = "dj8"},
    {name = "Dj 9", id = "dj9"},
    {name = "Twerk", id = "twerk"},
    {name = "Lapdance", id = "lapdance"},
    {name = "Lapdance 2", id = "lapdance2"},
    {name = "Lapdance 3", id = "lapdance3"},
    {name = "Lapdance 4", id = "lapdance4"},
    {name = "Lapdance 5", id = "lapdance5"},
    {name = "Lapdance 6", id = "lapdance6"},
    {name = "Lapdance With", id = "lapdancewith"},
    {name = "Lapdance With2", id = "lapdancewith2"},
    {name = "Lapdance With3", id = "lapdancewith3"},
    {name = "Lap Chair", id = "lapchair"},
    {name = "Lap Chair2", id = "lapchair2"},
    {name = "Lap Chair3", id = "lapchair3"},
    {name = "Salso Roll", id = "salsa"},
    {name = "Dance Crank Dat", id = "dancecrankdat"},
    {name = "Dance Crank Dat 2", id = "dancecrankdat2"},
    {name = "Monkey Dance", id = "dancemonkey"},
    {name = "Monkey Dance 2", id = "dancemonkey2"},
    {name = "Monkey Dance 3", id = "dancemonkey3"},
    {name = "Boxing Dance Solo", id = "boxdance"},
    {name = "Hip Hop Dance", id = "dancehiphop"},
    {name = "Hip Hop Dance 2", id = "dancehiphop2"},
    {name = "Hip Hop Dance 3", id = "dancehiphop3"},
}

```
```lua
-- add at line 165 (after admin_options) 
local menu12_button7 = menu2:AddButton({
    icon = ':dancer:',
    label = "Dance Menu(Sync dance with all near by players)",
    value = menu18,
    description = "Open Dance Menu(It's Sync dance with all near by players)",
    
})
```
```lua
-- add at line 173 after 
menu12_button7:On('select', function(_)
    menu18:ClearItems()
    for k, v in pairs(dance) do
        menu18:AddButton({
            label = v.name,
            description = 'Set Dance ' .. v.name,
            select = function()
                setDance(v.id, v.name)
        end})
    end
end)

function setDance(did,dname)
    if did ~= nil then
        QBCore.Functions.Notify("Dance Set : "..dname, "info")
        TriggerServerEvent("qb-admin:server:setemote", did)
    else
        QBCore.Functions.Notify("Invalid Dance or emote", "error")
    end
end
```
```lua
-- add at bottom of rpemotes/client/Emote.lua
local danceflag = true
RegisterNetEvent('animations:client:PlayEmoteSync', function(args, coords)
  if LocalPlayer.state.isLoggedIn then
    if not PlayerData.metadata['inlaststand'] and not PlayerData.metadata['isdead'] then
      local plyCoords = GetEntityCoords(PlayerPedId(), 0)
      local distance = #(plyCoords - vector3(coords.x, coords.y, coords.z))
      if distance < 50 and danceflag then
        EmoteCommandStart(source, args)
      end
    end
  end
end)
```
