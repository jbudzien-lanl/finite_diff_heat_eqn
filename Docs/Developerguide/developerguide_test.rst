.. _testsuite:

Add a Test to the Test Suite
============================

 #. Decide whether you need a new class based on the setup/teardown necessary

    * For a new class, decide if you need a new file or can add to the existing file(s).  Base your decision on fit with other tests and projected number of similar tests to be added in the near future.  Length of file is less important than grouping similar tests together.

    * For an existing class, think carefully about any changes to the setup/teardown.  Do you really want to use the same class or do you want to create a new class with some inheritance from the existing class?  The answer depends on thinking through all the proposed tests and a plan.

 #. Create the test and be sure that it can be found through the testing mechanism.

 #. If you have created any new files in Finitediff/Tests, update the Docs/Tests directory with a test_<name>.rst file.  Follow the template at test_template.rst.

