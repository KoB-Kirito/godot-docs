:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/CircleShape2D.xml.

.. _class_CircleShape2D:

CircleShape2D
=============

**Inherits:** :ref:`Shape2D<class_Shape2D>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Circular shape resource for 2D physics.

.. rst-class:: classref-introduction-group

Description
-----------

2D circular shape to be added as a *direct* child of a :ref:`PhysicsBody2D<class_PhysicsBody2D>` or :ref:`Area2D<class_Area2D>` using a :ref:`CollisionShape2D<class_CollisionShape2D>` node. This shape is useful for modeling balls or small characters and its collision detection with everything else is very fast.

\ **Performance:** Being a primitive collision shape, **CircleShape2D** is the fastest collision shape to check collisions against, as it only requires a distance check with the shape's origin.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------+----------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`radius<class_CircleShape2D_property_radius>` | ``10.0`` |
   +---------------------------+----------------------------------------------------+----------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_CircleShape2D_property_radius:

.. rst-class:: classref-property

:ref:`float<class_float>` **radius** = ``10.0``

.. rst-class:: classref-property-setget

- void **set_radius** **(** :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_radius** **(** **)**

The circle's radius.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
