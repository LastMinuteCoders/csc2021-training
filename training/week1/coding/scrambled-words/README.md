# Scrambled words

R-boy is convinced that something’s going on! The website contains a games area: he's sure that it contains hidden messages. The first game is scrambled words. Help him find the hidden secret code!

You have to find the original unscrambled words, which were randomly taken from a dictionary.

Note:

The SHA-256 hash of the concatenated unscrambled words will be *the content* of the flag and it needs to be converted to lowercase.

To get the complete flag, insert the lowercase string obtained between “{FLG:” and “}” without any blank space after the “:” and before the “}”.

Consider UTF-8 as the character encoding. Unscrambled words must have the same order of scrambled ones and they must be concatenated without spaces.

## Resolve

Use the _.ipynb_ file to resolve this enigma. I converted the scrambled and the dictionary words to numbers and then used those to find the corrects words. Then by passing any online SHA256 converder you get the **FLAG**:

{FLG:70c42b6d6818f3141865f10d1608f7a9763138554f6d5120662222189854231c}
