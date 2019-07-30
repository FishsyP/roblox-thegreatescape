Control Panel
=============

.. image:: images/allbuttons.png

Screenshot taken on 30/7/2019.

Buttons
=======

.. contents:: Contents
    :depth: 2
    :local:

Bottom Row
----------

.. image:: images/bottom.png
    :width: 75%

These buttons control the room directly.
The buttons in this row are documented in the order from left to right.

Reset
^^^^^

.. warning:: |notYetImplemented|

Resets the whole room.

.. _setup:

Setup
^^^^^

Sets up the room for a round.
This will initiate the start of round sequence.

.. todo::

    Further elaborate

Red Lighting
^^^^^^^^^^^^

Makes the red lights flash.
When turned on, the lights will keep on flashing until they are turned off.
The flashing is disabled by default.
The colour of the button determine its state.

.. csv-table:: Colours and States
    :header: "Colour", "State"
    :widths: 20, 60

    "Brown", "Off (Default)"
    "Green", "On"

Door Lock
^^^^^^^^^

.. warning:: |notYetImplemented|

Locks the door.

Extract Floor
^^^^^^^^^^^^^

Closes the floor if it is open.
This is used if a round is cleared.

.. note::

    This can only be used when the floor is opened.
    To open the floor, click on the :ref:`setup` button.

Beam Controls
-------------

.. image:: images/beams.png
    :width: 75%

These buttons control the movement of the beams.

.. note::

    The room must be set up before these buttons are usable.
    To set up the room, click on the :ref:`setup` button.

Movement
^^^^^^^^

The first column buttons (Beam 1, Beam 2, Beam 3 and Beam 4) control whether
or not the beams are moving.
All beams are not moving by default.
Clicking on these buttons toggles the movement of the respective beams.
The colour of the button determine the state of a beam.

.. csv-table:: Colours and States
    :header: "Colour", "State"
    :widths: 20, 60

    "Red", "Not moving (Default)"
    "Green", "Moving"

Speed
^^^^^
