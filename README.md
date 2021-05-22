# cookiebytes
A JavaScript library to manage cookies on client side. I know it is too silly to create a repo, I'm experimenting NPM, that's why.

#Installation

`npm -i cookiebytes --save`

#Usage

```
import {CookieBytes} from 'CookieBytes';

//to set a cookie of name cookie_name and value cookie_value with an expiration time of 10 days.
CookieBytes().set("cookie_name", "cookie_value", "10")l

//to retrive thec cookie that you set.
CookieBytes().get("cookie_name");

//to delete a cookie.
CookieBytes().delete("cookie_name");

```
