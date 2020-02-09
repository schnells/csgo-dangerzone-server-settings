# csgo-dangerzone-server-settings

rcon changelevel dz_jungle

rcon game_type 6
rcon game_mode 0

rcon exec gamemode_competitive

rcon game_type 6; game_mode 0; changelevel dz_blacksite; sv_dz_team_count 2; sv_dz_jointeam_allowed 1; sv_dz_autojointeam 0; sv_dz_player_spawn_armor 1

rcon spec_allow_roaming 1
rcon tv_enable 1

 sv_dz_jointeam_allowed.
 
 rcon mp_warmup_end 
 
rcon mp_warmup_end
 
 
 [ COMMUNITY SERVERS ]
– Added a setting “sv_prime_accounts_only”. When enabled, only prime accounts can connect to the game server.
– Added console commands to support Danger Zone squads:
— sv_dz_team_count N : set DZ team size to N players per squad.
— sv_dz_jointeam_allowed 1: enable users to choose their own squad during warmup via dz_jointeam.
— sv_dz_autojointeam 0: disable players from automatically being assigned a squad when they join the server.
— dz_clearteams – remove players from all squads.
— dz_shuffle_teams – shuffle all players onto random squads.
— dz_jointeam N : Join squad #N (0 = none, valid squads range from 1 to 9).
— dz_jointeam N : Server admins only – assign a player to a particular squad. Doesn’t require sv_dz_jointeam_allowed.
– dz_jointeam only works during warmup. Use dz_clearteams / sv_dz_autojointeam 0 with care — all players must be assigned a valid squad when the game starts.


LinuxGSM/lgsm/config-default/config-lgsm/csgoserver/_default.cfg

https://webhostgb.com/billing/index.php/knowledgebase/4076/How-to-change-the-gamemode-of-the-csgo-server.html
