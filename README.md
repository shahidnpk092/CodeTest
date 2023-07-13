# CodeTest

Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php


Some Important Points:
1) Validation missing for validate request data
2) Do not use ENV variables directly in controller and repo
3) Write a private funcation for reuse code instead of writing it's code over and over again
4) For send emails, always use laravel jobs for speedup current process
5) For SMS notification, make a SMS Trait for use in multiple repositories