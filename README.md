# authentication-and-authorisation-with-expressjs

Requiring authentication before allowing user deletion is a necessary step. However, it should be paired with proper authorization checks to ensure that only users with the appropriate rights can perform this action.
Authentication should be depicted as a process of identifying whether user is who they are claim they are. This is very important in regard the application is giving access of its resources.

While Authorization is the process of determining if the user has the right permission to perform operations such as obtaining and even modifying data in the application.
This approaches of course should also be a very good idea, because it provides a layered security model, reducing the risk of unauthorized deletions and ensuring that only legitimate actions are taken.

So, in my opinion, the requirement "“This delete user functionality can be done after authentication” not only is a good idea, but is a must. 
