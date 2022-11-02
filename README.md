# SoN Timesheet

> Please note that i was an absolute beginner to nix and learning curve was a bit steeper, so learning and documentation took more than i expected

> Work after  2022-08-22 was mostly mob programming and debugging, and some of the issues are yet to be addressed and some documentation to be completed so contribution to Nix will continue.

**Name**: Yawar Mushtaq ([yawar1](https://github.com/yawar1))

## 2022-07-18 -- 2022-07-24

Hours: 40

**Meetings:**

 * Kickoff meeting 1
 * Team Meetings
 * Jitsi project meeting
 * Pair programming with [xmzlyw](https://github.com/xmzlyw)

**Learning:**

 * [Nix basics](https://www.youtube.com/watch?v=NYyImy-lqaA&list=PLRGI9KQ3_HP_OFRG6R-p4iFgMSK1t5BHs)
 * [Set up NixOS](https://www.youtube.com/watch?v=QKoQ1gKJY5A&list=PL-saUBvIJzOkjAw_vOac75v-x6EzNzZq-)
 * [History and Motivation about Nix](https://edolstra.github.io/pubs/phd-thesis.pdf)


## 2022-07-25 -- 2022-07-31

Hours: 40

**Meetings:**
* Team Meetings
* Pair Programming with teammates
* Public Lecture: History of Nix


**Learning:**

* [Nix Expression overview](https://nixos.wiki/wiki/Overview_of_the_Nix_Language)
* [Practiced Expression](https://nixcloud.io/tour/?id=1)
* [Nix package tutorials](https://www.youtube.com/watch?v=Ndn5xM1FgrY)
* [Nix Package Docs](https://nixos.wiki/wiki/Packaging/Tutorial)

**Worked on packages:**

* Went through the issues of ngi
    * Had meetings onto what issues to work
    * Tried fixing issues
* Packaged GNU-Hello-World 

## 2022-08-01 -- 2022-08-07

Hours: 40

**Meetings:** 
* Public Lecture: The Architecture and History of Nixpkgs
* Pair programming with [collin](https://github.com/collinarnett)
* Pair Programming with [Dan](https://github.com/tshaynik)
* Pair Programming with [xmzlyw](https://github.com/xmzlyw) (x3)


**Learning:**
* Learned about jitsi project
* Learned about Etherpad
* Learned nodejs application Packaging

**Worked on packages:**

* Looked into jitsi issues
* Worked on Packaging Etherpad

## 2022-08-08 -- 2022-08-14

Hours: 40

**Meetings:**

* Team meeting
* Pair programming with [collin](https://github.com/collinarnett)(x 2)
* Pair Programming with [xmzlyw](https://github.com/xmzlyw) (x 2)
* Public Lecture: Flattening the Learning Curve

**Learning:**
* Node2nix
* Dream2nix
    * Learned about working of flakes

**Worked on packages:**

* Packaging Etherpad
    * Writing derivation with node2nix
    * Patching files using bash scripts
    * Installing packaged etherpad and bug fixing

## 2022-08-15 -- 2022-08-21

Hours: 37

**Meetings:**
* Team meeting
* Pair programming with [collin](https://github.com/collinarnett)
* Pair Programming with [Dan](https://github.com/tshaynik)
* Team Meeting
* Meeting with about working on Maemo Leste [cab](https://github.com/cab404)
* Public Lecture: Nix Is Going Mainstream


**Learning:**
* Packaging for [Debian](https://wiki.debian.org/HowToPackageForDebian)
* Learned about [Maemo Leste](https://leste.maemo.org/Main_Page)

**Worked on packages:**
* [Packaged Etherpad](https://github.com/ngi-nix/Etherpad_nix)

## 2022-08-22 -- 2022-08-28

Hours: 40

**Meetings:**
* Public Lecture: Hydra, Nix's CI
* Weekly Team session
* Pair Programming with Atharva

**Learning:**
* Hydra, Nix's CI
* Implementing Cachix in Github Actions

**Worked on packages:**
* Sylk Mobile
  * Package [python3-otr](https://github.com/NixOS/nixpkgs/pull/188015)
* GNUNet Messenger
    * Triage
  
## 2022-08-29 -- 2022-09-04

Hours: 40

**Meetings:**
* Weekly Team session
* Michiel Leenaars - The Significance of Reproducible Software in International R&D 
* Pair Programming with Atharva

**Learning:**
* Testing nixos-containers
* How documentation in Nix toolchains work
* Mob Programming

**Worked on packages:**

* NixOS-Container
  * Continued Documentation of [nixos-container](https://hackmd.io/4bVSA0uWTPGEh9ZN54fGbQ)

* Waasabi
  * General Triage
  * Worked on the [issue](https://github.com/ngi-nix/ngi/issues/256)

* Etherpad
  * Pair Programmed with Atharva
  * Used dream2nix and flakes to debug [etherpad](https://github.com/ngi-nix/Etherpad_nix/blob/master/flake.nix)

* Sylk Server
  * Bugfixes in the PR

## 2022-09-05 -- 2022-09-18

Hours: 30

**Meetings:**

* Pair Programming
* John Ericson's Nix x IPFS talk
* Konrad Hinsen - Nix/Guix and Reproducible Science

**Learning:**

* Running nix-darwin with `OSX-KVM`
* NodeJS on Nix
* Gitlab actions for cachix

**Worked on packages:**

* NextCloud
  * General Triage
  * Curated the schema and list of packages needed to be packaged
  * Will be completed post Summer of Nix( alongside atharva )
  
* GNUNet Messenger
  * General Triage

* NixOS-Container
  * Continued Documentation of [nixos-container](https://hackmd.io/4bVSA0uWTPGEh9ZN54fGbQ)

## 2022-09-19 -- 2022-09-30

Hours: 30

**Meetings:**
* Pair Programming with Atharva
* Luc Perkins - Real World DevOps with Nix
* Connor Brewster - The Road to Nix at Replit 

**Learning:**
* crate2nix
* Github Actions for rust based packages

**Worked on packages:**

* Sylk Server
  * Bug Fixes and Improvements

* Wiredguard Rust Implementation
  * Schema for Github Actions
