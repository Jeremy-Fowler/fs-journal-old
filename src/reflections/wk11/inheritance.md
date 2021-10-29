# Inheritance

## What does Inheritance accomplish for us in C#?

Inheritance is the relationship between two classes, and allows parents to pass down code to children.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?

Not all members of a class can be inherited. Constructors and finalizers are not inherited from base classes.

## How does accessibility affect inheritance?

Public members are part of the public interface of children. Private members cannot be used by children unless nested in the parent class. Protected members can only be used in child classes. 