#Padam87AttributeBundle

An [EAV](http://en.wikipedia.org/wiki/Entity%E2%80%93attribute%E2%80%93value_model) implementation for Symfony2.

The purpose of this bundle is to allow users to create custom fields for entities.

Custom fields can be unique per row in the DB, or can be related to an entity itself.

[Installation](https://github.com/Padam87/AttributeBundle/blob/master/Resources/doc/installation.md)

[Usage with Schema](https://github.com/Padam87/AttributeBundle/blob/master/Resources/doc/usage_with_schema.md):
Custom fields are related to the entity. When the schema is updated, the attributes are syncronized.

[Usage without Schema](https://github.com/Padam87/AttributeBundle/blob/master/Resources/doc/usage_without_schema.md):
Custom fields are related to each data row individually.