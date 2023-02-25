# Eastside Hockey Manager (EHM) League Structures & Schedules
![GitHub last commit](https://img.shields.io/github/last-commit/archibalduk/EHM-League-Structures?style=flat-square) ![GitHub contributors](https://img.shields.io/github/contributors/archibalduk/EHM-League-Structures?style=flat-square) ![GitHub](https://img.shields.io/github/license/archibalduk/EHM-League-Structures?style=flat-square)


## About

A collection of league structures and schedule templates for Eastside Hockey Manager (EHM).


## Usage

Simply download your chosen structure or schedule from the relevant folder above. Real life structures are contained individual sub-folders. There is also an *--- Assorted Schedule Templates ---* folder which contains an assortment of generic schedule templates. 

The folders and the schedule template spreadsheets use the following naming convention:

```
[total_teams] Teams - [teams_per_division] ([total_teams]) - [games_played] GP

- OR -

[league_name] [season] - [teams_per_division] ([total_teams]) - [games_played] GP
```

Some examples:

- NHL 2023-23 season with four divisions (three of which have eight teams and one of which has seven teams) (31 teams in total) with a total of 82 games played in the regular season:
```
NHL 2022-23 - 8_8_8_7 - 82 GP
```

- Generic 30 team league with five divisions of six teams (30 teams in total) with a total of 82 games played in the regular season:
```
30 Teams - 6_6_6_6_6 - 82 GP
```

- Generic 30 team league with no divisions (30 teams in total) with a total of 82 games played in the regular season:
```
30 Teams - 30 - 82 GP
```

## Installation

Each folder contains one or both of the following:

- An .ehm file containing the full league structure and schedule data in a single file; and/or
- One or more spreadsheets containing the schedule templates and/or schedule dates.

The .ehm file is useful if you wish to import the full league structure (including schedules) into an EHM database. Whilst all structures work fine in EHM, they might require further work to reflect the real life rules for that season (e.g. season-specific icing rules, etc). The .ehm files can be imported using the EHM Editor by archibalduk - https://www.ehmtheblueline.com/editor

The spreadsheets are useful if you just want the schedule for use with an existing league structure. These can be imported into an EHM database using the EHM Editor by archibalduk.

Spreadsheets within each league structure folder use the following naming convention:

```
  regular_season_[type] <- Regular season schedule
  conference_playoff_[type] <- Conference/division-level playoff rounds
  championship_playoff_[type] <- Championship playoff rounds (i.e. after the conference/division-level playoff rounds)
```
[type] will either be "template" to denote a schedule template or "dates" to denote schedule dates. A suffix of "_[alt]" denotes that the schedule file relates to an Olympic season (i.e. alternative schedule for an Olympic season).


## Authors

This repository is a compilation of structures and schedules created by:

- [@archibalduk](https://www.github.com/archibalduk)
- [@xECK29x](https://www.ehmtheblueline.com/forums/memberlist.php?mode=viewprofile&u=10633)


## License

[Creative Commons Zero v1.0 Universal](https://choosealicense.com/licenses/cc0-1.0/)