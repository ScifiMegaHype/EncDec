# EncDec

'A package that allows to encrypt and decrypt string data using a unique key of your choice. Gives developers more control over their encryption'

# Test

original = 'Fire is an animal=+TiPi never remembers?/...'

print(f'Original: {original}')

print(f'\nEncryptedv1: {encsimple(original)}')
print(f'Decryptedv1: {decsimple(encsimple(original))}')

toPrint = enccomplex(original, 0)
print('\nEncryptedv2:', toPrint)
print('Decryptedv2:', deccomplex(toPrint, 0))