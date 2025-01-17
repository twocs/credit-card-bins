| Scheme/Network                        | Brand                                 | Bin                                            | Length  | Pattern |
| ------------------------------------- | ------------------------------------- | ---------------------------------------------- | ------- | ------- |
| Amex                                  | American Express                      | 34, 37                                         | 15      | ```/^(34\|37)[0-9]{13}$/```                          |
|                                       | Aura                                  | 50                                             | 16      | ```/^(50)[0-9]{14}$/```                              |
|                                       | China T-Union                         | 31                                             | 19      | ```/^(31)[0-9]{17}$/```                              |
|                                       | China UnionPay                        | 62                                             | 16-19   | ```/^(62)[0-9]{14,17}$/```                           |
| Discover                              | Diners Club International             | 36                                             | 14-19   | ```/^26[0-9]{12,17}$/```                             |
| Diners Club United States & Canada    | 54                                             | 16      | ```/^54[0-9]{14}$/```                                |
| Discover                              | 300, 301, 302, 303, 304, 305, 36, 38, 39       | 14      | ```/^30[0-5]{1}[0-9]{11}\|(36\|38\|39)[0-9]{12}$/``` |
| Discover Card                         | 6011, 644-649, 65                              | 16      | ```/^(6011[0-9]{12}\|64[4-9]{13}\|65[0-9]{14}$/```   |
| Unionpay          | Discover (China UnionPay co-branded)  | 622126–622925 | 16-19 | ```^622(1[2-9][6-9]\|[2-8][0-9][0-9]\|9[0-1][0-9]\|92[0-5])[0-9]{10,13}```               |
| Elo               |  Visa                                      | 401178, 401179, 431274, 438935, 451416, 4573, 4576, 506, 509, 636, 6500, 6504, 6505, 6507, 6509, 6516, 6550, 504175, 627780 | 16 | ```/^(506|509|636)[0-9]{13}|(4573|4576|6500|6504|6505|6507|6509|6516|6550)[0-9]{12}|(401178|401179|431274|438935|451416|504175|627780)[0-9]{10}$/``` |
| Hiper         | 637095, 637599, 637609, 637612, 637600, 637568 | 16      | ```/^637(095\|568\|599\|600\|609\|612)[0-9]{10}$/``` |
| Hipercard     | 606282                                         | 16      | ```/^606282[0-9]{10}$/``` |
| JCB           | 3088, 3096, 3112, 3158, 3337, 35               | 16      | ```/^(3088\|3096\|3112\|3158\|3337)[0-9]{12}\|(35)[0-9]{14}$/``` |
| Mastercard    | 5, 2                                           | 16      | ```/^(2\|5)[0-9]{15}$/``` |
| Visa          | 4                                              | 13, 16  | ```/^4[0-9]{12,15}$/``` |

_Official data from the two of the largest acquirers in the world and from the largest bank in Latin America._

_Dados oficiais dos dois maiores adquirentes de cartões de crédito do mundo e do maior banco da América Latina._

## To do
- [ ] Identify other credit card brands

## Contribute

Make a repository fork, make your changes and [submit a pull request](https://github.com/Marjoel/credit-card-bins/pulls "Click here to create a pull request").<br>
Is there incorrect information? [Submit an issue](https://github.com/Marjoel/credit-card-bins/issues "Click here to create an issue").

### Contributors

[Marjoel Moreira](https://www.marjoel.com/ "Marjoel Moreira") (@[MarjoeM](https://www.twitter.com/MarjoelM "Twitter"))


TODO: [https://www.bincodes.com/bin-list/](https://www.bincodes.com/bin-list/)
