The bridge Module
=================

The bridge module allows two channels to be bridged.
You can see the bridging in action on our IRC channel (#mana on a [supported network]).

We currently bridge both normal messages and actions in the following formats:

| Type    | Format                                  | Example                      |
| ------- | --------------------------------------- | ---------------------------- |
| message | `[%primary_user_mode%%name%] %message%` | `[@Z750] looks pretty clear` |
| action  | `%name% %action%`                       | `jamierocks is the best`     |

[supported network]: /about/networks/
