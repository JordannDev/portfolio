---
layout: default
---

**Hi**, I'm Jordan. Welcome to my portfolio. I'm a self taught programmer with experience with:

- Laravel
- Docker
- Kubernetes
- *more below*

#### Contact

If you want to get in contact with me, send me an email @ admin@jordie.ml


# Progamming

| Language     | Experience (years)|
|:-------------|:------------------|
| Java         | 6+                |
| PHP          | 2+                |
| .NET         | 3+                |
| HTML & CSS   | 2+                |
| Lua          | -1                |
| C++          | 1                 |
| Go           | -1                |
| JavaScipt    | 1+                |

# SysAdmin

I have *some* SysAdmin experience. Most of my SysAdmin expeience comes from personal projects. 

## VATSIM Canada (Organization, *SysAdmin+Development*)

I joined VATSIM Canada (*VATCAN*) as a volunteer in late 2019, and am still currently working with them. My current role in VATCAN is to develop and maintain our infrastructure, and code base. Aswell as take on leadership responsibilities when required.

### Programming

*VATCAN*s codebase is almost entirely [Laravel](https://laravel.com) (a PHP framework). Our TeamSpeak & Discord Bots are both written in Java, and we have another project in the works which utilizies C#, and React (JavaScript Framework).

I wrote *VATCAN* a new website from scratch, starting in early 2020, and finishing by the first quarter of 2021. In November [Kolby Dunning](https://kolbyd.ca) joined to assist aswell. During November 2020, and the beginning of April of 2021, we collectively wrote *~50,000* lines of code. 

Our main website is a large Laravel project, which has brought on many insights on how we should optimize our website to increase performance, and make Laravel run a lot cleaner. Naturally, this also brought on a lot of new methods for keeping the code base clean, and maintainable. We both learned a lot about how to make sure we future-proof the codebase for future developers.

### Leadership Role

My role primarily is development, but I am also responsible for managing our Web Team, aswell as assisting the other Webmasters within our organization when required. I currently manage a small Web Team, those responsibilities include:

1. Assigning tasks / bugs to developers to fix
2. Hosting development meetings when required
3. Ensuring high level goals are met
4. Assigning priority to specific tasks to meet organization goals


### Kubernetes & Docker

*VATCAN*s applications are used in Docker containers, we have also recently deployed a Kubernetes cluster.

## VATSIM Sync (Personal, *Java*)

VATSIM Sync is a Discord bot that uses VATSIM's OAuth to connect Discord accounts, and VATSIM profiles. The Discord Bot then synchronizes ratings (rank) based on roles that are setup by the Discord Servers administrators. This bot has a user base of *~2500*. This bot was written in Java, and utilizing multi-threading, and caching to avoid rate-limiting, and efficiently assign roles.

## VATSIM Notify (Personal, *Java*, Outdated)

VATSIM Notify is a Discord bot that uses VATSIM's legacy datafeed to alert members in Discord server when a user logs into the network. It simply parses the datafeed, caches it, waits for the next update, and compares the data. Based on the comparison it will alert accordingly.
