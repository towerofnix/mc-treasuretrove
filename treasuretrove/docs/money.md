## Money

**Money** allows mobs to drop emeralds. The amount of emeralds varies depending on the `rolls` of the loot table includer as well as how many mobs the player killer has killed so far.

### Usage

Append this into the `pools` section of your own loot table:

    {
        "rolls": (Rolls),
        "entries": [
            {
                "type": "loot_table",
                "name": "treasuretrove:entitytreasure/money",
                "weight": 1
            }
        ]
    }

Remember that you can use an object `{min:, max:}` instead of a number inside of `rolls`.

Also, you can do this..

    ...
    {
        "type": "empty",
        "weight": (Weight)
    }

..beside the `money` import to decrease the chance of getting money.
