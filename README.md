# Khôra CTF
Container capture the flag activity.

# Table Of Contents
- [Overview](#overview)
- [Run](#run)
- [Name](#name)

# Overview
This was my final project for UMass CS 590A systems test and defense. It is a container based capture the flag activity. It aims to demonstrate how familiar security analysis techniques can be used on a container production environment. Docker Compose is used to emulate said container production environment.

The CTF simulates a traditional client engagement with a fake company named "ACME Company". A letter of engagement is provided, and the rest is up to you. The CTF wiki does however provide full guides, including solutions, for each flag. A `workbench` container is also provided with all the tools you will need to complete this CTF.

# Run
The entire CTF is provided as a Docker Compose setup. To run it:

```
docker-compose up -d --build
```

Then navigate to the CTF wiki on [127.0.0.1:1111](http://127.0.0.1:1111). This will explain everything and get you started.

# Name
Every technology project needs a "cool" name, usually something greek or mythology related. Khôra was a term used by the ancient Greek philospher Plato to describe a type of seperated space. Containers are also a sort of seperated space.
