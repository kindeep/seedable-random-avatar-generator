# Random Avatar Generator

- Generates random avatars from the website https://getavataaars.com/

## Usage

### Simple 

```typescript
import { getRandomAvatar } from 'random-avatar-generator';

// Returns get a url for a random avatar
getRandomAvatar();
```

### With a seed

For instance, if you want to generate a random avatar for a user id/email which stays the same each time.


```typescript
import { getRandomAvatar } from 'random-avatar-generator';

// Returns https://avataaars.io/?accessoriesType=Kurt&avatarStyle=Circle&clotheColor=Blue01&clotheType=Hoodie&eyeType=EyeRoll&eyebrowType=RaisedExcitedNatural&facialHairColor=Blonde&facialHairType=BeardMagestic&hairColor=Black&hatColor=White&mouthType=Sad&skinColor=Yellow&topType=ShortHairShortWaved
getRandomAvatar('avatar'); 

```

In the example above, specifying the seed `avatar` results in: -

![avatar](https://avataaars.io/?accessoriesType=Kurt&avatarStyle=Circle&clotheColor=Blue01&clotheType=Hoodie&eyeType=EyeRoll&eyebrowType=RaisedExcitedNatural&facialHairColor=Blonde&facialHairType=BeardMagestic&hairColor=Black&hatColor=White&mouthType=Sad&skinColor=Yellow&topType=ShortHairShortWaved "Avatar with seed 'avatar'")
