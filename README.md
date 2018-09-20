# laravel_api_logger_middleware
Allow simple logging of laravele request response.

You can simply copy paste the above files to your laravel project and ready to go.
(Please make sure you create a table before proceed and register middleware :P) 

# Follow up steps!

1) Create a model provided and respective table in database.

columns :

 id | client_ip | status_code | user_token | url | user_id | user_name | request_data | response_data | created_at | updated_at


2) Create middleware and register it in app/Http/Kernel.php file.
   (copy paste the content of above file to it simply use the one above.)

3) Apply the middleware in your api routes. 
