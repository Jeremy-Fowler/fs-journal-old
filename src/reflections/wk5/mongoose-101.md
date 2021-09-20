# Mongoose 101

## In simple terms what is a sub-document?

Sub-documents are documents that are nested in other documents.

## When might you use a sub-document?

You might use a sub-document when creating a model that has multiple properties that you'd like to update at any given time.

## How do you add to a collection of sub-documents? What about editing them?

To add to a collection of sub-documents, you first create an object, then you define the object and use the .save() method.

To edit sub-documents, you use the .findOne() method, and the use the .push() method to add sub-documents. You can use string notation to edit one sub-document.

https://jeremy-fowler.github.io/galaxy/