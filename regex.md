## REGEX Examples


|  PATTERN	                                | REPLACE  	                                                          | DESCRIPTION  	                              |
|---      	                                |---      	                                                          |---	                                        |
|  ([\?-\\\\"-\\/])istanbul-balat              | $1istanbul-avrupa-yakasi-balat-sanal-ofis                           | specific characters in head of string       |
|  ([\?\/])istanbul-balat 	                | $1istanbul-avrupa-yakasi-balat-sanal-ofis                           |  	                                        |
|  (?<=\\\\/[M\|m]{1}odules\\/).*?(?=(\\/|$))    | $1                                                                  | string between two regex conditions         |
|  ^((?!merhaba).)*$									      | $1                                                                  | find what not contains specific string  	  |
|  ^((?!Base\\/Helpers\\/[M\|m]odule\\.php).)*$ | $1                                                                  | find what not contains specific regex       |
|  (?<=[\\$\|\\\\->])(parentKey)                 | $1  	                                                              | find a string starts with a pattern         |
