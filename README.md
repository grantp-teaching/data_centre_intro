---
title: Data Centre Introduction
---

IT equipment
============

The data centre exists to house IT equipment. Broadly, this can be
broken down into:

Servers

:   providing compute capability. May be single-purpose servers,
    virtualisation hosts, modular multiple-unit blade server enclosures
    or larger mainframe equipment.

Storage systems

:   providing aggregate storage to servers, such as dedicated NAS and
    SAN devices. May also include backup-centric storage such as tape
    storage systems.

Networking equipment

:   including switches (unmanaged, L2/L3 managed), routers, hardware
    firewalls, hardware VPN, WAN termination and routing equipment.

Management equipment

:   including local KVM, remote KVM, KVM-over-IP, serial console
    servers, smart power distribution units.

Data hall
=========

The data hall is the main area of interest in a data centre where IT
equipment is housed, . Data centre environments may have one or more
data halls, sometimes called suites.

![Data hall schematic (TSM tutorials)<span
data-label="fig:data-hall-schematic"></span>](data_hall){width="1.0\linewidth"}

Raised floor
------------

The data hall often has a raised floor, meaning that the tiles can be
removed and a space exists under the floor, . It is somewhat similar to
a false-ceiling in reverse.

![Raised floor (Wikipedia)<span
data-label="fig:raised-floor"></span>](raised_floor_wikipedia){width="0.75\linewidth"}

Not all data centres have raised floors. Where present, the raised floor
has two key functions:

-   Provides space for cooling air to circulate. Some times are solid
    but others are perforated to allow air to escape. More on
    that later.

-   Allows cables to be routed and re-routed easily.

Infrastructural equipment
-------------------------

All data halls will vary. However, most will include some/all of the
following:

Power distribution

:   panels including circuit breakers, switches and meters. Also may
    include floor-standing UPS units.

Climate control

:   equipment to maintain the room temperature and humidity in allowable
    ranges, often termed CRAC or CRAH.

Fire

:   detection and suppression equipment.

Security

:   equipment including access control devices, motion sensing and
    video cameras.

Cage
----

A cage is a subdivision of a data hall to demarcate a number of racks
for security or regulatory purposes.

![Cage (Equinix)<span
data-label="fig:cage"></span>](cage){width="1.0\linewidth"}

Form factor
===========

Rack units
----------

IT equipment in data centre environments is normally rack-mount form.
Rack-mount equipment has a standard width of or 19 inches, which
includes the rack ears protruding from the side of each piece of
equipment.

Equipment height is standardised in multiples of or 1.752 inches. One
rack unit (commonly called 1U) is equivalent to . Conventionally we just
use the number of units, such as 4U.

Blade servers
-------------

You will sometimes encounter so-called Blade Servers in high-performance
computing environments. A blade system consists of a chassis that holds
a number of individual blade servers, . Each blade server is a fully
functional server but is powered and may receive connectivity via a
backplane in the enclosure. Blade servers needs to be managed carefully
as their power density is very high.

![Blade server enclosure (Wikipedia)<span
data-label="fig:blade-server-enclosure"></span>](blade_server_enclosure){width="0.3\linewidth"}

Non-rackmount equipment
-----------------------

Non-rackmount equipment such as tower-type server PCs should be
discouraged in data centre environments. Sometimes legacy equipment has
to be accomodated. The only exception to this would be large equipment
like mainframe computers which are supplied in a cabinet case, .

![IBM mainframe<span
data-label="fig:ibm-mainframe"></span>](ibm_mainframe){width="0.5\linewidth"}

Equipment layout
================

IT equipment is mounted in racks within cabinets. Cabinets make up rows
and pairs of rows make up aisles.

Cabinet
-------

A cabinet contains front-and-back vertical rack rails, and is secured by
a lockable door, usually perforated. Equipment is racked within the
cabinet. Standard full-size cabinets are 42U in height, with each
position numbered from the bottom upwards.

![image](cabinet){width="1.0\linewidth" height="0.8\paperheight"}

Most servers, like desktop computers, are air cooled. Air is drawn in at
the front and ejected out the rear of the server. Servers are always
racked front-to-back.

Cabling is normally done at the rear of the rack. Networking and power
distribution equipment is often (but not always) mounted at the rear of
a cabinet facing the rear.

Rack mounting
-------------

Racks have holes drilled in them for allowing equipment to be secured.
These are normally unthreaded, and allow cage nuts and bolts to be
inserted. The cage nut inserts into the rack, whilst the bolt is
inserted through the holes drilled in the IT equipment’s rack ears.

![Cage nuts and bolt (wikipedia)<span
data-label="fig:cage-nut"></span>](cage_nut){width="0.75\linewidth"}

Heavier pieces of equipment such as servers normally are placed on
horizontal rails inserted into the rack first. The rails are secured to
the front and back racks.

Rows
----

Where more than one cabinet is required, they are normally placed beside
each other to form a row. The number of cabinets in a row will depend on
spatial and usage requirements.

Aisle
-----

An aisle is where two rows of cabinets face each other. Data centres
normally use a hot aisle/cold aisle arrangement where servers face each
other front-on or rear-on. This is to aid in cooling (see later).

![Hot/cold aisle (Oracle)<span
data-label="fig:hot-cold-aisle"></span>](hot_cold_aisle_oracle){width="1.0\linewidth"}

Regulation
==========

Reliability standards

:   govern to what degree a data centre can be described as
    fault-tolerent:

    Uptime institute

    :   has a number of “tiers” which summarise how reliable a
        particular data centre environment is.

    TIA-942

    :   has a number of similar tiers that are primarily dependent on
        reliability and redundancy

Efficiency standards

:   aim to minimise the energy usage and environmental impact of data
    centres:

    LEED

    :   

