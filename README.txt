
bad practice : to send push notification in repository class
good practice : create separate class to send push notifications transfer business logic there

bad practice  :  to save data in DB without validation like ($request->all())
good practice : apply proper validation send save only desired data in the DB

bad practice  : make to user strict type
good practice  use  === instead of ==


keys points :
Declare return type
Use if block with {} even its single liner (optional)
use ternary operator in case of if else


FINAL THOUGHTS
There were alot of method which seemed un-used but refactor them too !
Use single responsibility in class
Use model relationship scope method , type casting , fillable event observers and so on
if method is getting to long i call it terrible code I would like to decouple the logic
in separate classes 