# loadouts
Custom Tiny Combat Arena (TCA) loadouts

## For Creators
You can add your own loadout here using this format:
```json
{
    "Name": "You can place anything here",
    "Author": "Your Name Here",
    "Description": "Description goes here",
    "Version": "1.0.0-or-anything-you-like",
    // If your aircraft is not officially supported by the game,
    // you need to add this:
    "Aircraft": "Your aircraft name",
    // It is recommended for you to place your custom aircraft name in the "Name" key
    // The rest is like how you do it normally:
    "NormalizedFuel": 0.4,
    "Stores": [
        {
            "Station": 1,
            "Name": "AIM9L",
            "Count": 1
        } // etc.
    ]
}
```
Please do not add `// comment` into your JSON file as JSON itself doesn't support comment that way.