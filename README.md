# polymorphic-stacks-network
polymorphic stacks layer 2 address bound to more than one mainnet coin using the same stacks address

# proposal for design

```
i realize how it's possible to have one stacks address between more than one
network as a theory

the stacks address protocol should use an inscription to tie more than one
public address and more than one private address and more than one wif key
to the same stacks address...

the inscription would would have a public view and a private view for the
stacks address

the public view would be the mainnet public addresses that are viewable by
anyone looking at the public stacks inscription

the private view of the stacks inscription would be accessible with a pass key
that is generated when the stacks address is created


so a user can access the private view of the stacks inscription using a passkey
that is generated when the stacks address is created and the private view of the
inscription would reveal all of the mainnet private keys and mainnet wif keys
that are bound and intertwined with the stacks address

this way a stacks address could be polymorphic and one stacks address could be
imported to more than one different type of mainnet wallet to be used

 like a bridge almost
all it takes it upgrading the existing stacks address but keeping the same encoding
of the actual stacks address

that's what I propose to the stacks developer team and network

(the private view of the stacks address inscription would be encrypted using openssl)
because if anyone tried to view the private view of the stacks inscription without the
passkey it would be encrypted to protect it the only way someone can decode the private
view of the stacks inscription would be with a passkey that carries the openssl private key
to decode it because the private view of the stacks address inscription carries all the
different wif keys to be able to import private key the binding addresses for the different
types of coin networks that it shares
so when using stacks.js packages cli bin.js.......

it does two things

first thing it does is bind more than one address with a public key to the same stacks
address and inscribes that part as an ordinal nft for public view

then the second part takes place in a few seconds of running the script it then takes all
of the private keys and private key wifs and encrypts them with openssl and generates a
random passcode to decode that ssl and gives it to the user

next after that the program then inscribes another ordinal as an encrypted text ordinal
which contains the private view

finally the cli bin.js program makes a third ordinal inscription linking the public view
and the encrypted data containing the users private view data into one ordinal and labels
the start of the ordinal with the stacks address

now if the user needs to retrieve the private view of the ordinal they have a passcode if
the want to reimport one of the many different wif keys into a particular coin wallet
the passcode only decodes the private view of the ordinal only for the user
and this idea could be part of the API for stacks
so wallets and programs can use the stacks multipart ordinal for more than one balance
for sending and receiving between multiple different types of mainnet wallets
Bitcoin Litecoin Dogecoin vertcoin dash etc etc etc
almost any kind of standard utxo QT wallet the stacks address could have many different
network type wif keys for import and bind to QT wallets but only using one stacks address
between all of them


so that it's polymorphic
```
# 02-24-2024
