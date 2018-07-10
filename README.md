Notes

    Important! Make sure you call session_start() before calling the simple_php_captcha() function
    Requires PHP GD2 library
    Backgound images must be in PNG format
    Fonts must be either TTF or OTF
    Backgrounds and fonts must be specified using their full paths (tip: use $_SERVER['DOCUMENT_ROOT'] . '/' . [path-to-file])
    Angles should not exceed approximately 15 degrees, as the text will sometimes appear outside of the viewable area
    Creates a function called simple_php_captcha() in the global namespace
    Uses the $_SESSION['simple-php-captcha'] session variable
