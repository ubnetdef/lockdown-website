+++
date = "2025-10-22"
title = "Rules"
+++

1. Code of Conduct  
    1.1. All participants (competitors, organizers, volunteers) are expected to behave
    professionally at all times throughout the duration of the competition. This means
    to treat others with dignity and respect, and to foster an open and welcoming
    environment for all involved. Anyone found to be violating this stipulation will be
    penalized at the discretion of the competition organizers.

    1.2. **All network traffic during the competition is being captured and logged.
    Do not enter any personal credentials unless you are comfortable with sharing it with the world.**

    1.3. All university and local/state/federal government rules apply and ultimately
    supersede the regulations listed

    1.4. No alcohol or substance use will be tolerated, including smoking (the University at
    Buffalo is a smoke-free campus).

    1.5. You are free to come and go from the competition room as you please so long as it is
    not for outside assistance regarding competition matters. What happens in the
    competition room stays in the competition room (until the event is over, then by all
    means talk about and review whatever you wish!)

2. Scoring  
    2.1. _Service Uptime_: **50%** of blue team scores will be determined by the uptime of 
    various services within their network and configuration of new services and system, via 
    inject request. ​Teams will all have access to a scoreboard, which will show which services 
    are currently “up” (meaning reachable and usable) and which are “down” (unreachable and/or 
    unusable). Scoring engine checks occur in a synchronous fashion – each service will be 
    checked once every 60 seconds. Misconfigurations and not following best practices will mostly 
    likely result in loss of point. This is determined based on Red Team gaining access.

    2.2. _Injects_: **50%** of blue team scores will be determined by the successful and quality 
    completion of the tasks they are given by the white team throughout the competition. 
    Completeness counts, as does quality. It is expected that any injects that are written will 
    be typed in a professional and report/documentation format. Anything you submit inject-wise 
    should be something that you would feel comfortable submitting to your boss at work.

3. Infrastructure  
    3.1. The University at Buffalo owns all infrastructure – this includes hardware, software,
    the hypervisor/VM’s, etc. Treat it with respect and take due care to not cause any
    damage outside the scope of the competition.

    3.2. You are not authorized to revert any VM's to a previous snapshot or template, or
    create your own snapshots or templates. Doing so will result in a significant white
    team penalty. You may purchase this service from the white team during the
    competition, however (more information on that will be provided). The white team
    purchase will inform you of any penalties to your budget at the time of the request.

    3.3. **All software used by blue teams in the competition must be free and open
    source (FOSS) and publicly available to anyone. No personal use or
    commercial trial software will be allowed.**

    3.4. There is to be no “pre-staging” of scripts or software prior to the start of the
    competition (i.e. creating a .zip archive and hiding it on Dropbox). All scripts and
    software must be publicly available and free for any competitor. The exceptions to
    this rule are scripts that are written during the competition inside of virtual
    machines and scripts written on paper.

    3.5. You may not touch another team’s infrastructure (either physical or virtual). Doing
    so will result in immediate disqualification for your team. If it isn’t your team’s –
    **don’t touch it**!

    3.6. There is no attacking in this competition, but certain injects may have you using
    tools such as nmap. You must only use these tools on _your own team’s network_. Any
    activity that could be construed as reconnaissance or attacking against another
    team, the University, or an outside entity will result in immediate disqualification
    for your team.

    3.7. You are allowed to collaborate with teams participating in the competition. Reason
    being, most industry professionals need to do this to be successful. Teams will still
    be individual scored even when a joint effort is made.

4. Reference Material  
    4.1. You will have access to Internet on your host machines during the competition to
    use for looking up reference material. You may only use free and publicly
    available resources (i.e. no paid support forums).

    4.2. On the subject of Internet on your host machines – you may not use the host
    machine Internet for anything unrelated to the competition. This means no
    Facebook, Reddit, Twitter, etc. (unless specifically allowed by the white team for the
    purpose of an inject).

    4.3. Any and all paper-based reference materials (cheat sheets, books, printed PDF’s,
    etc.) are allowed and encouraged. You may also write scripts beforehand and print
    them on paper to bring with you.

    4.4. No electronic media will be allowed in the competition, namely USB drives, external
    hard drives, CD’s/DVD’s/BD’s etc.
