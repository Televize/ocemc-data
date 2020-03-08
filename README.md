## OCEMC Data
Data from the Minecraft server tracker at https://ocemc.pro/ from ***September 24th 2019*** to ***February 28th 2020***

## Format
The data is in the following format, taking into account:
- Timestamp is the value returned by JavaScript `Date.now()`
- Playercount is the server's online player count returned in the [Server List Ping](https://wiki.vg/Server_List_Ping)
- A `-1` value for playercount means the ping failed, most likely from timing out.

```
{
"timestamp1": playercount1,
"timestamp2": playercount2,
...
}
```

## Credit Me
I do not mind what you do with this.
If you make anything with this, at the very least link this repository.
