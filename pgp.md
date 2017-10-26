---
layout: page
title: PGP
permalink: /pgp/
---

{% highlight bash %}

-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

eric@rasmus ~ $ gpg --fingerprint "Eric Parra"
pub   ed25519 2017-10-25 [SC] [expires: 2019-10-25]
      7B74 5C30 7FA6 C2E4 6F0A  648C 0676 42AE C0D9 3842
uid           [ultimate] Eric Parra <parra@csu.fullerton.edu>
sub   cv25519 2017-10-25 [E] [expires: 2019-10-25]

eric@rasmus ~ $ gpg --armor --export 7B745C307FA6C2E46F0A648C067642AEC0D93842
- -----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEWe/6oRYJKwYBBAHaRw8BAQdA204Dr3WSsKdxxAUFUXbnt8UAS3H4+/mNMR/5
fJ+hIkK0JEVyaWMgUGFycmEgPHBhcnJhQGNzdS5mdWxsZXJ0b24uZWR1PoiWBBMW
CAA+FiEEe3RcMH+mwuRvCmSMBnZCrsDZOEIFAlnv+qECGwMFCQPCZwAFCwkIBwIG
FQgJCgsCBBYCAwECHgECF4AACgkQBnZCrsDZOEIidAEA3zPrlmL0xSFIyD0/bQdy
AN3vMeY6rdKMe5b0f268VTIBAPgeRf2m0j9h2fs5AlNVpQbxCzqCUGMDf3Tc8/0o
MvMEuDgEWe/6oRIKKwYBBAGXVQEFAQEHQAWbXXEMU34+uvLe77HMhELRlVB0Stla
+gWLN8TABEgrAwEIB4h+BBgWCAAmFiEEe3RcMH+mwuRvCmSMBnZCrsDZOEIFAlnv
+qECGwwFCQPCZwAACgkQBnZCrsDZOEKKkgD8CAOSkYcw08lGufh7Pu+qK/AXjoPB
TqaUv6mHH4254AEBANH41TxPSzSTZsCAwyl7E6FlP6fUjq+Gc86jv1nTFLcK
=puv0
- -----END PGP PUBLIC KEY BLOCK-----
-----BEGIN PGP SIGNATURE-----

iHUEARYIAB0WIQR7dFwwf6bC5G8KZIwGdkKuwNk4QgUCWfIbtgAKCRAGdkKuwNk4
Qh7AAP9EpD+w+VhTCX9cwyYSSQ3fmQ5u4EORCojTHsdggn8oQgEAlVJ4wKkB7wCp
aL26a3Gi3kR44Zc79rWiVR1GfsHTNQQ=
=Oz4y
-----END PGP SIGNATURE-----

{% endhighlight %}

[Commits to this page](https://github.com/eaparra/eaparra.github.io/commits/master/pgp.md) **shall** be verified by the preceding PGP key. Communicate in confidence ... with confidence!
