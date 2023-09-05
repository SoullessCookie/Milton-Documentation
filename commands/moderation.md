# Moderation



<details>

<summary>Ban</summary>

Used to ban a user from the current server

* **user**: The user to ban -> <mark style="color:red;">Required</mark>
* **reason**: Reason for the ban -> <mark style="color:green;">Optional</mark>

```
Server Only = True
Default Permission = BanMembers
```

</details>

<details>

<summary>Unban</summary>

Used to unban a user from the current server

* **user**: The user to unban -> <mark style="color:red;">Required</mark>
* **reason**: Reason for the unban -> <mark style="color:green;">Optional</mark>

```
Server Only = True
Default Permission = BanMembers
```

</details>

<details>

<summary>Kick</summary>

Used to kick a user from the current server

* **user**: The user to kick -> <mark style="color:red;">Required</mark>
* **reason**: Reason for the kick -> <mark style="color:green;">Optional</mark>

```
Server Only = True
Default Permission = BanMembers | KickMembers
```

</details>

<details>

<summary>Timeout</summary>

Used to timeout a user from the current server

* **user**: The user to time out-> <mark style="color:red;">Required</mark>
* **duration**: Duration of time out (in minutes) -> <mark style="color:red;">Required</mark>
* **reason**: Reason for the timeout-> <mark style="color:green;">Optional</mark>

```
Server Only = True
Default Permission = KickMembers | BanMembers | ModerateMembers
```

</details>

<details>

<summary>Customvoice (Temporarily Disabled)</summary>

```
Server Only = True
Default Permission = 
```

</details>

<details>

<summary>Logs (Temporarily Disabled)</summary>

Toggles event logging on/off

* **switch**: Turns logging on/off -> <mark style="color:red;">Required</mark>
* **log-channel**: Channel to send logged events to -> <mark style="color:red;">Required</mark>

```
Server Only = True
Default Permission = ManageGuild
```

</details>

<details>

<summary>Nuke</summary>

Nukes a channel (not a server nuker).&#x20;

It create a blank replacement channel with no messages, but everything including permissions stays the same.

<pre><code><strong>Server Only = True
</strong>Default Permission = ManageChannels
</code></pre>

</details>

<details>

<summary>Purge</summary>

Purge messages in a channel

* **amount**: Number of messages to purge (including this one) -> <mark style="color:red;">Required</mark>
* **reason**: Reason for the ban -> <mark style="color:green;">Optional</mark>

```
Server Only = True
Default Permission = ManageMessages
```

</details>

<details>

<summary>Rolecleanup (Temporarily Disabled)</summary>

```
Server Only = True
Default Permission = ManageGuild
```

</details>

<details>

<summary>Server-advanced (Temporarily Disabled)</summary>

```
Server Only = True
Default Permission = Administrator
```

</details>
