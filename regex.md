## REGEX Examples


|  PATTERN	                                | REPLACE  	                                                          | DESCRIPTION  	                              |
|---      	                                |---      	                                                          |---	                                        |
|  ([\?-\\\\"-\\/])istanbul             | $1                         | specific characters in head of string       |
|  ([\?\/])istanbul 	                | $1                           |  	                                        |
|  (?<=\\\\/[M\|m]{1}odules\\/).*?(?=(\\/\|$))    | $1                                                                  | string between two regex conditions         |
|  ^((?!merhaba).)*$									      | $1                                                                  | find what not contains specific string  	  |
|  ^((?!Base\\/Helpers\\/[M\|m]odule\\.php).)*$ | $1                                                                  | find what not contains specific regex       |
|  (?<=[\\$\|\\\\->])(parentKey)                 | $1  	                                                              | find a string starts with a pattern         |
|  (^#{1})\\s(?=(\\w))                | $1  	                                                              | find specific number character '#' ending with a space then continuing any alphabetic characters         |
