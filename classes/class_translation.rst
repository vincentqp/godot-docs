.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Translation.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Translation:

Translation
===========

**Inherits:** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`PHashTranslation<class_PHashTranslation>`

**Category:** Core

Brief Description
-----------------

Language Translation.

Properties
----------

+-----------------------------+-----------------------------------------+
| :ref:`String<class_String>` | :ref:`locale<class_Translation_locale>` |
+-----------------------------+-----------------------------------------+

Methods
-------

+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                           | :ref:`add_message<class_Translation_add_message>` **(** :ref:`String<class_String>` src_message, :ref:`String<class_String>` xlated_message **)** |
+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                           | :ref:`erase_message<class_Translation_erase_message>` **(** :ref:`String<class_String>` src_message **)**                                         |
+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                    | :ref:`get_message<class_Translation_get_message>` **(** :ref:`String<class_String>` src_message **)** const                                       |
+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                          | :ref:`get_message_count<class_Translation_get_message_count>` **(** **)** const                                                                   |
+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PoolStringArray<class_PoolStringArray>`  | :ref:`get_message_list<class_Translation_get_message_list>` **(** **)** const                                                                     |
+------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------+

Description
-----------

Translations are resources that can be loaded/unloaded on demand. They map a string to another string.

Property Descriptions
---------------------

.. _class_Translation_locale:

- :ref:`String<class_String>` **locale**

+----------+-------------------+
| *Setter* | set_locale(value) |
+----------+-------------------+
| *Getter* | get_locale()      |
+----------+-------------------+

Method Descriptions
-------------------

.. _class_Translation_add_message:

- void **add_message** **(** :ref:`String<class_String>` src_message, :ref:`String<class_String>` xlated_message **)**

Add a message for translation.

.. _class_Translation_erase_message:

- void **erase_message** **(** :ref:`String<class_String>` src_message **)**

Erase a message.

.. _class_Translation_get_message:

- :ref:`String<class_String>` **get_message** **(** :ref:`String<class_String>` src_message **)** const

Return a message for translation.

.. _class_Translation_get_message_count:

- :ref:`int<class_int>` **get_message_count** **(** **)** const

.. _class_Translation_get_message_list:

- :ref:`PoolStringArray<class_PoolStringArray>` **get_message_list** **(** **)** const

Return all the messages (keys).

