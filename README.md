# laravel-pivot-polymorph
Polymorphic relations for eloquent.
This package supports fully morph reciprocalMany relation.

## Usage
Include trait `\Pisochek\PivotPolymorph\Concerns\HasRelationships` to model.
Then like any other relation, write, for example:

`return $this->ReciprocalMany('relatedClass, 'parentName', 'relatedName', 'table');`

Use morphMap in model if needed