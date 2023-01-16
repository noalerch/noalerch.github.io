+++
title = "Lag"
weight = 6
+++

Lagen är som följer:

```C
#define NO_PLAYERS = 24

char **get_teams(char *players[])
{
    // code not tested, do not expect this to work
    char **teams = malloc((NO_PLAYERS / 2) * sizeof(char *)); 
    char *player = players[0];

    // precondition: 24 players
    for (int i = 0; i < NO_PLAYERS / 2; ++i)
    {
        assign_to_team(teams, players[i])
    }

    return teams;
}
```

![Logo](/images/logo.png)

