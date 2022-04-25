# Public pgp keys

If you want to send me an encrypted email, you can use one of the following pgp keys:

| pgp public key file |
|-------------- |
| `pavelsam.pub` |
| `samanpavel-gmail.pub` |
| `samanpavel-proton.pub` |
| `psaman-cisco.pub` |
| `psaman-slido.pub` |

# Public ssh keys

If you want to send me an encrypted file, you can use `id_rsa_files.pub` public key.

You can use [age](https://github.com/FiloSottile/age) to encrypt the file(s):

```
$ age -R id_rsa_files.pub file-to-encrypt > encrypted-file.age
```
