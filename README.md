This problem is an extension of the original minimal prime problem (see https://cs.uwaterloo.ca/~cbright/reports/mepn.pdf https://www.primepuzzles.net/puzzles/puzz_178.htm https://github.com/curtisbright/mepn-data/tree/master/data https://github.com/RaymondDevillers/primes), to include the CRUS Sierpinski/Riesel conjectures base b (see http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm and http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm) with k-values < b

The original minimal prime base b problem does not cover CRUS Sierpinski/Riesel conjectures base b with CK < b (such Riesel bases are 14, 20, 29, 32, 34, 38, 41, 44, 47, 50, 54, 56, 59, 62, 64, 65, 68, 69, 74, 77, 81, 83, 84, 86, 89, 90, 92, 94, 98, 104, 110, 113, 114, 116, 118, 119, 122, 125, 128, 129, 131, 132, 134, 137, 139, 140, 142, 144, 146, 149, 152, 153, 155, 158, 164, 167, 170, 173, 174, 176, 178, 179, 182, 184, 185, 186, 188, 189, 194, 197, 200, 202, 203, 204, 206, 208, 209, 212, 214, 216, 218, 219, 221, 224, 227, 229, 230, 233, 234, 236, 237, 239, 242, 244, 245, 246, 248, 251, 252, 254, 257, 258, 259, 260, 263, 264, 265, 266, 269, 272, 274, 275, 278, 279, 284, 285, 286, 289, 290, 293, 294, 296, 298, 299, 300, ..., and such Sierpinski bases are 14, 20, 29, 32, 34, 38, 41, 44, 47, 50, 54, 56, 59, 62, 64, 65, 68, 69, 74, 76, 77, 83, 84, 86, 89, 90, 92, 94, 98, 101, 104, 109, 110, 113, 114, 116, 118, 119, 122, 125, 128, 129, 131, 132, 134, 137, 139, 140, 142, 144, 146, 149, 152, 153, 154, 155, 158, 159, 160, 164, 167, 169, 170, 172, 173, 174, 176, 179, 181, 182, 184, 185, 186, 188, 189, 194, 197, 200, 202, 203, 204, 206, 208, 209, 212, 214, 216, 218, 219, 220, 221, 224, 227, 229, 230, 233, 234, 236, 237, 239, 242, 244, 245, 246, 248, 251, 252, 254, 257, 258, 259, 260, 263, 264, 265, 266, 269, 272, 274, 275, 278, 279, 281, 284, 285, 289, 290, 293, 294, 296, 298, 299, 300, ...), since in Riesel side, the prime is not minimal prime if either k-1 or b-1 (or both) is prime, and in Sierpinski side, the prime is not minimal prime if k is prime, but this extended version of minimal prime base b problem does, this version requires a restriction of prime > b, i.e. primes should have >=2 digits (and should not be "10", i.e. should not equal to the base (b)), and the single-digit primes (including the k-1, b-1, k) are not allowed.

CRUS requires exponent n>=1 for these primes, n=0 is not acceptable to avoid the trivial primes (e.g. 2\*b^n+1, 4\*b^n+1, 6\*b^n+1, 10\*b^n+1, 12\*b^n+1, 3\*b^n-1, 4\*b^n-1, 6\*b^n-1, 8\*b^n-1, 12\*b^n-1, ... cannot be quickly eliminated with n=0, or the conjectures become much more easy and uninteresting). For the same reason, this minimal prime problem requires >base (i.e. >=2 digits) for these primes, single-digit primes are not acceptable to avoid the trivial primes (e.g. simple families containing digit 2, 3, 5, 7, B, D, H, J, N, ... cannot be quickly eliminated with the single-digit prime, or the conjectures become much more easy and uninteresting)

Minimal primes > base, but single-digit prime (and the prime "10", i.e. the prime equal to base) substrings are allowed.

Left/Right-truncatable primes >= base, but the single-digit suffix/prefix (i.e. the leftmost digit of right-truncatable primes, or the rightmost digit of left-truncatable primes) need not to be prime.

Definition in these problems:

Minimal primes: Primes for which there is no shorter sub-sequence with length >=2 of the digits that form a prime.

Left-truncatable primes: Primes that remain prime when the leading digit is successively removed until becoming a single-digit number (numbers with leading zeros are consider as nonprimes, to avoid trivial examples, such as 10^60+7 in base 10).

RIght-truncatable primes: Primes that remain prime when the least significant digit is successively removed until becoming a single-digit number.

References:

Minimal primes:

https://docs.google.com/document/d/e/2PACX-1vQct6Hx-IkJd5-iIuDuOKkKdw2teGmmHW-P75MPaxqBXB37u0odFBml5rx0PoLa0odTyuW67N_vn96J/pub

https://mersenneforum.org/attachment.php?attachmentid=24177&d=1610562701

https://mersenneforum.org/attachment.php?attachmentid=24180&d=1610587279

https://mersenneforum.org/showthread.php?t=24972

https://primes.utm.edu/curios/page.php?number_id=22380

Left-truncatable primes:

https://fellis.wescreates.wesleyan.edu/research/publications/JRM_30_177_2000.pdf

Right-truncatable primes:

https://codegolf.meta.stackexchange.com/questions/2140/sandbox-for-proposed-challenges/17229#17229

https://hlma.math.cuhk.edu.hk/wp-content/uploads/2018/06/a90bcf7cf0e95d023687faea1b2408fa.pdf

Also see https://github.com/xayahrainie4793/minimal-primes-and-left-right-truncatable-primes (the same problem when single-digit primes are included) for more references.
