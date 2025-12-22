---
title: 📝 Register a new user
description: OpenUEM User registration
keywords:
  [
    IT assets,
    inventory,
    openuem,
    uem,
    rmm,
    console,
    sign in,
    register,
    unified endpoint manager,
    remote monitoring and management,
  ]
---

# Register

Several users can get access to the console. An administrator can create new users from the **Admin** -> **Users** section or users can sign in and wait for the administrator to admit the sign in request. This page describes the latter.

In the log in page, you can find an icon to register.

![Register button](/img/console/register_button.png)

A register form is displayed, where you must fill in the fields. You can select the authentication type that you’ll use (password, digital certificate, OIDC). 

![Register form](/img/console/register_form.png)

Once the form is validated, you can submit it, and you’ll receive a message telling you that you must wait until an administrator approves your request. 

![Register button](/img/console/confirm_email_warning.png)

Starting with version 0.10.0, you can hide the register button from the log in page. You can do it from the **Authentication** tab in the **Global** config view.

![Show or hide the register button](/img/console/show_register.png)
