$(mixer)
========

Show text in Mixer chat only.

Usage:
    $(mixer ``<message>``)

Arguments:
    * ``message`` **<required>** - The message to display in chat

Example Command:
    **name**: !example

    **response**: You are a $(mixer super awesome and) cool dude$(mixer !)

    **mixer output**::

        user:     !example
        botisimo: You are a super awesome and cool dude!

    **twitch/youtube/discord output**::

        user:     !example
        botisimo: You are a cool dude
