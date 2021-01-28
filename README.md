Gesture Wheel allows players to have a convenient wheel that provide them the ability to use gestures.

## Permissions
This plugin uses Oxide's permission system. To assign a permission, use oxide.grant <user or group> <name or steam id> <permission>. To remove a permission, use oxide.revoke <user or group> <name or steam id> <permission>.

    gesturewheel.use -- Required to use Gestures (if enabled)

## Configuration
The settings and options for this plugin can be configured in the GestureWheel.json file under the oxide/config directory. The use of a JSON editor or validation site such as jsonlint.com is recommended to avoid formatting issues and syntax errors.

```json
{
  "Command": "gestures",
  "Use Permission": false,
  "Button Radius": 100,
  "Close Button Color": "#FFB6B3DE",
  "Gesture Button Color": "#FF6666DE",
  "Gesture Button Size": 50,
  "Gestures": [
    {
      "Gesture Name": "wave",
      "Image": "https://i.imgur.com/pB3iZer.png"
    },
    {
      "Gesture Name": "victory",
      "Image": "https://i.imgur.com/PLbSgED.png"
    },
    {
      "Gesture Name": "shrug",
      "Image": "https://i.imgur.com/A3hHcgV.png"
    },
    {
      "Gesture Name": "thumbsup",
      "Image": "https://i.imgur.com/yWuhCMu.png"
    },
    {
      "Gesture Name": "chicken",
      "Image": "https://i.imgur.com/Qxhjf6N.png"
    },
    {
      "Gesture Name": "hurry",
      "Image": "https://i.imgur.com/vVKVeha.png"
    },
    {
      "Gesture Name": "whoa",
      "Image": "https://i.imgur.com/AFeGOrK.png"
    }
  ]
}
```

## Preview
![](https://i.imgur.com/PGvdmqZ.png)

## Credits
    Tricky - Maintenance up to 0.1.3
    Mevent - Initial development.
