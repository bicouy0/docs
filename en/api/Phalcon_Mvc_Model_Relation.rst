Class **Phalcon\\Mvc\\Model\\Relation**
=======================================

This class represents each relationship between two models


Constants
---------

*integer* **BELONGS_TO**

*integer* **HAS_ONE**

*integer* **HAS_MANY**

*integer* **MANY_TO_MANY**

Methods
---------

public  **__construct** (*int* $type, *string* $referencedModel, *string|array* $fields, *string|array* $referencedFields, *array* $options)





public *int*  **getType** ()

Returns the relation's type



public *string*  **getReferencedModel** ()

Returns the referenced model



public *string|array*  **getFields** ()

Returns the fields



public *string|array*  **getReferencedFields** ()

Returns the referenced fields



public *string|array*  **getOptions** ()

Returns the options



public *string|array*  **isForeingKey** ()

Check whether the relation act as a foreign key



public *string|array*  **getForeignKey** ()

Returns the foreign key configuration


