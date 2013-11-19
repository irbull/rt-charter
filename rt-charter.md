RT Project Charter
=====
This charter was developed in accordance with the Eclipse Development Process and 
outlines the mission, scope, organization, and development process for the Eclipse 
Runtime Project (RT). This document extends the Eclipse Standard Top-Level Charter 
v1.1, and includes the required content and overrides which follow. It is 
anticipated that as the standard charter is updated, this charter will incorporate 
the changes and make adjustments as seen fit by the PMC, and with approval from 
the EMO and board of directors.

Overview
-------
Since the creation of the Eclipse Rich Client Platform (RCP) and the adoption of 
Equinox and OSGi in 2004, interest in and use of Eclipse technologies in runtime 
scenarios has been steadily increasing. Initially, the focus of these runtime 
efforts was on desktop or client technologies. The community has steadily found 
new and innovative uses for Equinox and the Eclipse platform in areas such as 
devices, rich internet applications and servers.

RT is an open source collaborative software development project dedicated to 
supporting and enhancing these efforts and providing a generic, extensible, 
standards-based runtime platform.

This document describes the composition and organization of the project, roles and 
responsibilities of the participants, and development process for the project.

Mission
------
RT is designed to foster, promote and house runtime efforts in the Eclipse community. 
These efforts strive towards the common goal of providing a uniform component model 
across a wide variety of computing environments. The Equinox framework and OSGi 
form the basis of this infrastructure.

RT projects target "clients" and "servers" across embedded devices, desktops, 
and enterprise systems, and provide those intermediate software services which 
enable applications to be more easily and concisely constructed across these 
environments. This supports and extends the Equinox vision of a consistent 
programming and component model where developers create application domain code 
that runs on a variety of platforms.

By providing a consistent symmetric architecture, RT technology enables 
developers to focus on the business problem at hand and still have many system 
architecture options available at deployment time.

Scope
----
Concretely, RT projects supply the Equinox implementation of the OSGi core 
framework specification and a set of bundles that implement additional services 
and other infrastructure for running applications on the Equinox framework and 
OSGi-based systems. The nature of this work is scoped as follows:

* Developing and delivering the OSGi framework implementation used for all of Eclipse.

* Implementation of all aspects of the OSGi specification (including but not limited 
to the Enterprise Expert Group, Mobile Expert Group and Vehicle Expert Group work).

* Investigation and research related to future versions of OSGi specifications and related runtime issues.

* Implementation of key framework services and extensions needed for running 
Eclipse (e.g., the Eclipse Adaptor, Extension registry) and deemed generally useful to systems using Equinox.

* All implementations must be based on OSGi and run on Equinox.

* The implementation of generally applicable runtime standards (e.g., OASIS, JCP).

* Incidental tooling efforts to enable or facilitate particular runtime functions in 
conjunction with (e.g., as a component of) a sub-project.

Out of Scope
-----
* Major tooling efforts
* Industry-specific vertical technologies