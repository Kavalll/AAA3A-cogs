.. _seen:
====
Seen
====

This is the cog guide for the 'Seen' cog. This guide contains the collection of commands which you can use in the cog.
Through this guide, ``[p]`` will always represent your prefix. Replace ``[p]`` with your own prefix when you use these commands in Discord.

.. note::

    Ensure that you are up to date by running ``[p]cog update seen``.
    If there is something missing, or something that needs improving in this documentation, feel free to create an issue `here <https://github.com/AAA3A-AAA3A/AAA3A-cogs/issues>`_.
    This documentation is auto-generated everytime this cog receives an update.

--------------
About this cog
--------------

A cog to check when a member/role/channel/category/user/guild was last active!

--------
Commands
--------

Here are all the commands included in this cog (14):

* ``[p]seen ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] <object>``
 Check when a member/role/channel/category was last active!

* ``[p]seen board ["message"|"message_edit"|"reaction_add"|"reaction_remove"] ["members"|"roles"|"channels"|"categories"=members] [reverse=False]``
 View a Seen Board for members/roles/channels/categories!

* ``[p]seen board guilds ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [reverse=False]``
 View a Seen Board for guilds!

* ``[p]seen board users ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [reverse=False]``
 View a Seen Board for users!

* ``[p]seen category ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [category=None]``
 Check when a category was last active!

* ``[p]seen channel ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [channel=None]``
 Check when a channel was last active!

* ``[p]seen getloopstatus``
 Get an embed for check loop status.

* ``[p]seen guild ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [guild=None]``
 Check when a guild was last active!

* ``[p]seen hackmember ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] <user>``
 Check when a old member was last active!

* ``[p]seen hackuser ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] <user_id>``
 Check when a old user was last active!

* ``[p]seen member ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [member=None]``
 Check when a member was last active!

* ``[p]seen purge ["user"|"member"|"role"|"channel"|"guild"=None]``
 Purge Config for a specified type ou all.

* ``[p]seen role ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [role=None]``
 Check when a role was last active!

* ``[p]seen user ["message"|"message_edit"|"reaction_add"|"reaction_remove"] [show_details] [user=None]``
 Check when a user was last active!

------------
Installation
------------

If you haven't added my repo before, lets add it first. We'll call it
"AAA3A-cogs" here.

.. code-block:: ini

    [p]repo add AAA3A-cogs https://github.com/AAA3A-AAA3A/AAA3A-cogs

Now, we can install Seen.

.. code-block:: ini

    [p]cog install AAA3A-cogs seen

Once it's installed, it is not loaded by default. Load it by running the following command:

.. code-block:: ini

    [p]load seen

---------------
Further Support
---------------

Check out my docs `here <https://aaa3a-cogs.readthedocs.io/en/latest/>`_.
Mention me in the #support_other-cogs in the `cog support server <https://discord.gg/GET4DVk>`_ if you need any help.
Additionally, feel free to open an issue or pull request to this repo.