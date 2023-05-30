#Sending an email to multiple people in a SharePoint Group.

![image](https://github.com/isogunro/power-automate-http/assets/19296277/017e54cd-c636-424a-8782-71cee894eec6)

EXPANDED
![image](https://github.com/isogunro/power-automate-http/assets/19296277/6eef0a26-6f74-4ed0-9757-b2b90da60333)
![image](https://github.com/isogunro/power-automate-http/assets/19296277/4c584e16-aad4-46a7-8d12-008ce514d283)
![image](https://github.com/isogunro/power-automate-http/assets/19296277/47aa08af-9c2c-4db2-8410-7f2a7e2bca75)

  
  
#SCHEMA
`{
    "type": "array",
    "items": {
        "type": "object",
        "properties": {
            "__metadata": {
                "type": "object",
                "properties": {
                    "id": {
                        "type": "string"
                    },
                    "uri": {
                        "type": "string"
                    },
                    "type": {
                        "type": "string"
                    }
                }
            },
            "Alerts": {
                "type": "object",
                "properties": {
                    "__deferred": {
                        "type": "object",
                        "properties": {
                            "uri": {
                                "type": "string"
                            }
                        }
                    }
                }
            },
            "Groups": {
                "type": "object",
                "properties": {
                    "__deferred": {
                        "type": "object",
                        "properties": {
                            "uri": {
                                "type": "string"
                            }
                        }
                    }
                }
            },
            "Id": {
                "type": "integer"
            },
            "IsHiddenInUI": {
                "type": "boolean"
            },
            "LoginName": {
                "type": "string"
            },
            "Title": {
                "type": "string"
            },
            "PrincipalType": {
                "type": "integer"
            },
            "Email": {
                "type": "string"
            },
            "Expiration": {
                "type": "string"
            },
            "IsEmailAuthenticationGuestUser": {
                "type": "boolean"
            },
            "IsShareByEmailGuestUser": {
                "type": "boolean"
            },
            "IsSiteAdmin": {
                "type": "boolean"
            },
            "UserId": {},
            "UserPrincipalName": {}
        },
        "required": [
            "__metadata",
            "Alerts",
            "Groups",
            "Id",
            "IsHiddenInUI",
            "LoginName",
            "Title",
            "PrincipalType",
            "Email",
            "Expiration",
            "IsEmailAuthenticationGuestUser",
            "IsShareByEmailGuestUser",
            "IsSiteAdmin",
            "UserId",
            "UserPrincipalName"
        ]
    }
}
`
