# PSEC Electronics Integration Plan

### Main Components

The goal of this effort is to produce a single, self contained package that powers the LAPPD and readout electronics, handles communications, and manages the slow controls. 

The goal is to have a fully functioning realization of this system by early-to-mid January. There are several components
of the system:

* The Analog Pick-Up Board: This is the board that bring the signals from the LAPPD around the backside of a PCB with XX connectors to mate with the ACDC cards.

* The Bridge Boards: bridge the connection from the silver striplines of the LAPPD to the Analog Pick-up board

* The two ACDC cards: Plug into the back of the analog pickup board and digitize the signals

* LV-HV Board: Provides the five HV lines for the LAPPD, two 5-V lines for the ACDC cards, optical isolation for the LVDS communication between the ACDCs (in the housing) and the ACC cards (surface), and slow monitoring/communication via a microcontroller and CANBUS.

### Physical Assembly

The LAPPD will be mounted onto the pickup board, both contained in the plastic frame, as designed by incom
