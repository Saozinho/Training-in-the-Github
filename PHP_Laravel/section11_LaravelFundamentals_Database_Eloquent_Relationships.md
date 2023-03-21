# Section 11 Laravel Eloquent Relationships

**Eloquent/ORM**
 
- Laravel includes Eloquent, an object-relational mapper (ORM) that makes it enjoyable to interact with your database. When using Eloquent, each database table has a corresponding "Model" that is used to interact with that table.

**One-to-One Relationship:** 

- In a one-to-one relationship, each record in one table is associated with exactly one record in another table. In Eloquent, you can define a one-to-one relationship using the ``hasOne()`` method on the parent model and the ``belongsTo()`` method on the child model.

**One-to-Many Relationship:**

- In a one-to-many relationship, each record in one table can be associated with multiple records in another table. In Eloquent, you can define a one-to-many relationship using the ``hasMany()`` method on the parent model and the ``belongsTo()`` method on the child model.

**Many-to-Many Relationship:**

- In a many-to-many relationship, each record in one table can be associated with multiple records in another table, and vice versa. In Eloquent, you can define a many-to-many relationship using the ``belongsToMany()`` method on both models.

**Polymorphic**

- A polymorphic relationship allows the child model to belong to more than one type of model using a single association.