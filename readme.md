# FINAL PROJECT

Issues and References to their solutions
1. There is an issue with the email verification as it is showing None when a user clicks on the Verify Email link #1

Issue Reference: https://github.com/alvitesg/user_management/issues/1

Enhanced Testing: Created 4 new tests within the test_user_service.py
test_first_user_role_assignment
test_password_hashing_on_creation
test_list_users_extreme_pagination
test_user_creation_sends_verification_email_with_token

To capture verification of the issue and enhance the overall testing file for user services.

Issue Closure: 
Merge pull details and successful integration of solution into main branch: https://github.com/alvitesg/user_management/actions/runs/8978932160

2.  First user should have Admin role but expired verification token shows up as error 

Issue Reference: https://github.com/alvitesg/user_management/issues/2
Issue Closure: https://github.com/alvitesg/user_management/pull/3

3. Nickname used to register is not the correct being stored in the pgAdmin DB
Issue Reference: https://github.com/alvitesg/user_management/issues/4
Issue Closure: https://github.com/alvitesg/user_management/pull/5/files

Enhanced Testing
test_generate_unique_nickname_with_collision

4. Emails can be duplicated
Issue reference: https://github.com/alvitesg/user_management/issues/6
Issue Closure: https://github.com/alvitesg/user_management/pull/7

5. Enhance documentation to improve software developer experience
Issue reference: https://github.com/alvitesg/user_management/issues/8
Issue Closure: commit: https://github.com/alvitesg/user_management/actions/runs/8975337397

Pytest Coverage Screenshot: 
GitHub Commits: https://github.com/alvitesg/user_management/actions
DockerHub Repository: https://hub.docker.com/r/alvitesg/user_management/tags
Enhanced Testing: In addition to the tests integrated above, additional tests were included to solidify the user schema and user api: https://github.com/alvitesg/user_management/pull/10

New Feature Implementation:

Key Takeaway from class:
As a risk management and treasury subject matter expert with 20 years of experience in financial services and insurance, I am impressed by the lack of understanding I had of the backend processes of an app. My biggest takeaway is if we start to teach kids how to navigate via the back end process, operations and activities will be done so much more efficiently and controlled (if tested). I am looking forward to taking my learnings from this class and seeing how I can integrate some of these tools and capabilities to eliminate low value of work individuals do with front end applications.
