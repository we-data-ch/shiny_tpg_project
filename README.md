<img src="https://wedata.ch/images/me.png" alt="wedata logo" height="100"/><img src="https://github.com/user-attachments/assets/15988c7a-28ea-44a7-a617-c096a982c695" alt="x" height="90"/><img src="https://s3-eu-central-1.amazonaws.com/aws-ec2-eu-central-1-opendatasoft-staticfileset/tpg/logo?tstamp=16667914182042198" alt="tpg logo" height="100"/>

# WeData X TPG Shiny Project

## WeData Goals

1. Create a standalone shiny app using TPG (Transports Publics Genevois) datasets which will require many skills from data analysis to web development.

2. Apply conventional team knowledge: version/package control, branches, githubaction, clean-code, documentation, division-of-work, etc.

## Data Dictionary

`20241002_arrets.csv` : [Stops](https://opendata.tpg.ch/explore/dataset/arrets/information/?disjunctive.arretcodelong&disjunctive.nomarret&disjunctive.commune&disjunctive.pays&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImFycmV0cyIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuYXJyZXRjb2RlbG9uZyI6dHJ1ZSwiZGlzanVuY3RpdmUubm9tYXJyZXQiOnRydWUsImRpc2p1bmN0aXZlLmNvbW11bmUiOnRydWUsImRpc2p1bmN0aXZlLnBheXMiOnRydWV9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoiY29sdW1uIiwiZnVuYyI6IkFWRyIsInlBeGlzIjoiY29kZWRpZG9jIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzY2YzJhNSJ9XSwieEF4aXMiOiJhcnJldGNvZGVsb25nIiwibWF4cG9pbnRzIjo1MCwic29ydCI6IiJ9XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D)

`20241002_frequentation-journaliere-par-tranche-horaire.csv` : [Ridership per day per time slot](https://opendata.tpg.ch/explore/dataset/frequentation-journaliere-par-tranche-horaire/information/?disjunctive.jour_semaine&disjunctive.horaire_type&disjunctive.indice_semaine&disjunctive.horaire_tranche_stop_theo&sort=-date&dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImZyZXF1ZW50YXRpb24tam91cm5hbGllcmUtcGFyLXRyYW5jaGUtaG9yYWlyZSIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuam91cl9zZW1haW5lIjp0cnVlLCJkaXNqdW5jdGl2ZS5ob3JhaXJlX3R5cGUiOnRydWUsImRpc2p1bmN0aXZlLmluZGljZV9zZW1haW5lIjp0cnVlLCJkaXNqdW5jdGl2ZS5ob3JhaXJlX3RyYW5jaGVfc3RvcF90aGVvIjp0cnVlLCJzb3J0IjoiLWRhdGUifX0sImNoYXJ0cyI6W3siYWxpZ25Nb250aCI6dHJ1ZSwidHlwZSI6ImxpbmUiLCJmdW5jIjoiQVZHIiwieUF4aXMiOiJpbmRpY2Vfam91cl9zZW1haW5lIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzY2YzJhNSJ9XSwieEF4aXMiOiJkYXRlIiwibWF4cG9pbnRzIjoiIiwidGltZXNjYWxlIjoieWVhciIsInNvcnQiOiIifV0sImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9)

`20241002_montees-mensuelles-par-arret-par-ligne.csv` : [Ridership per month per stop per line](https://opendata.tpg.ch/explore/dataset/montees-mensuelles-par-arret-par-ligne/information/?disjunctive.ligne&disjunctive.ligne_type_act&disjunctive.arret&disjunctive.arret_code_long&sort=-mois)
