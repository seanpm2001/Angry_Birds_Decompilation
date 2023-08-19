# ANGRY BIRDS Decomp

## Usage
You will need to have openssl installed and in your Environment variables.
AND 7z installed.

## Keys

Angry Birds

    Str = USCaPQpA4TSNVxMI1v9SK9UC0yZuAnb2
    
    Hex = 55534361505170413454534E56784D49317639534B39554330795A75416E6232

Angry Birds: Rio

    Str = USCaPQpA4TSNVxMI1v9SK9UC0yZuAnb2

        Hex = 55534361505170413454534E56784D49317639534B39554330795A75416E6232

Angry Birds: Seasons

    Str = zePhest5faQuX2S2Apre@4reChAtEvUt
    
    Hex = 7A65506865737435666151755832533241707265403472654368417445765574

Angry Birds: Space

    Str = RmgdZ0JenLFgWwkYvCL2lSahFbEhFec4
    
    Hex = 526D67645A304A656E4C466757776B5976434C326C5361684662456846656334

Angry Birds: Star Wars

    Str = An8t3mn8U6spiQ0zHHr3a1loDrRa3mtE
    
    Hex = 416E3874336D6E38553673706951307A4848723361316C6F44725261336D7445

Angry Birds: Star Wars II

    Str = B0pm3TAlzkN9ghzoe2NizEllPdN0hQni
    
    Hex = 4230706D3354416C7A6B4E3967687A6F65324E697A456C6C50644E3068516E69

Decrypt:

    openssl enc -aes-256-cbc -d -K [key] -iv 0 -in [name].lua -out [name].lua.dec

Encrypt:

    openssl enc -aes-256-cbc -e -K [key] -iv 0 -in [name].lua.dec -out [name].lua
