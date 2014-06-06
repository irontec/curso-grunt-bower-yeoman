#### usemin exports 2 different tasks:

* useminPrepare.

    * prepares the configuration to transform specific construction (blocks) into a single line.
    * transformation flow: concat -> uglifyjs

* usemin

    * replaces the blocks by the file they reference
    * references to assets by their revisioned version (grunt-rev)
