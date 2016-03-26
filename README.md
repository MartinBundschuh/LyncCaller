# MyTrialWork
Some few code stuff to show a little of my programming skills

In this sample, it is shown how to youse LyncClient to start calls.

The Cass LyncCall:
- Start the Call itself. It is possible to call people within ones contactlist or any other number.
- Group calls are possible.
- All calls are logged in the database (Entity Framework)

The Cass PhoneNumber:
- Is used to pass LyncCall a defined phonenumber syntax.
- Returns a formated phonenumber wich can be used in GUIs.

UnitTests:
- Just a few standard UnitTests.
- Only basic tests to show how to use them.

ExceptionClasses:
- Custom ExceptionClasses for more detailed exception handling.
- Different Exceptions for false e-mail address, phonenumber or lync-call.

Call Logging:
- Calls will be logged in the database.
- Callinformations: From, To, Date/Time, call to user in contactlist.
