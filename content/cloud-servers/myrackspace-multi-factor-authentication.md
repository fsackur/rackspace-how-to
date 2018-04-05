---
permalink: myrackspace-multi-factor-authentication/
audit_date: '2018-03-30'
title: MyRackspace two-factor authentication
type: article
created_date: '2014-07-14'
created_by: Rackspace Support
last_modified_date: '2018-03-30'
last_modified_by: Cat Lookabaugh
product: Cloud Servers
product_url: cloud-servers
---

Multi-factor authentication uses an extra device, like a mobile phone, to
provide an additional layer of security when you access your account.
Multi-factor authentication is a significant security improvement over
using a password alone. This article explains how to manage multi-factor
authentication for your MyRackspace account from the
[MyRackspace](https://my.rackspace.com/portal/auth/login?targetUri=%2Fhome) portal.

**Note:** You must be an administrative user to manage multi-factor
authentication for your MyRackspace account.

### Set up multi-factor authentication for users

An administrative user of the account can use the **Require Multi-factor**
option to decide whether to make multi-factor authentication a requirement for
all users or to allow users to choose if they want to use multi-factor
authentication.

1.  Log in to the [MyRackspace portal](https://my.rackspace.com/).

2.  In the top menu bar, click **Account** and then select **User
    Management**.

3.  Click **My Multi-Factor Devices**.

4.  Next to the **Require Multi-Factor** label, click the pencil icon and
select one of the following options:

    -  **Required for all users on this account** - Makes multi-factor
    authentication a requirement for all users on your account. Setup
    must take place at each user's next login.

    -  **Optional per user** - Makes multi-factor authentication optional for
    all users on your account. Users who want to use multi-factor
    authentication are prompted to register a paired mobile passcode or
    SMS-capable device at their next login.

7.  Click **Save Setting**.

### Register a device after multi-factor authentication is enabled for your account

If multi-factor authentication is enabled for your user account, you must
register a new device to pair with your account by using
these steps:

1.  Log in to the [MyRackspace portal](https://myrackspace.com).

2.  In the top menu bar, click **Account** and then choose **User Management**.

3.  Click **My Multi-Factor Devices**. Now, decide whether you want to use the
    **Mobile Passcode** or **SMS** authentication method.

4.  If you choose the *Mobile Passcode* authentication method, follow these steps:

    a. Click **Add** next to the **Mobile Passcode** option.
    b. Enter a device nickname and click **Add Device**.
    c. Scan the displayed QR code by using the authentication application on
       your device.
    d. To complete the verification of your device, enter the code that the
       authentication application provides after scanning the QR code.

5.  If you choose the SMS authentication method, follow these steps:

    a. Click **Add** next to the **SMS** option.
    b. Enter the phone number of your SMS-capable device and click **Add SMS Device**.

       After you click **Add SMS Device**, the Identity service sends an SMS
       text message with a four-digit PIN to the specified phone.

    c. To complete the verification of your device, enter the 4-digit PIN code
       from the text message that you receive and click **Verify SMS Device**.

6.  After your device is verified by either PIN code or QR code, you are granted
    access to MyRackspace.

### Log in with multi-factor authentication

After you register a paired device with your account and log in to the
MyRackspace portal with your username and password, you are prompted for a
verification code to complete multi-factor authentication. If you have a
mobile passcode device paired, enter the code generated by the mobile passcode
application. If you have an SMS device paired, enter the 7-digit verification
code sent via SMS text message after you logged in to the
[MyRackspace portal](https://myrackspace.com).

### Manage your multi-factor devices

Users are allowed multiple mobile passcode devices and one SMS device for
multi-factor authentication. To manage the devices that you use with
multi-factor authentication, use the following steps:

1.  Log in to the [MyRackspace portal](https://myrackspace.com).

2.  In the top menu bar, click **Account** and then choose **User Management**.

3.  Click **My Multi-Factor Devices**.

4.  On the **My Multi-Factor Devices** page, choose one of the following options:

    -   Click **Remove all devices** at the top of the page to remove any
        existing devices.
    -   Click **Manage** next to the **Mobile Passcode** option to manage
        existing mobile passcode devices.
    -   Click **Delete** next to the **Mobile Passcode** option to delete a
        mobile passcode device.
    -   Click **Verify** next to the **Mobile Passcode** option to continue
        setting up a mobile passcode device.
    -   Click **Add** next to the **SMS** option to add a new SMS device.
    -   Click **Delete** next to the **SMS** option to delete an SMS device.
    -   Click **Generate Bypass Codes** to generate from one to ten
        bypass codes to use in place of your device.


### Troubleshoot multi-factor authentication problems

This section describes a few common problems that you might encounter when
you set up multi-factor authentication and some basic troubleshooting
steps that can help you overcome them.

#### Invalid phone number

When trying to register a mobile device, you might receive an error
indicating an invalid phone number. Confirm that you have entered a valid
10-digit phone number correctly with no extra characters or spaces.

#### Verify device - Invalid PIN

When attempting to verify your mobile device, you might receive an error
that the PIN entered is incorrect. Confirm that you have entered the correct
4-digit PIN received via SMS text message.

#### MyRackspace account locked

After six failed attempts to the [MyRackspace portal](https://myrackspace.com),
the account is locked. Failures can result from an invalid username or password
or from an invalid multi-factor authentication code.

A user with administrator privileges is required to unlock the account. See
the following section for instructions.

#### Unlock a user account

Follow these steps to unlock a user account:

1.  Log in to the [MyRackspace portal](https://myrackspace.com) as an
    administrator.

2.  Select **Account > User List**.

3.  Locate the locked user and open the user's account record.

4.  From the **Actions** menu, select **Unlock User**.

    A green banner is displayed, stating that the user account was
    successfully unlocked.

#### Generate a temporary passcode

Follow these steps to generate a temporary passcode for a user.

**Note:** An account must be unlocked for this item to be displayed in
the **Actions** menu.

1.  Log in to the [MyRackspace portal](https://myrackspace.com) as an administrator.

2.  Select **Account > User List**.

3.  Locate the user and open the user's account record.

4.  From the **Actions** menu, select **Send Temporary Code**.

    A green banner is displayed, stating that the temporary code has
    been sent to the indicated device. The code is valid for
    five minutes.

#### Multi-factor authentication links do not appear in the MyRackspace portal

If you do not see the multi-factor authentication links in the menu bar of
the MyRackspace portal, the account might not be enabled for multi-factor
authentication, or the multi-factor authentication system might be unavailable
because of maintenance or service interruption.