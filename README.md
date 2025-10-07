# DataBasesProdject
A database archiving project. The project links football-related entities (football clubs, competitions, matches, players, events, etc.)

Requirements
A football competition, such as the Premier League or the Champions League, must be stored in
the database with attributes such as its name, the country (or countries) in which it is organized
and its type (e.g., national league, national cup, international competition). Each competition is
divided into seasons (e.g., 2024/2025), and every season must include a start date and an end
date.

Each football club that competes in a season must also be recorded. A club is described by its
name, the country it belongs to, and the year it was founded. It should be possible to find out
which titles a club won and in which seasons. Clubs are managed by coaches, referred to as
managers in the database. The system must not only record which manager currently leads a
club but also keep a complete historical record of all past managers, including their start and
end dates of employment.

Players are central to the system. For each player, the database must store their name, date of
birth, physical attributes such as height and weight, and their current market value. Since players
frequently change clubs during their careers, the system must also record transfers. A transfer
involves a player moving from one club to another on a given date, with a transfer fee and a
contract length in years. The system must allow the reconstruction of a player’s full transfer
history and determine their current club based on the most recent transfer.
Matches are at the heart of football statistics. A match belongs to a specific season and always
involves two clubs: the home club and the away club. Matches must include attributes such as
the matchday number (e.g., round 6 of the Portuguese League), the date of the match, and the
attendance (number of spectators).

For each match, the system must also store the lineups of both clubs. A lineup connects a player
to a specific match and specifies the position the player played (e.g., center midfielder, striker),
and whether the player was a starter or a substitute.

During a match, many actions occur. The system must record every action with details about the
match in which it occurred, the player who performed it, the minutes and seconds, and the type
of action. Examples of action types include (but not limited to) goals, shots, passes, fouls, and
cards. In addition to actions, the system must store/calculate match statistics for each player,
2such as the number of minutes played, passes completed, shots on target, and goals scored. The
final result of a match could (and should) be obtainable using the goals stored in actions.
This football statistics database must therefore integrate information about competitions,
seasons, clubs, managers, players, transfers, matches, lineups, actions, and player statistics.
With such a structure, it will be possible to answer important questions such as which player
scored the most goals in a season, which club has spent the most on transfers in the past five
years, or which manager has had the longest tenure at a single club.
