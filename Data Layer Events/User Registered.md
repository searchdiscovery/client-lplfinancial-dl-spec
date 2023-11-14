# User Registered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Registered",
    "user": {
        "loginStatus": "<loginStatus>",
        "registrationType": "<registrationType>",
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.registrationType|string|Describes the thing that was registered for |account, loyalty program, event, sweepstakes, warranty|||||||
|user.system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||



