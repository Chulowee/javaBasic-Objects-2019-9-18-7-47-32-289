# ExceptionTest
## Test -> should_customize_exception
## Test -> should_customize_exception_continued
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Exceptions. 
* The official document of this knowledge point is https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual return value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way to be have the exception return the message.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_be_careful_of_the_order_of_finally_block
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Finally block. 
* The official document of this knowledge point is https://www.javatpoint.com/finally-block-in-exception-handling.
* Q2: Why the test failed at first?
* The test failed at first because the return value assigned to the expected result is wrong.
* Q3: Why you corrected the test that way?
* I corrected it this way since finally will always be executed.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_use_the_try_pattern
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Try pattern. 
* The official document of this knowledge point is https://stackoverflow.com/questions/11085281/try-do-pattern-implementation-in-java.
* Q2: Why the test failed at first?
* The test failed at first because assigned expected result was not equal to the actual result.
* Q3: Why you corrected the test that way?
* I corrected it this way since try will always be executed.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_call_closing_even_if_exception_throws
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of AutoClosable. 
* The official document of this knowledge point is https://docs.oracle.com/javase/8/docs/api/java/lang/AutoCloseable.html.
* Q2: Why the test failed at first?
* The test failed at first because there is no assigned value in the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since I tried to follow the flow of the objects.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_get_method_name_in_stack_frame
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of StackTrace. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_stacktraceelement.htm.
* Q2: Why the test failed at first?
* The test failed at first because the function did not return any value.
* Q3: Why you corrected the test that way?
* I corrected it this way since assigning the "Exception().getStackTrace()[1]" would be easier to call for the className and classMethod.
* Q4: Do you have further questions on this knowledge point?
* No.

# ExceptionTest
## Test -> should_be_derived_from_object_class
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since what is asked is what the get superClass returns.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_call_super_class_constructor
## Test -> should_call_super_class_constructor_continued
## should_call_super_class_constructor_more
## should_call_most_derived_methods
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since I tried to follow the flow of the constructors whether it was overiden or not.
* Q4: Do you have further questions on this knowledge point?
* No.

## should_use_caution_when_dealing_with_array_type
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was an exception so it will proceed to catch.
* Q4: Do you have further questions on this knowledge point?
* No.

## should_not_make_you_confused
## should_not_make_you_confused_2
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was an override.
* Q4: Do you have further questions on this knowledge point?
* No.

## should_use_instance_of_to_determine_inheritance_relationship
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since an instance will always retun there an object is declared as new.
* Q4: Do you have further questions on this knowledge point?
* No.

## should_use_instance_of_only_in_inheritance_relationship
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there was no assigned value for the expected.
* Q3: Why you corrected the test that way?
* I corrected it this way since Object was assigned as an Integer, it will only create an instance for Integer and not for Long.
* Q4: Do you have further questions on this knowledge point?
* No.

## should_write_perfect_equals_1
## should_write_perfect_equals_2
## should_write_perfect_equals_3
## should_write_perfect_equals_4
## should_write_perfect_equals_5
## should_write_perfect_equals_6
## should_write_perfect_equals_7
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Inheritance. 
* The official document of this knowledge point is https://www.javatpoint.com/inheritance-in-java.
* Q2: Why the test failed at first?
* The test failed at first because there were no comparing for the entries in the inheritted class.
* Q3: Why you corrected the test that way?
* I corrected it this way since the object needed to be made unique first by hashcode, then will be filtered or compared to other entries even if one element is the same. They are looked as a whole to avoid misenterpretations.
* Q4: Do you have further questions on this knowledge point?
* No.

# ObjectTest
## Test -> should_point_to_the_same_object
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual return value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since I just followed if they were equal.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_point_to_different_object
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects(LocalDate). 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since LocalDate will always return a new instance.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_point_to_different_object
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since the Object declared did not put any value in the variables, they will proceed to have null for string and 0 for int or any number types.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_pass_by_value
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since the declared object that had the update method was not used, rather the same reference was assigned to the expected.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_calling_another_constructor
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since there was already a name declared in the object called.
* Q4: Do you have further questions on this knowledge point?
* No.

## Test -> should_calling_another_constructor
## Test -> should_get_message_of_var_length_parameters
## Test -> should_get_message_of_var_length_parameters_2
* Q1: What is the knowledge point of the test? Where is the official document to the knowledge point?
* The knowledge point of the test is to learn the behavior of Objects. 
* The official document of this knowledge point is https://www.tutorialspoint.com/java/lang/java_lang_object.htm.
* Q2: Why the test failed at first?
* The test failed at first because there was no actual value in the exception.
* Q3: Why you corrected the test that way?
* I corrected it this way since I just had to follow the flow.
* Q4: Do you have further questions on this knowledge point?
* No.