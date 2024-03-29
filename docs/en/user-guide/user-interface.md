# User Interface (UI)

The user interface (UI) includes all visible elements users see and interact with while using TreoPIM. This chapter describes all the main elements of user interface, which are the same for all entities in the system, as well as gives details on how to perform common tasks or operations in the system.

Please, make sure to contact your administrator in order to have access to a whole set of options described in this user guide. 

The following elements make up the TreoPIM user interface:

- [**Navigation Menu**](#navigation-menu) – to navigate through available entities.
- [**Taskbar**](#taskbar) – to help the user interact with the TreoPIM system in a more efficient way; additional information or actions are displayed here. 
- [**Search and Filtering Panel**](./search-and-filtering.md) – to search and filter within one entity or its related entities.

Within the TreoPIM system your information may be presented in various ways:

- [**List View**](./views-and-panels.md#list-view) – to view the lists of entity records.
- [**Plate View**](./views-and-panels.md#plate-view) – to view entity records as plates.
- [**Detail View**](./views-and-panels.md#detail-view) – to view the entity record details.
- [**Create View**](./views-and-panels.md#create-view) – to create a new entity record in the main window.
- [**Edit View**](./views-and-panels.md#edit-view) – to edit the entity record.
- [**Quick Detail View (pop-up)**](./views-and-panels.md#quick-detail-view-small-detail-view) – to view the record details in the pop-up window.
- [**Quick Edit View (pop-up)**](./views-and-panels.md#quick-edit-view) – to edit the record detail in the pop-up window.
- [**Quick Create View**](./views-and-panels.md#quick-create-view) – to create a new entity record in the pop-up window.

## Navigation Menu

The navigation menu in the default TreoPIM theme is the menu placed on the left side of your user interface. It allows you to open list views for all entities in the system.

The navigation menu can be configured by your administrator according to your needs.

Each user can customize his/her own navigation menu in the `User Interface` section of the user ["Preferences"](#user-preferences) page:

![Navigation Menu Cfg](../../_assets/user-interface/navigation-user-cfg.jpg)

Here select the `Custom Tab List` option and add the desired tabs using the `Add` button.

## Taskbar

Taskbar is a top panel of the TreoPIM user interface:

![Taskbar](../../_assets/user-interface/taskbar.jpg)

A taskbar consists of a global search field and some functional icons that help you work and collaborate within the TreoPIM system.

### Global Search

You can search all the records existing in the TreoPIM system using the global search functionality. Use the search form on the taskbar for it:

![Global Search](../../_assets/user-interface/global-search.jpg) 

### Desktop Notifications

TreoPIM uses two types of notifications: email notifications and system notifications (desktop notifications). Generally, email and desktop notifications are configured globally, for all users.

User can receive notifications in case when:
- a record is assigned to him;
- changes are made to the record he is following.

![Desktop Notifications](../../_assets/user-interface/desktop-notifications.jpg)

To view the notification details, click `View List` in the upper right corner of the `NOTIFICATIONS` panel.

### Queue Manager

Queue Manager is opened in the pop-up window for each operation executed displaying its status and a progress circle for the currently run operation:

![Queue Manager](../../_assets/user-interface/queue-manager.jpg)

In the Queue Manager you will see the most recent TreoPIM operations, which were executed in the background mode or run automatically via scheduled jobs, i.e  latest imports and exports. To view the details of the performed operations, click `View List` in the upper right corner of the Queue Manager.

### Quick Create

To create new records from anywhere, click the quick create button located in the upper right corner of the taskbar on any TreoPIM page and choose the entity for the record to be created:

![Quick Create](../../_assets/user-interface/quick-create.jpg)

The [quick create view](./views-and-panels.md#quick-create-view) page will be opened.

## Breadcrumb Navigation

TreoPIM comes with breadcrumb navigation on each page in the system. Breadcrumb navigation is a form of a path-style clickable navigation, which links the user back to the prior website page in the overall online route. It reveals the path the user took to arrive to the given page. The `>` symbol separates out the hierarchical search order from beginning to end and may look something like:
`Home Page > Section Page > Subsection Page`

## User Menu

Click the hamburger icon in the upper right corner of the user interface to open the user menu:

![User Menu](../../_assets/user-interface/user-menu.jpg)

### User Account

There are many configuration options available to users once logged into the system. Click your username to open your user account.

By default, your **user profile** is opened:

![User Account](../../_assets/user-interface/user-account.jpg)

#### User Profile

Click the `Access` button to view your current permissions within the TreoPIM system on the scope and field levels in the pop-up window that appears:

![User Access Window](../../_assets/user-interface/user-access-window.jpg)

*Access rights are modified by the administrator only.*

Click the actions button to see the list of actions available for the currently open entity:

![User Actions Menu](../../_assets/user-interface/user-actions-menu.jpg)

To change your user password, select the corresponding option in the actions drop-down menu and complete the operation on the "Change Password" page:

![User Password Change](../../_assets/user-interface/user-change-paswd.jpg)

If you forget your password, it can be recovered using the `Forgot Password?` link on the TreoPIM login page.

You can also manage your team and access control, if you have the corresponding permissions.

At the bottom of the screen you will see your personal activity stream:

![UA stream](../../_assets/user-interface/user-account-stream.jpg)

You can manage the types of activity to be displayed here in the corresponding actions menu:

![UA stream menu](../../_assets/user-interface/user-account-stream-menu.jpg)

Recent updates and comments about certain entity records are displayed on the activity stream panel, making it an excellent way of keeping track of the changes in TreoPIM. You can also create a post in the corresponding message box right on the `STREAM` panel.

#### User Preferences

If you want to edit your user preferences, select the `Preferences` option from the user drop-down menu or use the `Preferences` button on the user profile page and make the desired changes on the "LOCALE", "MISC", "USER INTERFACE", "SMTP" panels of the current user page.

To reset preferences to default, please click the `Reset to default` button.

 ![User Interface Settings](../../_assets/user-interface/user-preferences.jpg)

#### Email Accounts

TreoPIM works with IMAP mail accounts, with or without SSL protection. TreoPIM is able to send emails via SMTP Server, also with or without SSL protection, which can be enabled or not.

To open your personal email accounts, click the `Email Accounts` button on the user profile page; the list of the existing accounts, if any, will be displayed on the "Personal Email Accounts" page:

![Email Accounts](../../_assets/user-interface/email-accounts.jpg) 

Each user can have one or more private email accounts that can be viewed, edited or removed right from the "Personal Email Accounts" list view page:

![Email Actions](../../_assets/user-interface/email-actions.jpg)

##### Creating

Click the `Create Email Account` button; the following creation page will open: 

![Create Personal Email Accounts](../../_assets/user-interface/personal-email-accounts-create.jpg)

Here and fill in the required fields (marked with an asterisk) and configure the IMAP, SMTP options available in accordance with your email account server.

#### External Accounts

Currently not available.

#### User Interface Settings

Select the `Custom Tab List` checkbox to enable a custom navigation menu. Using the `Add` button select the entities to be linked to your custom [navigation menu](#navigation-menu).

[Dashboard](./dashboards-and-dashlets.md#dashboards) layout and [dashlet](./dashboards-and-dashlets.md#dashlets) settings are also available for editing on the `USER INTERFACE` panel:

![Dashboard settings](../../_assets/user-interface/ui-dashboard.jpg) 

The same options are available on the TreoPIM starting page:

![PIM dashboard editing](../../_assets/user-interface/pim-dashboard-edit.jpg)

Click the editing button and enter a name for your dashboard in the corresponding field of the "Edit dashboard" pop-up and hit `Enter`:

![Dashboard editing](../../_assets/user-interface/ui-dashboard-edit.jpg)

Click the `Save` button to finish creating the new dashboard. Use the same pencil button if you wish to rename or remove the existing dashboards.

Using the `+` button add as many dashlets as you need. The added dashlets can be resized using the double-headed arrow in the bottom right corner of each dashlet. Click `Edit` to modify the added dashlets, if needed.

To rearrange your dashboard view, drag-and-drop the dashlets right on the `USER INTERFACE` panel:

![Dashlets order](../../_assets/user-interface/dashlets-order.jpg)

Alternatively, you can customize your [dashboard](./dashboards-and-dashlets.md#dashboards) view in the same way on the TreoPIM starting page.

### Last Viewed

Select the `Last Viewed` option from the main drop-down menu to see the history of your visited pages within the TreoPIM system:

![Last viewed](../../_assets/user-interface/last-viewed.jpg)

### Clear Local Cache

TreoPIM is a single page application (SPA). To improve the page loading time, it actively uses cache for content as well for the user interface.

If you want to be sure in getting the latest information and application functions, please use the `Clear Local Cache` option from the main drop-down menu.

