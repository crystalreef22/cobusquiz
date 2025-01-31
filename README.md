# Cobusquiz

**This is currently under development**

**This is NOT a discord bot**


Complete with "GUI"!

This program pulls quotes from a database of 40000+ quotes. All ciphers for use in the 2020-2021 season, with the exception of keyed monoalphabetic substitution ciphers (K1/K2), have been implemented.

**Disclaimer: This program is only for practice. If you are an event supervisor, tournament director, or any test writer, you may not use Codebuilder to generate tests for use in any sanctioned competition, including invitationals, regionals, or state competitions. In addition, you may not use Codebuilder for any test exchanges, such as SSSS, Captains Test Exchange, or anywhere where the test will be publicly released without my permission.**

If you would like to request new features or report any bugs, feel free to create an issue; however, chances are I won't get to it.

### Commands: ###

    - `c!about` - About Me

    - `c!ays' - As you should 😌

    - `c!customQ` - Lists possible question types for `c!genCustom`.
   
    - `c!fetch \[Name]` - `c!fetch example` - Fetches a test with a given name.

    - `c!gen \[Name] \[Preset]` - `c!gen example 1` - Generates a test with a given preset.
    
    - `c!genCustom \[Name] \[Custom Question List]` - `c!gen example "1 2,3 1,8 0" - Generates a test with a list of question types.
    
    - `c!presets` - Lists possible presets for `c!gen`.
    
    - `c!washed` - Washed

### Presets ###
Currently, there are four presets:

1.  **All Types** - 33 Questions + Timed - Includes one of each cipher type.
    - 1 Timed Question
    - 1 Unhinted Aristocrat
    - 1 Character-Hinted Aristocrat
    - 1 Word-Hinted Aristocrat
    - 1 Unhinted Patristocrat
    - 1 Character-Hinted Patristocrat
    - 1 Word-Hinted Patristocrat
    - 1 Affine Decode
    - 1 Affine Encode
    - 1 Affine Cryptanalysis
    - 1 Caesar Decode
    - 1 Caesar Encode
    - 1 Vigenere Decode
    - 1 Vigenere Encode
    - 1 Vigenere Cryptanalysis
    - 1 2x2 Hill Compute Decryption Matrix
    - 1 2x2 Hill Decode
    - 1 2x2 Hill Encode
    - 1 3x3 Hill Decode
    - 1 3x3 Hill Encode
    - 1 Xenocrypt
    - 1 Bacon Letter for Letter
    - 1 Bacon Sequential
    - 1 Bacon Words
    - 1 Morbit Decrypt
    - 1 Morbit Cryptanalysis
    - 1 Pollux Decrypt
    - 1 Pollux Cryptanalysis
    - 1 Porta Encrypt
    - 1 Porta Decrypt
    - 1 Porta Cryptanalysis
    - 1 Rail Fence w/ 2 Rails
    - 1 Rail Fence w/ 4 Rails
    - 1 Rail Fence w/ Range
   
2.  **National Level Test** - 32 Questions + Timed - National level test, with random modes of questions.
    - 1 Timed Question
    - 10 Unhinted Aristocrats
    - 1 Unhinted Patristocrat
    - 1 Character-Hinted Patristocrat
    - 1 Word-Hinted Patristocrat
    - 2 Affine 
    - 1 Caesar Decode
    - 1 Caesar Encode
    - 2 Vigenere
    - 3 Hill
    - 2 Xenocrypt
    - 2 Bacon
    - 3 Morse
    - 1 Porta
    - 1 Rail Fence w/ >= 5 rails
    - 1 Rail Fence w/ Range

3.  **Regional Level Test** - 22 Questions + Timed - Regional level test, with random modes of questions.
    - 1 Timed Question
    - 4 Unhinted Aristocrats
    - 1 Character-Hinted Aristocrat
    - 1 Word-Hinted Aristocrat
    - 1 Unhinted Patristocrat
    - 1 Word-Hinted Patristocrat
    - 1 Affine Decode
    - 1 Caesar Decode
    - 1 Vigenere Decode
    - 1 2x2 Hill Decode
    - 2 Encode (Affine/Caesar/Vigenere/2x2 Hill)
    - 1 Xenocrypt
    - 2 Bacon
    - 1 Morbit Decrypt
    - 1 Pollux Decrypt
    - 1 Porta
    - 1 Rail Fence w/ >= 5 fails
    - 1 Rail Fence w/ Range
    
4.  **Aristo Spam** - 10 Questions + Timed - 10 Unhinted Aristocrats.
    - 1 Timed Question
    - 10 Unhinted Aristocrats
    
5.  **Patristo Spam** - 10 Questions + Timed - 10 Unhinted Patristocrats.
    - 1 Timed Question
    - 10 Unhinted Patristocrats
    
6.  **Custom** - Custom made test.
