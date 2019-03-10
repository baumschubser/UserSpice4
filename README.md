# UserSpice4
## SQLite flavour

 UserSpice 4 is a complete OOP PDO PHP User Management System.  Full details, documentation, walkthroughs, and forums can be found at UserSpice.com.

 **This a fork from [UserSpice 4.4](https://github.com/mudmin/UserSpice4/) that uses a SQLite file instead of MySQL as database.**

### Requirements

Make sure you have all requirements installed:

* PHP >= 5.6.0
* PHP XML module installed
* PHP PDO module installed
* PHP SQLite module installed

## Installation
The installation wizard is removed in this fork. But since we do not have to setup a MySQL database connection, all is left to do is setting the timezone.

1. Clone the repository or copy all files to a directory.
* Make sure the SQLite file `userspice.sqlite` is writable for the webserver.
* Edit the file `init.php`. In the line second to last, edit the timezone according to [this list](https://secure.php.net/manual/en/timezones.php), e.g. `$timezone_string = 'America/Caracas';`

## Thank you
Thank you thank you thank you to [mudmin](https://github.com/mudmin) for Userspice.