Data-related legislation

:   has legal effect and may have ramifications in certain data centre
    environments:

    GDPR

    :   governing personal data

    FOI

    :   ensuring right of access to own personal data and to aggregate
        public data. Similar FOI laws exist in many countries.

    HIPPA

    :   controlling how health data is stored and process

    COPPA

    :   controlling how personal data of children is used and collected,
        including how consent from children/parents is taken for
        data processing.

Industry standards

:   often are a requirement to do business in certain sectors and need
    to be followed:

    PCI/DSS

    :   relating to handling and storage of payment card data.
        Compliance is normally a condition of being given
        merchant facilities.

    ISO 27001

    :   relating to storage/handling of general data in a
        secure fashion. Compliance is often a condition of being awarded
        business from certain public and private organisations.

Key trends
----------

There are a number of trends globally that are influencing data centre
design and usage:

Virtualisation

:   is becoming much more common where a hypervisor manages multiple
    operating systems on a single physical machine.

Cloud

:   is a greater focus. Both in terms of replacement of certain on-site
    infrastructure with cloud services, integration in a hybrid
    onsite/cloud setup and provision of private cloud facilities.

Security

:   is now a main focus area, and generally needs to be handled
    throughout all other activities as standard practice.

Environmental awareness

:   both for energy saving, cost reduction and business reputation.

Automation

:   to reduce the need for physical visits to the data
    centre environment.

![Modular data centre (IBM/Wikipedia)<span
data-label="fig:modular-data-centre"></span>](modular_data_centre){width="1.0\linewidth"}

People involved
===============

Customer

:   We will use customer to mean a customer of data centre services, as
    opposed to end user who utilises the services provided. The data
    centre customer has essentially got two options: on-site or
    co-located data centre.

End users

:   People / systems who use the services provided by our data centre
    environment. They normally have expectations of availability,
    reliability but are not connected with the running of the
    data centre.

Estates / Facilities management personnel

:   Depending on the facilty, a demarcation between the roles of data
    centre and facilites management will exist. This will become evident
    in things around power, cooling and fire alarm infrastructure. The
    relationship between data centre managers / technicians and
    facilities management professionals is a key asset to a well-run
    data centre environment.

On-site
=======

Many organisations operate some on-site data centre provision:

-   Some organisations may build and operate dedicated data centres for
    their own use.

-   Many organisations will have a data centre that forms part of a
    larger facility, such as a hospital or college. It is often the case
    that non-IT personnel might have no idea that the facility has a
    data centre or where it is.

-   Often, it’s not even noticed or considered by the persons owning
    them. Even a NAS box stuffed in a corner that holds critical data
    needs to be considered as part of data centre provision!

Connectivity
------------

An on-site data centre will need WAN connections to be ordered. These
may take a number of forms such as standard DSL, GPON fibre, leased
lines, microwave links. Carrier-owned equipment is often required and
connects to customer owned equipment at the so-called demarcation point.

An on-site data centre located within a larger facility will also often
form the central hub of the end-user-facing networking throughout the
building or site, such as the office LAN.

Responsibilities
----------------

On-site data centres need careful co-ordination of different
responsibilities:

IT personnel

:   normally undertake network admin, system admin, patching and other
    IT-related duties.

Facilities management

:   normally look after plant such as heating/cooling, parts of the
    electrical system and may have to facilitate
    copper/fibre installations.

Where exactly the demarcation between both sets of staff occurs is fluid
and organisation-dependent. However, it is essential that the IT staff
have a basic knowledge of certain mechanical and electrical concepts to
facilitate productive interaction.

Co-location
===========

Co-location is where a customer rents space from a so-called co-location
facility, or co-lo.

Renting
-------

Co-los rent space in various different units:

Rack spaces

:   in single/multiple units.

Full cabinet

:   where the customer has use of a single cabinet in its entirety and
    can populate it as they wish.

Cage

:   is a restricted area within the airspace of the data hall that is
    for a single customer’s use. They can normally populate the cabinets
    within it (supplied by the data centre) as they wish.

Suite

:   is where an entire data hall is provided to a single customer.

Networking
----------

Within a co-lo environment, the customer is solely responsible for their
own networking. This means that the co-lo provider *does not* supply IP
addresses or outbound connectivity as standard. Customers must have the
appropriate networking cables and equipment to adequately connect their
own equipment together.

Cross-connects
--------------

Customers may sometimes have equipment in multiple cabinets, or may wish
to connect directly to other data centre customers. They can do this by
ordering a cross-connect from the co-lo provider. Depending on the
provider, there may be a charge for this service.

Carrier connection
------------------

Most links to locations away from the data centre will be made via
telecommunication carriers.

Whilst some data centres historically have restricted the carriers a
customer can use, indeed many have been operated by telecommunications
carriers themselves, most are said to be carrier-neutral.

Carriers normally terminate their connections in a so-called meet-me
room (MMR). The meet-me room allows patching through cross-connects to
the customer’s equipment in the data hall.

It is the responsibility of the customer to order the WAN service from
the carrier, and to order the appropriate cross connect from the co-lo
provider.

Business needs
==============

Business needs must drive the choice of data centre provision. Some key
questions include:

1.  Is the workload better served by cloud or data-centre provision in
    the first place?

2.  Are the users of the workload located in one particular site? Or are
    they distributed amongst multiple distinct sites or the wider
    internet?

3.  How criticial is the workload to on-site business continuity?

4.  What volume of data is likely to be exchanged between end-users and
    the data centre?

5.  Can your on-site services match those a co-located provider can
    offer?

The solution chosen is often a compromise, and frequently a combination
of multiple modes. For example:

-   A supermarket chain might be best suited with a small on-site server
    room for in-store services, use a co-lo for central services and a
    cloud provision for its online store.
