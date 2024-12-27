# Ada: Incorrect Usage of 'Img' Attribute

This example demonstrates a common error in Ada related to the incorrect use of the `'Img` attribute.  The `'Img` attribute is used to access the modular type's image, which is only relevant for modular types, not for standard Integer types.  This code attempts to use `'Img` with an Integer array, resulting in a compilation error.

The solution shows how to correct the code by removing the incorrect usage of `'Img` and using direct array indexing.