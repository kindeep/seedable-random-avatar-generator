# Seedable Random Avatar Generator

- Forked from https://www.npmjs.com/package/random-avatar-generator

- Generates random avatars from the website https://getavataaars.com/

# Usage

```typescript
import { getRandomAvatar } from 'seedable-random-avatar-generator';

// Returns get a url for a random avatar
getRandomAvatar();

// Optionally specify a seed for the avatar. e.g. for always getting the same avatar for a user id.
// With seed as 'avatar', always returns https://avataaars.io/?accessoriesType=Kurt&avatarStyle=Circle&clotheColor=Blue01&clotheType=Hoodie&eyeType=EyeRoll&eyebrowType=RaisedExcitedNatural&facialHairColor=Blonde&facialHairType=BeardMagestic&hairColor=Black&hatColor=White&mouthType=Sad&skinColor=Yellow&topType=ShortHairShortWaved
getRandomAvatar('avatar'); 

```