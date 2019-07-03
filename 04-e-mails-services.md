# E-Mails (custom domain)

E-Mails are a complicated topic so it's divided into two sub chapters. They are complementary but independent. You can choose to follow both or one of them. The first chapter deals with custom domain and the second with mail encryption.

## TLDR basic:

Switch to a custom domain. Currently it's likely you are using a mail from an external mail provider. You can keep the mail provider but switch to your custom mail domain. I know it's sounds crazy and difficult to start (and you will have to pay a little bit) with this but it will simplify your life in the future.

* Register a domain
* Point the MX entries to your current mail provider
* Start to change all your mails to your new domain

## TLDR advanced:

Do all the parts from the TLDR basic but create one mail per account (something like google@yourdomain.com, microsoft@yourdomain.com, etc). This is one of the most powerful feature to have a custom domain because you can turn tracking around and now you know exactly who is writing which mails.

If you don't want to go with a custom domain, some mail providers allow you to create alias usually like yourname+google@your-mail-service.com. While you loose the benefit of freedom given by a custom domain you can still know where a mail comes from.

When you think about it it's quite empowering and gives you back the control over your accounts/data!

## Convenience:

You can now easily switch from one mail provider to the other. You aren't bound to a service and you recover your freedom to choose without having to change your mail every single time you want to switch to another provider.

The ability to track what is done to your mail and know if one of your account data was sold is also a big plus (if you choose to do the advanced setup).

You have also brand recognition (it's usually better to have your own domain. It gives credibility over a generic e-mail hosting service).

## Why is it important:

Regardless of the convenience of having the possibility to switch at anytime it's also a guarantee for your independence. You could be banned from a provider and loose all your mails, and yes this happened and you have limited chance to get your account back. You shouldn't let yourself becoming vulnerable to a scenario like this.

# E-Mails (E2E encryption)

## TLDR basic:

Switch to a secure mail provider which offers native E2E encryption like ProtonMail or Tutanota. I would privilege ProtonMail since their data center are outside of EU and US, and they use the standard PGP.

## TLDR advanced:

Warning: the advanced is actually harder and more complicated to maintain than going with the basic.

Setup PGP to encrypt and digitally sign your mails. You can use something like mailvelope, and keep your current solution.

Convenience:

I would strongly recommend to use the first basic setup since it brings encryption without you doing much. You just continue to send your mails as before. If you created your own domain like in the previous chapter switching it is trivial (simply change the MX records).


Why is it important:

It might surprise you but E-Mails aren't really secure. They aren't encrypted and it's trivial to spoof fields like FROM or SENDER. And while you have nothing to hide and nothing to fear what you write to your friends and family is NONE of Google business!


Finally, e-mails is done. This is one of the most time consuming section. Take your time and do it in chunks. Don't burn yourself with this.
