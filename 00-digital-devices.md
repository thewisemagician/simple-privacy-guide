# Your personal device (laptop/tablet/phone etc).

:warning: Warning be aware if you forget your password you can't recover your data.

## TLDR basic:

Enable full disk encryption on all your mobile devices.

* Iphones [1] are by default encrypted
* Android [2] is also by default but, if you have an old device go in settings -> memory -> enable encryption

## TLDR advanced:

Enable encryption on your computer too. The easiest is just to fully encrypt the whole system, once done you won't see any difference.

* Windows 10:
  * The recommended option is to use Veracrypt [3] a powerfull open source encryption tool. If you prefer to use the built in but less secure windows solution called bitlocker just check the option bellow. [You can find Veracrypt on there official webpage](https://www.veracrypt.fr/en/Home.html).
  * If you have Windows 10 Entreprise you can enable Bitlocker, while you don't have to install anything additional software this isn't the recommended option because Bitlocker isn't open source and had several security issues in the past. If you still want to use it, follow [the guide on Microsoft website](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-device-encryption-overview-windows-10)
* MacOSX: They come with a default encryption solution called FileVault. [Check Apple documentation how to enable it.](https://support.apple.com/en-us/HT204837)
* Linux: Check for your distribution documentation how to setup LUKS

## Convenience:

No matter which operating or solution you choose, once enabled you don't have to worry about it anymore. Your daily workflow usage remain virtually unchanged. Be aware if you loose your password you won't be able to access your data. Store it in your password manager (check the next section for more information)


## Why is it important:

By default usually the memory of your device isn't encrypted and if you loose your device it's trivial to recover/steal the data inside. It's especially important when you travel with confidential documents.

## Sources:
* [1] [Is my iPhone encrypted?](https://ioshacker.com/iphone/is-my-iphone-encrypted-everything-you-need-to-know-about-iphone-encryption)
* [2] [New Android Marshmallow devices must have default encryption, Google says](https://nakedsecurity.sophos.com/2015/10/21/new-android-marshmallow-devices-must-have-default-encryption-google-says/)
* [3] [The VeraCrypt Audit Results](https://ostif.org/the-veracrypt-audit-results/)
* [Use FileVault to encrypt the startup disk on your Mac](https://support.apple.com/en-us/HT204837)
* [Data of 43,000 patients breached after theft of unencrypted laptop](https://www.healthcareitnews.com/news/data-43000-patients-breached-after-theft-unencrypted-laptop)
* [NASA suffers major data breach over stolen laptop that wasn’t encrypted](https://nakedsecurity.sophos.com/2012/11/15/nasa-data-breach-stolen-laptop/)
