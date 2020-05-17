# Seedable Random Avatar Generator

- Forked from https://www.npmjs.com/package/random-avatar-generator

- Generates random avatars from the website https://getavataaars.com/

# Usage

```typescript
import { AvatarGenerator } from 'seedable-random-avatar-generator';

generator = new AvatarGenerator();

// Simply get a random avatar
generator.getAvatar();

// Optionally specify a seed for the avatar. e.g. for always getting the same avatar for a user id.
// Always returns https://avataaars.io/?accessoriesType=Kurt&avatarStyle=Circle&clotheColor=Blue01&clotheType=Hoodie&eyeType=EyeRoll&eyebrowType=RaisedExcitedNatural&facialHairColor=Blonde&facialHairType=BeardMagestic&hairColor=Black&hatColor=White&mouthType=Sad&skinColor=Yellow&topType=ShortHairShortWaved
generator.getAvatar('avatar'); 

```