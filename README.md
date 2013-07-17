Validation
==========

Brainstorming on Validation as an Extension:
 * Could just create a validation function in DRY extensions.
 * Start at Object and add base validation options?
 * test.Validate(RuleSet) -- for a set of rules dynamically defined
  * Or test.Validate() which sets of generic rules for that kind of object
      {... 
        public static Validate(this TestObject)
            (
                return  Rule1(TestObject).Rule2(TestObject)....
             )
