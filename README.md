# entityreference_enhancements
This is a Drupal 7 module for preventing data from being deleted if there is an Entity Reference to it.  The module 
also finds Entity References that reference missing entities.

## Preventing Deletion
The module will prevent the deletion of Nodes, Taxonomy Terms, Taxonomy Vocabularies, and Users, if there
is a reference to the content in question.  

**Note**: Support for Comments depends on a bug fix.
**Note**: Support for Files is coming.
**Note**: This module prevents deletion of content in the UI only. **It is still possible to delete content through code
or other methods not covered by this module.**

## Missing Entities
The module will detect missing entities through Entity References.  There is support for all Entity References types.

You can access this with the URL /bad_data off the base URL of your site.

**Note**: More checks will happen in the future.
**Note**: Improvements to the report will be made.  Some ideas: detect empty references, combining links for a given 
piece of content. 





