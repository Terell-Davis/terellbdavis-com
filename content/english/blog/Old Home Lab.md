---
title: Homelab - Is this overkill? Yeah probably, but I'm having fun.
description: Old 1 Post Blog Page
date: 2024-04-21T20:58:00.000Z
categories:
  - homelab
  - technology
image: images/tech/serverrack.jpg
draft: false
---
\[This is an edit of what was was on my previous blog site that is now archive, I wasn't happy how it was and want to change it up.]

# Is this overkill? Yeah probably, but I'm having fun.

This is was about a year and a half after getting into Linux.

There are two servers that form the backbone of my entire network. It all started with a single server which was an old Compaq computer that came from my grandmother. Later, I upgraded to a system I picked up from Micro Center for around \$200.

A benefit, working at a smaller Managed Service Provider (MSP), was I able to keep a lot of old tech that was either laying around the office or from business when there was any decomissioned (Yes I asked).

This is also how I manage to get my hands on the server rack as it was a comapnies first rack and been sitting in a warehouse for years nesting spiders. My boss was generous enough to bring it back to the office and from there I cleaned it up and spray painted it.

***

### Meet Demiurge (Full Tower)

Down the line I upgraded my gaming setup which left me with some extra parts, so why not build _another_ computer so I can lay the poor AMD Athlon to rest.

This server is the remians of my previous gaming machine minus the GPU, and now hosts the majority of my VMs and containers thanks to the extra power.

<ul>
    <li>CPU: 8 x Intel Core i7-9700K @ 3.60GHz</li>
    <li>RAM: 4x16GB DDR4 3200MHz (64GB Total)</li>
    <li>Storage: </li>
        <ul>
            <li>4x4TB WD Red Drives in Raid 10: For backups, projects, and general household data.</li>
            <li>2x500GB SSDs in Raid 1: Primarily for running VMs, benefiting from the speed of SSDs.</li>
        </ul>

</ul>

***

### Judgement (4U Rack Server)

(Yeah I swapped naming schemes by this point) </br>This is the hub of my data hording habits and recieved thanks to one of those benefits. </br>​

It serves primarily as a Plex/Jellyfin server but also anything else that likes to eat up space such as a game cache/server & local system backups.

<ul>
    <li>CPU: 16 x Intel Xeon CPU E5-2630 v3 @ 2.40GHz</li>
    <li>RAM: 5x8GB DDR 2400MHz (40GB Total)</li>
    <li>Storage:</li>
        <ul>
            <li>4x10TB WD Gold Drives in Raid 10: This is my largest storage setup for media, Plex server content, and large ISO files.</li>
            <li>2x500GB SSDs in Raid 1: Added for replication efforts, though still a work in progress.</li>
        </ul>

</ul>

***

### Current Containers & VMs

<ul>
    <li>Mumble Server: Temp Vocie chat incase of cloudflare outage... </li>
    <li>MagicMirror2 Server: Provides local access only, displaying system information and calendar. </li>
    <li>Pi-hole: The ads became too much. </li>
    <li>Home Assistant OS: Controls smart devices throughout my apartment. </li>
    <li>Steam Server: Game Server using steam cmd.. </li>
    <li>Windows Server 2022 (x2): Serves as the primary domain controller with a backup DC. </li>
</ul>

​
