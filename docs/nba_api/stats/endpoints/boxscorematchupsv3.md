# BoxScoreMatchupsV3
##### [nba_apiv3/stats/endpoints/boxscorematchupsv3.py](https://github.com/swar/nba_api/blob/master/src/nba_api/stats/endpoints/boxscorematchupsv3.py)

##### Endpoint URL
>[https://stats.nba.com/stats/boxscorematchupsv3](https://stats.nba.com/stats/boxscorematchupsv3)

##### Valid URL
>[https://stats.nba.com/stats/boxscorematchupsv3?GameID=0021700807](https://stats.nba.com/stats/boxscorematchupsv3?GameID=0021700807)

## Parameters
| API Parameter Name                                                                                                  | Python Parameter Variable |  Pattern   | Required | Nullable |
|---------------------------------------------------------------------------------------------------------------------|---------------------------|:----------:|:--------:|:--------:|
| [_**GameID**_](https://github.com/shufinskiy/nba_apiv3/blob/master/docs/nba_api/stats/library/parameters.md#GameID) | game_id                   | `^\d{10}$` |   `Y`    |          | 

## Data Sets
#### PlayerStats `player_stats`
```text
["gameId", "teamId", "teamCity", "teamName", "teamTricode", "teamSlug", "personIdDef", "firstNameDef", "familyNameDef", "nameIDef", "playerSlugDef", "positionDef", "commentDef", "jerseyNumDef", "personIdOff", "firstNameOff", "familyNameOff", "nameIOff", "playerSlugOff", "jerseyNumOff", "matchupMinutes", "matchupMinutesSort", "partialPossessions", "percentageDefenderTotalTime", "percentageOffensiveTotalTime", "percentageTotalTimeBothOn", "switchesOn", "playerPoints", "teamPoints", "matchupAssists", "matchupPotentialAssists", "matchupTurnovers", "matchupBlocks", "matchupFieldGoalsMade", "matchupFieldGoalsAttempted", "matchupFieldGoalsPercentage", "matchupThreePointersMade", "matchupThreePointersAttempted", "matchupThreePointersPercentage", "helpBlocks", "helpFieldGoalsMade", "helpFieldGoalsAttempted", "helpFieldGoalsPercentage", "matchupFreeThrowsMade", "matchupFreeThrowsAttempted", "shootingFouls"]
```


## JSON
```json
{
    "data_sets": {
        "PlayerStats": [
            "gameId", 
            "teamId",
            "teamCity",
            "teamName",
            "teamTricode",
            "teamSlug",
            "personIdDef",
            "firstNameDef",
            "familyNameDef",
            "nameIDef",
            "playerSlugDef",
            "positionDef",
            "commentDef",
            "jerseyNumDef",
            "personIdOff",
            "firstNameOff",
            "familyNameOff",
            "nameIOff",
            "playerSlugOff",
            "jerseyNumOff",
            "matchupMinutes",
            "matchupMinutesSort",
            "partialPossessions",
            "percentageDefenderTotalTime",
            "percentageOffensiveTotalTime",
            "percentageTotalTimeBothOn",
            "switchesOn",
            "playerPoints",
            "teamPoints",
            "matchupAssists",
            "matchupPotentialAssists",
            "matchupTurnovers",
            "matchupBlocks",
            "matchupFieldGoalsMade",
            "matchupFieldGoalsAttempted",
            "matchupFieldGoalsPercentage",
            "matchupThreePointersMade",
            "matchupThreePointersAttempted",
            "matchupThreePointersPercentage",
            "helpBlocks",
            "helpFieldGoalsMade",
            "helpFieldGoalsAttempted",
            "helpFieldGoalsPercentage",
            "matchupFreeThrowsMade",
            "matchupFreeThrowsAttempted",
            "shootingFouls"
        ]
    },
    "endpoint": "BoxScoreMatchupsV3",
    "last_validated_date": "2023-09-14",
    "nullable_parameters": [],
    "parameter_patterns": {
        "GameID": "^\\d{10}$"
    },
    "parameters": [
        "GameID"
    ],
    "required_parameters": [
        "GameID"
    ],
    "status": "success"
}
```

Last validated 2023-09-14
