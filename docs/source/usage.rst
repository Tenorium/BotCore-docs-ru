Usage
=====

.. _installation:

Installation
------------

To use BotBore, first clone with git:

.. code-block:: console

    $ git clone https://github.com/Tenorium/BotCore.git


Then move into cloned repository and install dependencies:

.. code-block:: console

	$ npm install

.. _configuring:

Configuring
-----------

Config fields:

logger
    Logger options.

    debug
        :type: Boolean
        Enable debug mode
    dateformat
        :type: String
        Compatible with `moment.js <https://momentjs.com/docs/#/displaying/format/>`_ date format
client
    `Options <https://discord.js.org/#/docs/main/stable/typedef/ClientOptions>`_ for Discord.JS client
locale
    :values: "ru","en"
    Locale used by botcore.
token
    Discord bot token
prefix
    Prefix for commands
