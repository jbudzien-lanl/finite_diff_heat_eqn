.. _doc_update:

Update Documentation for a New Feature and Test
===============================================

   #. cd Docs
   #. Decisions must be made regarding the feature.

      a. Is this feature part of something bigger or is it a new big change?
          
             **If you plan to have one or fewer <detail>.rst files in a**
             **new Docs/<feature> directory, then this is NOT a new big** 
             **change**

          i. The feature is a new big change:
             
             * Create a new <section>.rst file in the directory Docs named after the feature.  For example, finitediff.rst has the main code definitions. 

             * Pattern the new <section>.rst file using section.txt to ensure having a hyperlink reference, a section title, a brief explanatory note, and a toctree with a minimum of :glob: and pointer to a directory where <detail>.rst files will reside.

             * Create the new directory where <detail>.rst files will reside.

          #. Otherwise, skip to the next question.

      #. Does order matter on the documentation page?

          i. Yes: Edit the list in the <section>.rst file to be the order
              desired.
             
          #. No: Go to next step.
