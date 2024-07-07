◆ PIXEL MANIPULATION FOR IMAGE ENCRYPTION:
Image encryption through pixel manipulation involves transforming the original image into an encrypted form by altering its pixel values in a systematic and reversible manner.

_Steps for Image Encryption:
1. Key Generation: Generate or obtain an encryption key. This key will be used to control the permutation and substitution processes.
2. Pixel Permutation: Rearrange the pixels of the image based on the encryption key. This step can involve complex patterns and algorithms to ensure that the permutation is not easily reversible without the key.
3. Pixel Value Substitution: Modify the pixel values using a function controlled by the encryption key. This can be done in several ways, such as adding a pseudorandom number to each pixel value.
4. Bit Plane Manipulation (Optional): Further scramble the image by manipulating its bit planes according to the key.

_Steps for Image Decryption:
1. Key Retrieval: Obtain the correct decryption key. The decryption key should match the encryption key or be derivable from it.
2. Inverse Pixel Value Substitution: Reverse the pixel value modification by applying the inverse function used during encryption.
3. Inverse Pixel Permutation: Rearrange the pixels back to their original positions using the inverse permutation algorithm.
4. Bit Plane Reassembly (Optional): Reassemble the bit planes back into the original form.
