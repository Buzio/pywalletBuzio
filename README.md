# pywalletBuzio
Pywallet.py branch of Jackjack

I had the problem of recovering the bitcoins of a Bitcoin-QT wallet encrypted by a password 
and the original version of pywallet.py of jackjack didn't work (I don't know why).
I kept a backup of the wallet and the password with which I had encrypted.
Because of my ignorance I could not recover the bitcoins stored there.
Using an electrum-3.3.8 wallet (which allowed me not to download the whole blockchain with Bitcoin core QT) I could load there about 4000 private keys that were originally contained in my wallet. So I transferred the funds to another wallet. To do this, I had to modify jackjack's original pywallet. That's all. I hope it can serve someone like it served me.

Refer to https://bitcointalk.org/index.php?topic=34028.280 to discover how to get yours, about 4000, private keys from wallet dump.

Refer to original jackjack version for dependencies and other info

Notice to the readers ... consider that my changes to the original version were inspired by different posts obtained googling here and there and that I don't know Python...

and more ... consider that I don't know English, everything I wrote was translated by Google Translator. If it is understandable it is thanks to him!
