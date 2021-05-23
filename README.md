# cookiebytes
A JavaScript library to manage cookies on client side. I know it is too silly to create a repo, I'm experimenting NPM, that's why.

#Installation

`npm -i cookiebytes --save`

#Usage

```
import {cookiebytes} from 'cookiebytes';

var cb = new cookiebytes();

//to set a cookie of name cookie_name and value cookie_value with an expiration time of 10 days.
cb.set("cookie_name", "cookie_value", "10");

//to retrive thec cookie that you set.
cb.get("cookie_name");

//to delete a cookie.
cb.delete("cookie_name");

```

#Bug Fixes.

v2.0.0 is the bug free version of this library as of 23/05/2021
