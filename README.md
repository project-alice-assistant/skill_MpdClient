# MpdClient
[![Continous Integration](https://gitlab.com/project-alice-assistant/skills/skill_MpdClient/badges/master/pipeline.svg)](https://gitlab.com/project-alice-assistant/skills/skill_MpdClient/pipelines/latest)

### Download
##### > WGET method
```bash
wget http://skills.projectalice.ch/MpdClient -O ~/ProjectAlice/system/skillInstallTickets/MpdClient.install
```

### Description
Control an MPD server

- Version: 0.0.22
- Author: glueckself
- Maintainers: maxbachmann
- Alice minimum Version: 1.0.0-a5
- Conditions:
  - en
  - de
- Pip requirements: python-mpd2
- System requirements: N/A

### Configuration
`mpdHost`:
 - type: `string`

`mpdPort`:
 - type: `int`

`mpdPassword`:
 - type: `string`
