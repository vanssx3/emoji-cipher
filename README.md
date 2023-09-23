A dumb cipher that encrypts your text into emojis... Nobody asked for this. Sorry.

Written horribly in TypeScript.


You actually have to have some sort of emojis configured on your system for this to work properly.
Most systems should already have some type of emojis installed but if they don't then I'd recommend
installing the noto-fonts-emoji for your distro.


By default the supported characters include:
"abcdefghijklmnopqrstuvwxyz 0123456789"
(Capital letters work too but they are automatically converted to lowercase letters with .toLowerCase())
To add or change supported characters, add a different character to the index of alphabetLetters[]
that corresponds with the index of the emoji in alphabetEmojis[] you want it to encrypt to.


By defualt the supported emojis include:
"😦👶😭😈🤯🍉☠️🔥🧐🤤🥶😜🤑😡😮🐱🤔🥹😴🫠🥳🥸🥵🤬👽😸🫥👿😳🥺🤧🤢🤭🥲😂🤐😶‍🌫️"
To add or change supported emojis, add a different emoji to index of alphabetEmojis[] that
corresponds with the index of the character in alphabetLetters[] you want it to
encrypt to.


If you wanna use this for literally anything feel free to but it'd be cool if you credited me 😁
