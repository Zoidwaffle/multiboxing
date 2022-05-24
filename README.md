# multiboxing
A few pointers and other things related to multiboxing Azerothcore

## This is super rough for now
More info will get added, for now it might just add a bit of value as inspiration

## Keybindings

It's very important that you set your key bindings so that `Interact With Target` is using `G`. This is used a lot.

## Addons

A few worth mentioning.

I use `Bartender4` for the layout - this allows me to show a ton of buttons on screen.

The healer is using a mouse for most actions. For this I use `Clique` so I can click on portraits for different spells.

`Jamba` is a multiboxing addon that helps changing focus, selling stuff and many many other conveniences as a multiboxer.

## Macros

The use of macros is an important part. To simply copy/paste the ones used for a warlock in this example, you can look into the WTF folder of your game client.

Then copy `Accountname/Charactername/macros-cache.txt` into your `WTF/<account>/<character>/` folder and `Accountname/macros-cache.txt` into `WTF/<account>/`.

## HotKeyNet

To broadcast mouse/keyboard:

https://web.archive.org/web/20200203213430/http://www.hotkeynet.com/p/download.html

### Load the file for settings

The initial file to load into HotKeyNet is `1_priest_4_warlocks.txt`.

Notice that the setup here is for a 3440x1440 monitor with 5 runnins versions of WotLK. You will need to modify this accordingly.

### A few basic keys

`F1-F5` will change the leader of the group as well as rotate what screen is the master.

`g` will make all interact with the target - like a vendor.

`shift+g` will round-robin interact with a target, useful for looting corpses.

`f` all will follow the master.

`wasd` all move in the same direction.

`shift+wasd` only the minions move in a direction.

`alt+wasd` only 2 minions move in a direction.

#### Keys that need a macro to work

For my main, the healer, most keypresses do nothing. So I use macros that ddo nothing just to show the warlock icon for a spell in the right location.

`q` round robin attack with the pet.

`e` round robin call back your pet.

`shift+1` round robin, used for fear to allow chain fearing multiple targets easier.

`1-0`, `shift/alt/ctrl+1-0` will broadcast the key to all, so line up your spells/macros (a few exceptions like `shift+1` is actually round robin).


