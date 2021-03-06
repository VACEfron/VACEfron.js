Documentation of the wrapper's methods.

Properties in *italics* are not required. All methods return `Promise<Buffer>`.

- [Methods](#methods)
  * [carReverse()](#carreverse)
  * [distractedBoyfriend()](#distractedboyfriend)
  * [ejected()](#ejected)
  * [emergencyMeeting()](#emergencymeeting)
  * [firstTime()](#firsttime)
  * [grave()](#grave)
  * [iAmSpeed()](#iamspeed)
  * [iCanMilkYou()](#icanmilkyou)
  * [heaven()](#heaven)
  * [rankCard()](#rankcard)
  * [stonks()](#stonks)
  * [tableFlip()](#tableflip)
  * [water()](#water)
  * [wide()](#wide)

## Methods
### carReverse()
**Parameters**: 

text `string` | The text for the car reverse meme.

### distractedBoyfriend()
**Parameters**: 

boyfriendAvatarURL `string` | Avatar URL for the boyfriend's face.

womanAvatarURL `string` | Avatar URL for the woman's face.

girlfriendAvatarURL `string` | Avatar URL for the girlfriend's face.

### ejected()
**Parameters**:

name `string` | Name of the player.

*wasImposter* `boolean` | Whether the player is the imposter.

*color* `black|blue|brown|cyan|darkgreen|lime|orange|pink|purple|red|white|yellow` | The color of the player.

### emergencyMeeting()
**Parameters**:

text `string` | The text for the emergency meeting meme.

### firstTime()
**Parameters**:

avatarURL `string` | Avatar URL for the first time meme.

### grave()
**Parameters**:

avatarURL `string` | Avatar URL for the grave.

### iAmSpeed()
**Parameters**:

avatarURL `string` | Avatar URL for the I am Speed meme.

### iCanMilkYou()
**Parameters**:

faceAvatarURL `string` | Avatar URL for the face.

cowAvatarURL `string` | Avatar URL for the cow.

### heaven()
**Parameters**:

avatarURL `string` | Avatar URL to be in heaven.

### rankCard()
**Parameters**:

username `string` | The username of the user.

avatarURL `string` | Avatar URL of the user.

customBackgroundURL `string` | Custom background for the rankcard. Pass empty string for none.

level `number` | The level the user is at.

rank `number` | The ranking of the user.

currentXP `number` | The amount of XP the user currently has.

nextLevelXP `number` | XP required to reach the next level.

previousLevelXP `number` | XP required to reach the user's current level.

xpColor `string` | The color (hex) of the XP bar.

isBoosting `boolean` | Whether a boost badge will be displayed next to the user's name.

### stonks()
**Parameters**:

avatarURL `string` | Avatar URL for the Stonks meme.

### tableFlip()
**Parameters**:

avatarURL `string` | Avatar URL for the tableflip meme.

### water()

text `string` | Text for the water meme.

### wide()

imageURL `string` | Image URL to widen.